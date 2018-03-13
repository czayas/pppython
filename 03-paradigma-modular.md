# El Paradigma Modular

## ¿Qué es un módulo?

Un módulo es cada una de las partes de un programa que resuelve uno de los subproblemas en que se divide el problema complejo original. Cada uno de estos módulos tiene una tarea bien definida y algunos necesitan de otros para poder operar.

## Entrada-Proceso-Salida

Cada módulo puede o no aceptar valores de entrada y retornar valores de salida. El proceso interno puede o no estar relacionado con dichos valores. Los valores de entrada se denominan indistintamente **parámetros**, **argumentos** o **atributos**.

## Divide y vencerás \(top-down\)

Top-down es una técnica de refinamiento sucesivo o análisis descendente, donde un problema complejo debe ser dividido en varios subproblemas más simples, y éstos a su vez en otros subproblemas más simples. Esto debe hacerse hasta obtener subproblemas lo suficientemente simples como para poder ser resueltos fácilmente con algún lenguaje de programación.

## Procedimientos y funciones

Son subprogramas, también denominados submódulos, ya que en algunos lenguajes, como por ejemplo Python, se considera como módulo a un conjunto de subprogramas.

Un **procedimiento** es básicamente una función que no retorna ningún valor. Una **función** siempre retorna un valor al programa que la llamó. Tanto los procedimientos como las funciones pueden o no aceptar parámetros de entrada.

Palabras reservadas de Python: `import, def, return, yield`

```py
import random
def azar(limite):
    return random.randint(1,limite)
def genazar(limite):
    yield random.randint(1,limite)
def par(numero):
    return numero % 2 == 0
def pares(limite):
    for numero in range(limite):
        if numero % 2 == 0:
            yield numero
```



