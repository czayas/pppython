# El Paradigma Estructurado

## Estructuras jerárquicas de flujo

En la programación estructurada se utilizan únicamente tres tipos de estructuras: **secuencia**, **selección** e **iteración**, siendo innecesario el uso de instrucciones de transferencia incondicional como GOTO, GOSUB o EXIT que actualmente están casi en desuso.

**Estructura secuencial**: Las instrucciones se ejecutan una tras otra, a modo de secuencia lineal. Una instrucción no se ejecuta hasta que finaliza la anterior, ni se bifurca el flujo del programa.

```py
nombre = input('¿Cuál es tu nombre? ')
print('Hola,', nombre)
```

**Estructura selectiva**: La ejecución del programa se bifurca a una instrucción \(o conjunto\) u otra\(s\) según un criterio o condición lógica establecida. Sólo uno de los caminos en la bifurcación será el tomado para ejecutarse.

Palabras reservadas de Python: `if-else-elif`

```py
nombre = input('¿Cuál es tu nombre? ')
if nombre.isdigit():
    print('Dije nombre, no edad...')
elif nombre:
    print('Hola,',nombre)
else:
    print('No seas timido...')
```

**Estructura iterativa**: Dada una secuencia de instrucciones, un bucle iterativo o iteración hace que se repita su ejecución mientras se cumpla una condición. El número de iteraciones normalmente está determinado por el cambio en la condición dentro del mismo bucle, aunque puede ser forzado o explícito por otra condición.

Palabras reservadas de Python: `for, while`

```py
nombre = 'x'
while nombre:
    nombre = input('¿Cuál es tu nombre? ')
    if nombre.isdigit():
        print('Dije nombre, no edad...')
    elif nombre:
        print('Hola,', nombre)
        vocales = 0
        for letra in nombre:
            if letra in 'aeiou':
                vocales += 1
        print('Tu nombre tiene',vocales,'vocales')
    else:
        print('No seas timido...')
```



