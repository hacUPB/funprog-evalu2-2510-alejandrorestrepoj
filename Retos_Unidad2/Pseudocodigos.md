# Pseudocodigo

### Problema 1

```
Inicio
Escribir "Insertar los valores de x1, x2, y1, y2"
Leer x1, x2, y1, y2
co = x2-x1
Imprimir co
ca = y2-y1
Imprimir ca
Leer co, ca
D = SQRT((co*co)+(ca*ca))
Imprimir D
Escribir "El valor de la distancia es: ", D
Fin
```

### Problema 2

```
Inicio
Escribir "Insertar med-met"
Leer med-met
med-pulgadas = med-met * 0.0254
Imprimir med-pulgadas
Escribir "La medida de la tela en metros a pulgadas es: " med-pulgadas
Fin
```

### Problema 3

```
Inicio
Escribir "Insertar los valores de A, B"
Leer A, B
H = SQRT((A*A)+(B*B))
Imprimir H
Escribir "El valor de la hipotenusa es: ", H
Fin
```

### Problema 4

```
Inicio
Escribir "Insertar la fecha actual en el siguiente orden: dia, mes, año"
Leer dia, mes, año.
Escribir "Insertar su fecha de nacimiento: adia, ames, aaño"
Leer adia, ames, aaño.
Si dia = diaa, mes = ames
    Escribir "¡Feliz cumpleaños!"
    Edad = aaño - año
    Fin si
Si (mes < ames) o (mes = ames y dia < adia)
    Edad = aaño - año - 1
    Fin si
Si
    Edad = aaño - año
    Fin si
Imprimir Edad
Escribir "Tu edad actual es: ", Edad
Fin
```

### Problema 5

```
Inicio
Escribir "Insertar horas_trabajadas"
Leer horas_trabajadas
Si horas_trabajadas > 50
    Escribir "No esta permitido trabajar mas de 50 horas."
    Fin si
Si horas_trabajadas > 46
    Escribir "Su pago sera el triple."
    Fin si
Si horas_trabajadas > 41

    Escribir "Su pago sera el doble."
    Fin si
Si
    Escribir "Su pago sera normal."
    Fin si
Fin.
```

### Problema 6

```
Inicio
Escribir "Insertar cuantos valores N piensa introducir."
Leer N
Escribir "Insertar C:"
N = N - 1
Repetir N veces.
Si N = 0
Leer valores.
cero = 0
may_cero = 0
men_cero = 0
    Si C = 0
        cero = cero + 1
        Leer cero
        Fin si
    Si C = may_cero 
        may_cero = may_cero + 1
        Fin si
    Si C = men_cero
        men_cero = men_cero + 1
        Fin si
Escribir "La cantidad de valores igual a cero son: ", cero
Escribir "La cantidad de valores menores a cero son: ", men_cero
Escribir "La cantidad de valores mayores a cero son: ", may_cero
Fin
```

### Problema 7

```
Inicio
Aho_Dia = 3
T_Dia = 0
Si Dia =<365
    Aho_Dia = 3^Dia 
    T_Dia = T_Dia + Aho_Dia
    Imprimir Dia
    Dia = Dia + 1
Fin si
Imprimir: "El total ahorrado al final del año es: ", T_Dia    
Fin
```

### Problema 8

```
Inicio
Escribir "Insertar precio_total"
Leer precio_total
Si precio_total >= 200
    D = precio_total * 0.15
    Imprimir D
    precio_total = precio_total - D
    Imprimir precio_total
    Fin si
Si precio_total > 100
    D = precio_total * 0.12
    Imprimir D
    precio_total = precio_total - D
    Imprimir precio_total
    Fin si
Si precio_total > 0
    D = precio_total * 0.1
    Imprimir D
    precio_total = precio_total - D
    Imprimir precio_total
    Fin si
Escribir "El descuento es: ", D
Escribir "El precio final con el descuento es: ", precio_total
Fin
```

### Problema 9

```
Inicio
Escribir "Insertar el valor de X que queremos calcular."
Leer X
Escribir "Insertar el valor de N repeticiones"
Leer N
sin_x = 0
Si N > 0
    Termino = ((-1)^N * x^(2*N + 1)) / Factorial(2*N + 1)
    sin_x = sin_x + Termino
    Imprimir Termino
    N - 1
Fin si 
Imprimir "La aproximacion de x con N: ", N, "terminos es: ", X 
Fin
```

### Problema 10

```
Inicio
Escribir "Insertar el valor de X que queremos calcular."
Leer X
Escribir "Insertar el valor de N repeticiones"
Leer N
e^x = 0
Si N > 0
    Termino = x^N / Factorial(N)
    e^x = e^x + Termino
    Imprimir Termino
    N - 1 
Fin si 
Imprimir "La aproximacion de x con N: ", N, "terminos es: ", X 
Fin
```