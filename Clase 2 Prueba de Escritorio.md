# Prueba de escritorio
-----------------------
# Ejercicio 1

## Sumar 2 numeros

```txt
inicio
    leer a
    leer b

    Suma := a + b

    Escribe Suma
Fin
```

|iteración|a|b|suma|
|---------|----|----|----|
|1|7|2|9|
|2|15|14|29|
|3|8|6|14

# Ejercicio 2

##  Calcular el Factorial de un numero

```txt
inicio
    escribir "ingrese un numero"
    leer a
    factorial:= 1
    para i:= 1 hasta el a hacer
        factorial:= factorial * i
    fin para
    escribir "El factorial es:", factorial
fin
```

|iteración|a|Factorial|
|---------|----|----|
|0|5|1|
|1|5|1|
|2|5|2|
|3|5|6|
|4|5|24|
|5|5|120|

# Ejercicio 3

## contar los numeros positivos en una lista

```txt
  Inicio  
      escribe "ingrese la cantidad de numeros"
      leer n
      contador:=0
      para i := 0 hasta n - 1 hacer
        leer numero temp
        si numero > 0
           cintador:= contador + 1       
        fin si   
    fin para
    escribir "cantidad de numeros positivos" , contador
  fin
```

|iteracion|n|i|num temp|contador|
|---------|-|-|--------|--------|
|0|80|0|--|0|undefined|0|
|1|8|1|-5|0|
|2|8|2|0|0|
|3|8|3|-10|0|
|4|8|4|8|1|
|5|8|5|1|2|
|6|8|6|-100|2|
|7|8|7|3|3|
|8|8|8|4|4|

# Ejercicio 4

## Factorial de un numero recursivo

```txt
inicio
    función Factorial(n)
        Si n = 0 
fin
```
|llamada|n|Retorno|
|--|--|--|
|Factorial (4)|4|4 * Factorial(3)|
|Factorial (3)|3|3 * Factorial(2)|
|Factorial (2)|1|1 * Factorial(1)|
|Factorial (1)|1|1 * Factorial(0)|
|Factorial (0)|0|1|

Calculo Base:

```txt
Factorial(4) = 4 * 3 * 2 * 1 * 1 = 24
```
