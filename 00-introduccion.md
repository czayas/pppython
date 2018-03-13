# Introducción

## ¿Qué es un paradigma?

La palabra “paradigma” proviene del griego pará \(junto\) y deigma \(modelo\), y significa algo así como “demostración de un modelo”.

Un paradigma es un esquema formal de organización, un marco teórico, un conjunto de teorías alrededor de un tema determinado.

## ¿Qué es un lenguaje?

Un lenguaje, en su sentido natural, es un método humano, no instintivo, que sirve para comunicar ideas, emociones y deseos mediante un sistema de símbolos producidos voluntariamente.

Un lenguaje, en su sentido formal, es aquel que tiene una gramática que consta de un vocabulario de símbolos, reglas sintácticas \(combinaciones\) y reglas semánticas \(significado\).

El lenguaje, en general, es entonces un conjunto de objetos \(vocabulario\) capaces de ser combinados de acuerdo a ciertas reglas \(gramática\) con el fin de comunicarse con un receptor.

## ¿Qué es un programa?

Un programa, en un contexto informático, es una secuencia de instrucciones que permiten realizar una tarea específica con una computadora.

Dichas instrucciones primero son escritas por un programador en un lenguaje de programación para luego ser convertidas en un formato procesable por la computadora.

* En su forma legible para el ser humano, el programa se denomina **código fuente**.
* En su forma procesable por la computadora, el programa se denomina **código ejecutable**.

Para que un programa escrito en un lenguaje de programación “humano” \(de alto nivel\) pueda ser ejecutado, éste debe convertirse a **código máquina** mediante un programa traductor que funciona como intérprete \(traduce y ejecuta cada instrucción\) o compilador \(traduce y guarda las instrucciones en código máquina en un archivo nuevo\).

La conversión del código fuente al código ejecutable se realiza mediante uno de estos procesos:

* El **intérprete** es un programa que traduce y ejecuta secuencialmente cada una de las instrucciones del código fuente, sin conservar el resultado de dicha traducción.
* El **compilador** es un programa que traduce el código fuente y genera un nuevo programa escrito en un lenguaje de nivel inferior, típicamente lenguaje de máquina.

Un intérprete ofrece al programador más flexibilidad en su entorno de programación, y al programa un entorno de ejecución independiente de la máquina donde se ejecuta, lo que se conoce comúnmente como máquina virtual.

Un compilador, por su parte, permite que un programador pueda diseñar un programa en un lenguaje mucho más cercano a como piensa un ser humano, para luego convertirlo a un programa que pueda ser procesable directamente por una computadora.

## Código binario

El código binario es el sistema de representación de instrucciones y datos que utiliza un dispositivo electrónico. Se basa en el sistema de numeración binario \(de dos dígitos, “0” y “1”\) que representan los dos únicos niveles de tensión que usan los circuitos electrónicos.

La unidad básica de información del código binario es el **bit** \(binary digit\) que es una variable cuyo valor almacenado puede representar sólo a uno de dos posibles estados: encendido/apagado, verdadero/falso, sí/no, etc.

El código binario puede representar cualquier tipo de información, por ejemplo la letra minúscula “a” en la tabla ASCII \(_American Standard Code for Information Interchange_\) está representada por la cadena de bits “01100001” que tiene un valor decimal de 97.

## Arquitectura del conjunto de instrucciones

Del inglés “Instruction Set Architecture” \(ISA\) es una especificación que detalla las instrucciones que una CPU en particular puede interpretar y ejecutar.

ISA es la parte de la arquitectura de hardware relacionada con la programación, e incluye los tipos de datos, instrucciones, registros, modos de direccionamiento, arquitectura de memoria, interrupciones y manejo de excepciones.

## Lenguaje de programación

Un lenguaje de programación es un subconjunto de los lenguajes formales que le permite al ser humano comunicarse con una computadora \(receptor\) para indicarle a ésta qué es lo que debe hacer.

Se puede considerar a un lenguaje de programación como una **capa de abstracción** que le protege al ser humano \(programador\) de las complejidades o particularidades de la computadora. Esa capa le presenta al programador una **máquina virtual** que le resulta mucho más fácil de comprender que la máquina real.

## Lenguaje de máquina

El lenguaje de máquina es un sistema de instrucciones que pueden ser ejecutadas directamente por una unidad central de procesamiento \(microprocesador\). Se lo considera un lenguaje de programación primitivo e incómodo, por estar basado directamente en la lógica digital y por no haber un único lenguaje de máquina, sino que cada arquitectura de hardware cuenta con el suyo.

El código máquina a veces se denomina código nativo, por haber partes que dependen de una plataforma de hardware en particular. No debe confundirse al código máquina con bytecode \(código de bytes\) ya que este último es un código intermedio que se ejecuta a través de un intérprete o máquina virtual, no directamente por la CPU.

## Ensamblador

El término “ensamblador” puede referirse a un programa especial o a un lenguaje de programación \(Assembly\). El Assembly o Ensamblador es un tipo de lenguaje de bajo nivel \(cercano al hardware\) que permite una representación un poco más abstracta de las instrucciones en código máquina.

El programa ensamblador es capaz de leer un archivo con instrucciones escritas en lenguaje Assembly y traducirlas a código máquina, para posteriormente almacenarlas en un nuevo archivo, denominado objeto o ejecutable.

Los ensambladores fueron creados para facilitar la escritura de programas en código máquina, ya que hacerlo en código binario resulta muy complicado para el ser humano.

## Máquina virtual

Una máquina virtual es una implementación en software de una máquina real o física \(hardware\). Dicha máquina virtual debe poder ejecutar órdenes diseñadas para la máquina real.

Lo que comúnmente se entiende por máquina virtual es lo que en términos técnicos más específicos se conoce como máquina virtual **de sistema**, que permite compartir los recursos físicos \(hardware\) entre distintas máquinas virtuales, cada una de ellas funcionando sobre su propio sistema operativo.

Los lenguajes de programación pueden considerarse máquinas virtuales de un tipo especial, denominado máquina virtual **de proceso** o **de aplicación**, debido a que funcionan sobre un sistema operativo y soportan un único proceso.

Un lenguaje de programación provee al programador de un entorno de desarrollo independiente de la plataforma \(hardware + sistema operativo\) lo que al menos en teoría permite que un mismo programa funcione en cualquiera de ellas.

## Tipado de datos

Un sistema de tipos \(o tipado de datos\) define cómo un lenguaje de programación clasifica los valores y las expresiones en tipos, cómo se pueden manipular estos tipos y cómo interactúan.

Un tipo indica un conjunto de valores que tienen el mismo significado genérico o propósito.

Los sistemas de tipificación varían significativamente entre lenguajes, siendo quizás las más importantes variaciones las implementadas en tiempo de **compilación** y en tiempo de **ejecución**.

Los tipados, de acuerdo a criterios determinados, pueden categorizarse en:

* **Fuerte** y **débil** \(según cómo se combinan los datos\)
* **Estático** y **dinámico** \(según cuándo se comprueban los tipos de datos\)
* **Explícito** e **implícito** \(según si se declaran o no los datos\)

### Strong typing

Un lenguaje de programación es **fuertemente tipado** si no se permiten violaciones de los tipos de datos, es decir, dada una variable de un tipo concreto, no se puede usar como si fuera una variable de otro tipo distinto a menos que se haga una conversión.

No hay una única definición de este término. Un lenguaje que no es fuertemente tipado se dice que no está tipado. La mayoría de los lenguajes imperativos son fuertemente tipados mientras que los lenguajes declarativos no suelen estar tipados.

Algunos de los lenguajes fuertemente tipados son: C++, C\#, Java, Python.

Ejemplo \(en seudocódigo\):

`a = 2`

`b = "2"`

`concatenar(a, b)      # Type Error`

`sumar(a, b)           # Type Error`

`concatenar(str(a), b) # Retorna "22"`

`sumar(a, int(b))      # Retorna 4`

### Weak typing

Los lenguajes de programación no tipados o **débilmente tipados** no controlan los tipos de las variables que declaran, de este modo, es posible usar variables de cualquier tipo en un mismo escenario. Por ejemplo, una función puede recibir como parámetro un valor entero, cadena de caracteres, flotante...

No hay que confundir el término con los lenguajes de tipado dinámico, en los que no se declaran los tipos de las variables sino se deciden en tiempo de ejecución, si bien es cierto que muchos lenguajes de este tipo son también no tipados.

Algunos de los lenguajes débilmente tipados son: BASIC, JavaScript, Perl, PHP.

Ejemplo \(en seudocódigo\):

`a = 2`

`b = "2"`

`concatenar(a, b) # Retorna "22"`

`sumar(a, b)      # Retorna 4`

### Static typing

Se dice de un lenguaje de programación que usa un **tipado estático** cuando el chequeo de tipificación se realiza durante el tiempo de **compilación**, opuesto al de ejecución.

Comparado con el tipado dinámico, el estático permite que los errores de programación sean detectados antes, y que la ejecución del programa sea más eficiente.

Ejemplos de lenguajes que usan tipado estático son C, C++, Java y Haskell.

### Dynamic typing

Un lenguaje de programación tiene **tipado dinámico** si una misma variable puede tomar valores de distinto tipo en distintos momentos durante la ejecución.

La separación entre tipado estático y dinámico se suele confundir con la diferencia entre lenguajes fuertemente tipados y lenguajes débilmente o no tipados.

La mayoría de los lenguajes de tipado dinámico son lenguajes interpretados, como Python o Ruby.

### Duck typing

En los lenguajes de programación orientados a objetos, se conoce como _duck typing_ o **tipado de pato** al estilo de tipificación dinámica de datos en que el conjunto actual de métodos y propiedades determina la validez semántica, en vez de que lo hagan la herencia de una clase en particular o la implementación de una interfaz específica.

El nombre del concepto se refiere a la prueba del pato, una humorada de razonamiento inductivo atribuida a James Whitcomb Riley, que es como sigue: _“Cuando veo un ave que camina como un pato, nada como un pato y suena como un pato, a esa ave yo la llamo un pato.”_

Python es un buen ejemplo de lenguaje de programación que implementa el _duck typing_.

