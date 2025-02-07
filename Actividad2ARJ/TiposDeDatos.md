# Tipos de datos mas usados en Programacion.

## Java

### Enteros
Este grupo incluye byte, short, int y long. Estos tipos de datos nos permiten trabajar con números enteros ya sean positivos o negativos.

### Flotantes/Decimales
Este grupo incluye float y double. Estos tipos de datos nos permiten trabajar con números los cuales posean punto decimal ya sean positivos o negativos.

### Caracteres
En el grupo de caracteres únicamente encontraremos el tipo de dato char. Este tipo de datos nos permitirá trabajar con caracteres.

### Boleanos
Al igual que el grupo de caracteres, en el grupo de booleanos únicamente encontraremos un tipo de dato, el boolean. Este tipo de datos nos permitirá trabajar con valores lógicos, verdadero o falso.

### Texto
En este tipo de datos además de texto también pueden incluirse números pero no pueden hacerse operaciones como suma, resta u otras para lo cual se necesitaría int o float porque el lenguaje los interpreta como texto, para declarar una variable con este tipo se emplea la palabra char que significa character y se traduce como carácter, pero en este tipo de datos además tenemos que indicar la cantidad de caracteres máxima que se incluirán + 1 así es como "Estetexto" contiene 9 caracteres y reservamos un total de 10 como mínimo, se reserva entre paréntesis cuadrado

[Fuente - Web](https://codigofacilito.com/articulos/tipos_datos_java)

## C

### Matrices / Array
Los array son un tipo dato complejo, en el sentido de que nos permiten guardar conjuntos de datos, pero siempre datos del mismo tipo.

### Estructuras
Las estructuras nos permiten guardar un conjunto de datos, pero esos datos pueden ser de distinto tipo.

### Entero
Recordemos que un número entero simplemente es cualquier número(natural) sin punto por ejemplo 0 es de tipo entero, 846582 también lo es pero 1.2 no porque tiene un punto y por eso no podríamos almacenar este valor en una variable de tipo entero, para declarar una variable de tipo entero utilizamos la palabra reservada int que significa integer en inglés y como ya era de suponer se traduce como entero al español, posteriormente añadimos el nombre de la variable

### Punto flotante
Este tipo de datos es la solución para números que tienen decimales como es el caso de 98.3, al contrario de "Enteros" donde no podemos incluirlo en variables de tipo entero, para declararlos se utiliza la palabra reservada float.

### Booleano
Una variable de tipo booleano solo acepta dos tipos de valores estos son true que significa verdadero o false que significa falso, se utiliza si se quiere guardar el estado de un resultado por ejemplo si preguntamos 1=5 el resultado será false porque uno no es igual a cinco y podemos almacenarlo en una variable de tipo booleano, para declarar una variable booleana utilizamos la palabra reservada bool.

[Fuente - Web](https://www.codigazo.com/en-c/tipos-datos-variables-c-ejemplos)

## Python

### Números
En Python, existe un tipo de datos Número para todas las operaciones que involucran valores numéricos. Este tipo de datos puede manejar todo tipo de valores numéricos: números enteros, números de coma flotante y números complejos.

### Cadenas
Una cadena de Python no es más que una secuencia de caracteres y, por lo tanto, también se denomina cadena de caracteres.

Las cadenas en Python son inmutables; la misma instancia de String no se puede modificar. En su lugar, para actualizar el valor de la cadena, se debe proporcionar una nueva instancia actualizada.

### Booleanos
Los valores booleanos en Python incluyen dos valores posibles: True yFalse

Estos valores generalmente se usan en declaraciones condicionales. Estos dos valores se pueden usar como operandos para operaciones lógicas como and , or , not , etc.

### Conjuntos

Los conjuntos son colecciones desordenadas de valores de datos únicos. Los valores de datos pueden ser de cualquier tipo de datos siempre que sean hashables e inmutables.

Los conjuntos se pueden inicializar con valores de datos separados por una coma y encerrados entre llaves {}.

Los conjuntos ignoran todos los valores repetidos y solo almacenan elementos únicos. Los conjuntos son mutables, lo que permite actualizar los valores de los datos.

[Fuente - International Business School](https://eiposgrados.com/blog-python/tipos-de-datos-de-python/)

## Rust 

### Enteros
Rust admite enteros con y sin signo en varios tamaños. Estos son los tipos enteros comunes

### Números de coma flotante
Rust proporciona dos tipos de números de coma flotante:

f32 (32 bits) - f64 (64 bits)

### Booleanos
Los tipos booleanos en Rust están representados por el tipo, que puede ser o true o false.

### Caracteres
El tipo de Rust representa un único valor escalar Unicode. Tiene un tamaño de 4 bytes y puede representar una amplia gama de caracteres.char

### Tuplas
Las tuplas pueden contener varios valores de diferentes tipos. Tienen una longitud fija.

### Matrices
Las matrices en Rust pueden contener varios valores del mismo tipo. Tienen una longitud fija.

### Estructuras
Las estructuras de Rust se utilizan para crear tipos de datos personalizados. Le permiten nombrar y empaquetar varios valores relacionados. Definir una estructura mediante la palabra clave y especifique sus campos.

### Enumeraciones
Las enumeraciones, abreviatura de enumeraciones, permiten definir un tipo enumerando sus posibles variantes. Las enumeraciones son útiles para modelar datos que pueden ser de varios tipos diferentes.

[Fuente - Blog](https://medium.com/@apicraft/basic-data-types-and-structures-in-rust-bda9779ea9d1)