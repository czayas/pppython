# El lenguaje de programación Python

## ¿Qué es Python?

[Python](https://es.wikipedia.org/wiki/Python) es un lenguaje de programación de [alto nivel](https://es.wikipedia.org/wiki/Lenguaje_de_alto_nivel), [interpretado](https://es.wikipedia.org/wiki/Intérprete_%28informática%29), [multiparadigma](https://es.wikipedia.org/wiki/Lenguaje_de_programación_multiparadigma), [dinámico](https://es.wikipedia.org/wiki/Tipado_dinámico) y [fuertemente tipado](https://es.wikipedia.org/wiki/Tipado_fuerte), creado en 1991 por el programador holandés Guido van Rossum, basado en un fuerte énfasis en la simplicidad y legibilidad del código, para así hacer posible el desarrollo rápido de aplicaciones.

La mayoría de las veces, un programador experimentado en Python es capaz de escribir una cantidad considerablemente menor de líneas de código para realizar la misma tarea comparada con otros lenguajes. Esto conlleva a menos errores de programación y reduce el tiempo necesario para el desarrollo de un proyecto.

Otra ventaja de Python la constituye su enorme biblioteca de módulos, distribuida entre los que comprenden la llamada **Biblioteca Estándar** \([_Python Standard Library_](http://docs.python.org.ar/tutorial/3/stdlib.html)\) y los desarrollados por terceras partes, disponibles en el **Índice de Paquetes** \([PyPI](https://es.wikipedia.org/wiki/Python_Package_Index): Python Package Index\) e instalables mediante el administrador de paquetes [pip](https://es.wikipedia.org/wiki/Pip_%28administrador_de_paquetes%29).

## ¿Qué se necesita para programar en Python?

Python está disponible para prácticamente todos los sistemas operativos, y suele venir incluido en la mayoría de las distribuciones Linux, por lo tanto es probable que muchos usuarios ya tengan en su equipo todo lo necesario para poder empezar a programar en este lenguaje. De no ser así, puede descargarse el instalador necesario en [https://www.python.org/downloads/](https://www.python.org/downloads/)

En nuestra asignatura, usaremos la versión 3 de Python, a pesar de que la versión 2 sigue siendo muy popular al momento de escribir ésto, pero las diferencias entre ambas versiones no son muy notables, hasta el punto de que es posible escribir programas que sean completamente compatibles con cualquier versión.

Para que la experiencia con Python sea más cómoda, se recomienda usar un editor o IDE \(_Integrated Development Environment_, entorno integrado de desarrollo\) que tenga a Python entre los lenguajes de programación soportados.

## El modo interactivo

Python cuenta con un **modo interactivo** donde el programador puede introducir directamente por teclado una instrucción para ser evaluada y ejecutada inmediatamente por el intérprete.

El modo interactivo constituye una valiosa herramienta para el programador, ya que le permite aprender nuevos conceptos y probar ideas antes de incorporarlas al código de la aplicación que está desarrollando.

```
Python 3.6.4 (default, Mar  5 2018, 12:14:58) 
[GCC 7.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> "Hola, Mundo.".upper()
'HOLA, MUNDO.'
>>> 2+3
5
>>> for i, e in enumerate([1,2,3,4,5]): print("{}:{}".format(i, e))
... 
0:1
1:2
2:3
3:4
4:5
>>>
```



