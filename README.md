Co-authored-by: Aldo Maldonado Hernadez 165459


Co-authored-by: AUTHOR-NAME <ANOTHER-NAME@EXAMPLE.COM>"



### Introduction

- En este tutorial vamos a aprender como usar  jupyter.


# Python.md




**Table of Contents**

[ TOCM ]

[TOC]

# Instalar Anaconda
Lo primero que tienes que hacer es descargar Anaconda para poder trabajar con Júpiter, los enlaces aquí:
https://www.anaconda.com/

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

## Bibliografía
Londoño, P. (2023, 13 febrero). Listas en Python: qué son, cómo crearlas y ordenarlas. https://blog.hubspot.es/website/lista-python

P. (2022, 3 agosto). Python Data Types (With Complete List). DigitalOcean Community. https://www.digitalocean.com/community/tutorials/python-data-types

Torres, A. (2021, 27 septiembre). Comprensión de Diccionario en Python: Explicado con ejemplos. freeCodeCamp.org. https://www.freecodecamp.org/espanol/news/compresion-de-diccionario-en-python-explicado-con-ejemplos/
## How to create subroutines and execute them.
## Error management and configuration issues.














Programas muestra para introdución a Python
[![Run on Repl.it](https://repl.it/badge/github/ingrid717-py/PythonIntro)](https://repl.it/github/ingrid717-py/PythonIntro)
