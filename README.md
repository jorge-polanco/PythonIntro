Co-authored-by: Aldo Maldonado Hernadez 165459
Co-authored-by: Diego García Aldaco 170908
Co-authored-by: Luis Julian Alvarez Armenta 163247


Co-authored-by: AUTHOR-NAME <ANOTHER-NAME@EXAMPLE.COM>"



### Introduction

- En este tutorial vamos a aprender como usar  jupyter.


# Python.md




**Table of Contents**

[ TOCM ]

[TOC]

# Instalar Anaconda
Ve al sitio web de Anaconda (https://www.anaconda.com/products/individual) y descargua el instalador de Anaconda para tu computadora,
una vez completada la descarga, ejecuta el instalador haciendo doble clic en el archivo descargado. Sigue las instrucciones del asistente de instalación para completar la instalación. Puedes elegir la configuración predeterminada o personalizarla como prefieras al igual de donde se almacenarán los datos del programa. Una vez completada la instalación, puedes abrir anaconda buscándolo en tus aplicaciones o usando el acceso directo que se generará en el escritorio. Una vez te encuentres en el Anaconda Navigator, puedes buscar Jupyter Notebook e iniciarlo dando clic en “iniciar”, esto abrirá una pestaña en el navegador web


## Introducción a Python, cómo escribir código y ejecutarlo
 <br>
1-Abre Anaconda y selecciona el entorno en el que deseas trabajar.

2-En la pestaña "Home", haz clic en el botón "Launch" debajo de "Jupyter Notebook".

3-Se abrirá una nueva ventana del navegador con el panel de control de Jupyter Notebook.

4-Haz clic en el botón "New" en la esquina superior derecha y selecciona "Python 3" para crear un nuevo archivo de notebook de Python.

5-En el nuevo archivo de notebook, verás una celda vacía donde puedes escribir tu código.

6-Escribe tu código en la celda.

7-Para ejecutar el código, haz clic en la celda y presiona Shift + Enter o haz clic en el botón "Run" en la barra de herramientas.

8-El resultado se mostrará debajo de la celda.
 <br>

## Ejemplo Practico
Hello World Ejemplo
```sh
print("Hellow World")

```
Suma
```sh
a=10
b=5
addition= a+b
print(addition)
```
AAgregar Texto al notebook
(Recuerda cambiar la parte de Code por Markdown para que funcione )

```sh
<h1>Hellow World code <h1/>
```

## How to manage varibles, lists, dictionaries.


## Manejo de variables

Los tipos de datos de python se usan para definir el tipo de variable. Los que soporta son: 
1. Tipos de dato numéricos: int, float, complex
2. Tipos de dato string: str
3. Tipo de dato de sequencia:listas, tuplas
4. Datos de mapeo: diccionarios

 El método *type()* sirve para imprimir a que tipo de dato pertenece una variable. A continuación se muestran ejemplos de declaración de estas variables mencionadas (P, 2023).
 

#Variables numéricas
number = 1234
pi = 3.1417
irrational = 100 +2j

#Variables string
greeting = "Hello World"
onequote = 'Hi!'

#Lista y tupla
everyDataList = [33, "Hello world", 1.618]
untouchable = ("Hi", 44, 22.324)

## Listas
Una lista en Python es un tipo de datos nativos construido dentro del lenguaje de programación Python. Estas listas son similares a matrices (o arrays) que se encuentran en otros lenguajes. Sin embargo, en Python se manejan como variables con muchos elementos. Las listas tienen las siguientes características principales:

1.Ordenada: esto quiere decir que los elementos dentro de ella están indexados y se accede a ellos a través de una locación indexada. 

2. Editable: los elementos dentro de una lista pueden editarse, añadir nuevos o eliminar los que ya tiene. 

3. Dinámica: las listas pueden contener diferentes tipos de datos y hasta de objetos. Esto significa que pueden soportar paquetes multidimensionales de datos, como un array o muchos objetos. 

4. No única: esencialmente, esto quiere decir que la lista puede contener elementos duplicados sin que arroje un error (Londoño,2023). 

Las listas poseen la ventaja de ser altamente manipulables a a través de métodos ya integrados en Python. A continuación se ofrece una lista de los métodos más comunes junto con su descripción.
1. append(): Agrega un elemento al final de la lista
2. clear(): Elimina todos los elementos de la lista
3. copy(): Devuelve una copia de la lsita
4. count(): Devuelve el número de elementos del valro que se dio como argumento.
5. extend(): Agrega los elementos de la lista (o de cualquier iterable) al final del a lista actual.
6. index(): Devuelve el índice del primer elemento con el valor específicado
7. insert(): Agrega un elemento en la posición dada
8. pop(): Quita el elemento de la posición dada
9. remove(): quita el elemento con el valor dado
10. reverse(): invierte el orden de la lista
11. sort(): ordena la lista

## Diccionarios 
Los diccionarios en Python nos permiten almacenar una serie de mapeos entre dos conjuntos de elementos, llamados keys and values (Claves y Valores).
De igual forma, posee ciertas características.

1.Todos los elementos en el diccionario se encuentran encerrados en un par de corchetes {}
2.Cada elemento en un diccionario contiene una clave y un valor - es decir un par de clave-valor
3.Cada par de clave-valor es denominado como elemento (item)
4. La ventaja de esto es que puedes acceder a todos los valores almacenados 
usando simplemente las claves (Torres,2021)

A continuación se presenta un ejemplo de declaración de un diccionario.

numVariables = {
                "integer": number, 
                "rational": pi,
                "complex": irrational,
                "string": greeting
                }


## How to create subroutines and execute them.

## Error management and configuration issues.
# Manejo de errores

Parar saber manejar errores primero debemos conocer que python contiene excepciones integradas en las cuales se pueden consultar ingresando ell siguiente commando dentro de nuestro ambiente de desarrollo:
```ruby
print(dir(locals()['__builtins__']))
```
Dentro de las cuales en la siguiente tabla se muestran algunos errores junto con la causa por lo cual se generan

| Error |Causa del error|
|-------|-------------|
| AssertionError | Se genera cuando falla una instrucción `assert` |
| AttributeError | Se genera cuando falla la asignación de atributos o la referencia|
| EOFError | Se genera cuando la función `input()` alcanza la condición de fin de archivo|
| FloatingPointError | Se genera cuando falla una operación de punto flotante |
| GeneratorExit | Se genera cuando `close()` se llama al método de un generador |
| ImportError | Se genera cuando no se encuentra el módulo importado |
| IndexError | Se genera cuando el índice de una secuencia está fuera de rango |
| KeyError | Se genera cuando una clave no se encuentra en un diccionario |
| KeyboardInterrupt | Se genera cuando el usuario pulsa la tecla de interrupción (Ctrl+C o Delete) |
| MemoryError | Se genera cuando una operación se queda sin memoria |
| NameError | Se genera cuando una variable no se encuentra en el ámbito local o global |
| NotImplementedError | Generado por métodos abstractos. |
| OSError | Se genera cuando el funcionamiento del sistema provoca un error relacionado con el sistema |
| OverflowError | Se genera cuando el resultado de una operación aritmética es demasiado grande para ser representado |
| RuntimeError | Se genera cuando un error no pertenece a ninguna otra categoría |
| SyntaxError | Provocado por el analizador cuando se encuentra un error de sintaxis |
| IndentationError | Se levanta cuando hay una sangría incorrecta |
| TabError | Se genera cuando la sangría consiste en tabulaciones y espacios inconsistentes |
| SystemError | Se genera cuando el intérprete detecta un error interno |
| SystemExit | Generado por la función `sys.exit()` |
| TypeError | Se genera cuando se aplica una función u operación a un objeto de tipo incorrecto |
| ValueError | Se genera cuando una función obtiene un argumento del tipo correcto pero un valor incorrecto |
| ZeroDivisionError | Se genera cuando el segundo operando de la operación de división o módulo es cero |

Una vez contemplados las excepciones integradas en python, tenemos la posibilidad de personalizar el manejo de errores lo cuál es una buena práctica como programadores. Para empezar debemos saber que existen dos tipos de errores, el error de sintaxis y el error de excepción. La diferencia entre estos es que el error de sintaxis ocurre cuando al analizador detecta una declaración incorrecta, probemos con el siguiente ejemplo de código:
```ruby
print( 0 / 0 ))
```
Donde si lo compilamos, nos arroja lo siguiente:
```ruby
File "<stdin>", line 1
    print( 0 / 0 ))
                  ^
SyntaxError: invalid syntax
```
Lo cual indica que el analizador encontró que hay un paréntesis extra el cual está incompleto ya que no está encapsulando a un comando en específico. Por otro lado, el error de excepción ocurre cuando el código Python está sintácticamente correcto pero da como resultado un error, para compobarlo, probemos con el siguiente ejemplo:
```ruby
print( 0 / 0 )
```
Si lo compilamos, ahora nos da como resultado:
```ruby
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: integer division or modulo by zero
```
Lo que significa que el analizador no encontró errores de sintaxis, sin embargo, al compilar el código, se encontró la excepción de que la divisón no es válida ya que se está dividiendo sobre 0 lo cual matemáticamente no es válido.
# Excepción raise
Ya que ahora sabemos que existen dos tipos de errores, procederemos a manejar lo que son las excepciones comenzando con el commando `raise` que simplemente se encarga de lanzar una excepción de manera forzada al momento de cumplir cierta condición. Probemos con el siguiente ejemplo.
```ruby
x = 10
if x > 5:
    raise Exception('x should not exceed 5. The value of x was: {}'.format(x))
```
Por lo que al compilar, obtendremos lo siguiente:
```ruby
Traceback (most recent call last):
  File "<input>", line 4, in <module>
Exception: x should not exceed 5. The value of x was: 10
```
Lo cual explica que se lanzo la excepción programada debido a que se cumplió la condición de que el valor de x es mayor a 5, por el contrario, la excepción no se lanza y el código compila exitosamente.
# Assert
El commando `assert` se encarga de asegurar que una determinada condición se cumpla donde si la condición es verdadera, entonces el programa continua ejecutándose, en cambio, si es falso, el programa lanza una excepción tipo assert. Probemos con el siguiente código:
```ruby
ans = input("¿Are cats Mammals? (Y/N): ")
assert ans == "Y", "Wrong answer:cats are Mammals"
print("¡Correct answer!")
```
Esta excepción se encarga de verificar si nuestro sistema operativo es linux, por lo que si estamos en un sistema windows y lo compilamos, nos arroja lo siguiente:
```ruby
Traceback (most recent call last):
  File "<string>", line 2, in <module>
AssertionError: Wrong answer:cats are Mammals
```

# try y except
Los commandos `try` y `except` tienen un propósito similar al de if/else , donde try correrá el código que se encuentre dentro de su respectivo bloque mientras que si llegara el caso en el que se haya lanzado una excepción, el bloque except se activará y por lo tanto ejecutará todo código que se encuentre dentor de este bloque. Probemos con el ejemplo anterior colocando estos debajo de la función de la siguiente manera:
```ruby
def is_linux():
    return False;
def linux_interaction():
    assert is_linux(),"Function can only run on Linux systems"
    print('Doing something')
try:
    linux_interaction()
except AssertionError as error:
    print(error)
    print('The linux_interaction() function was not executed')
```
Por lo que al ejecutarlo en un sistema windows nos arrojará lo siguiente:
```ruby
Function can only run on Linux systems
The linux_interaction() function was not executed
```
Esto indica que el bloque try se ejecutó pero arrojo una excepción, por lo que el bloque except se activó y por lo tanto, mostró el error de assert de la función linux_iteraction() y después se imprimió que la función linux_iteraction() no se pudo ejecutar ya que dicha excepción se arrojo.

Por otra parte, que pasaría si usamos dos bloques except y un solo bloque try. Probemos con el siguiente ejemplo:
```ruby
def is_linux():
    return False;
def linux_interaction():
    assert is_linux(),"Function can only run on Linux systems"
    print('Doing something')
try:
    linux_interaction()
    with open('file.log') as file:
        read_data = file.read()
except FileNotFoundError as fnf_error:
    print(fnf_error)
except AssertionError as error:
    print(error)
    print('Linux linux_interaction() function was not executed')
```
Donde simularemos que podemos cambiar nuestro systema a linux, por lo que si ejecutamos el código nos arrojará lo siguiente:
```ruby
Function can only run on Linux systems
Linux linux_interaction() function was not executed
```
Esto ocurre debido a que como primero llamamos a la función de linux_interaction(), y en este caso devolvemos un valor falso al consultar si el sistema es linux, entonces, se lanza la excepción assert y se ignora la siguiente línea del bloque try y se pasa directamente al bloque de except que recibe la excepción assert y por lo tanto, se ejecuta el código dentro de este bloque. Ahora retornemos un valor vardadero dentro de is_linux() de la siguiente manera:
```ruby
def is_linux():
    return True;
```
y si compilamos nos arroja lo siguiente:
```ruby
[Errno 2] No such file or directory: 'file.log'
```
Lo que ocurrió en este caso fue que la función linux_interaction() se ejecutó exitosamente sin lanzar una excepción, por lo que paso a la siguiente línea del bloque try y al ejecutarse, se lanzó la excepción tipo FileNotFoundError ya que no pudo abrir una archivo con el nombre file.log y por lo tanto ahora se pasó al bloque except correspondiente a FileNotFoundError y se ejecutó el código dentro de este bloque que mando a imprimir el mensaje arrojado.

# Else
El comando `else` funciona como un segundo bloque try, pero este se ejecutará siempre y cuando todavía no se hayan lanzado excepciones en bloques anteriores a este, para probarlo, intentemos con el siguiente còdigo:
```ruby
def is_linux():
    return False;
def linux_interaction():
    assert is_linux(),"Function can only run on Linux systems"
    print('Doing something')
try:
    linux_interaction()
except AssertionError as error:
    print(error)
else:
    try:
        with open('file.log') as file:
            read_data = file.read()
    except FileNotFoundError as fnf_error:
        print(fnf_error)
```
y al compilarlo nos arrojará lo siguiente:
```ruby
Doing something.
[Errno 2] No such file or directory: 'file.log'
```
Esto implicó que el bloque try se ejecutó sin lanzar excepciones, por lo que el bloque except se ignoró y se pasó al bloque else y dentro de este al ejecutar el bloque try, se arrojó la excepción de que el archivo no fue encontrado y por lo tanto el siguiente bloque except se ejecutó, imprimiendo la excepción arrojada. Ahora si cambiamos nuestra función de is_linux() de la siguiente manera:
```ruby
def is_linux():
    return False;
```
al compilarlo nos arroja lo siguiente:
```ruby
Function can only run on Linux systems
```
Lo cual significa que el bloque try no se logró ejecutar exitosamente y por lo tanto lanzó una excepción y por lo que el bloque except se ejecutó imprimiendo la excepción, ignorando todo el código dentro del bloque else.


# Finally
Por último, el commando `finally` indica que todo el código dentro de este bloque se ejecutara siempre, sin importar si se lanzaron excepciones o no. Para comprobarlo probemos con el siguiente código:
```ruby
def is_linux():
    return False;
def linux_interaction():
    assert is_linux(),"Function can only run on Linux systems"
    print('Doing something')
try:
    linux_interaction()
except AssertionError as error:
    print(error)
else:
    try:
        with open('file.log') as file:
            read_data = file.read()
    except FileNotFoundError as fnf_error:
        print(fnf_error)
finally:
    print('Cleaning up, irrespective of any exceptions.')
```
Al compilarlo nos arrojará lo siguiente:
```ruby
Doing something.
[Errno 2] No such file or directory: 'file.log'
Cleaning up, irrespective of any exceptions.
```
Donde como se había dicho antes, el primer bloque try se ejecutó sin arrojar excepciones, por lo que se paso al bloque else y dentro de este, en el bloque try se arrojó una excepción y se ejecutó el bloque except siguiente y al final se ejecutó el bloque finally imprimiendo el mensaje dentro de este. En cambio si ahora retornamos un valor falso dentro de la función linus_interaction() de la siguiente manera:
```ruby
def is_linux():
    return False;
```
y compilamos, nos da el siguiente resultado:
```ruby
Function can only run on Linux systems
Cleaning up, irrespective of any exceptions.
```
Lo cual significa que el primer bloque try lanzó una excepción, por lo que se ejecuto el siguiente bloque except e ignorando todo el bloque else, por lo que se imprimió la excepción recibida y el mensaje contenido en el bloque finally, justificando que el bloque finally siempre se ejecutara sin importar si hubo excepciones o no.




## Bibliografía
Londoño, P. (2023, 13 febrero). Listas en Python: qué son, cómo crearlas y ordenarlas. https://blog.hubspot.es/website/lista-python

P. (2022, 3 agosto). Python Data Types (With Complete List). DigitalOcean Community. https://www.digitalocean.com/community/tutorials/python-data-types

Torres, A. (2021, 27 septiembre). Comprensión de Diccionario en Python: Explicado con ejemplos. freeCodeCamp.org. https://www.freecodecamp.org/espanol/news/compresion-de-diccionario-en-python-explicado-con-ejemplos/











Programas muestra para introdución a Python
[![Run on Repl.it](https://repl.it/badge/github/ingrid717-py/PythonIntro)](https://repl.it/github/ingrid717-py/PythonIntro)
