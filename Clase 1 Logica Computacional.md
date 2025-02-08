# Clase de logica computacional
Esta primera clase tambien cuenta para introduccion a la ingenieria de datos e IA

```python
# esto es un comentario
print("hola mundo");
```

# Ejercicio 1

```python
a = int(input("ingrese numero 1 "));
b = int(input("ingrese numero 2 "));
c = int(input("ingrese numero 3 "));

# : = then in python

if (a > b) and (a > c):
 print("El numero mayor es", a);
elif (b > c):
 print("El numero mayor es", b);
else:
  print("El numero mayor es", c);
```

# Tipos de datos

```python
num = 0
string = "hola"
decimal = 21.12
array = [1, 2, 3]
tupla = {1, 2, 3}
diccionary = {"key": "value"}
boolean = True

data = [num, string, decimal, array, tupla, diccionary, boolean]

for i in data:
  print(type(i))
```

# Ejercicio 2

```python
suma = 0

for i in range(0, int(input("Inserte la cantidad de numeros "))):
  suma += int(input( "ingrese el valor del num " + str(i) +  ": "))

  print("el valor es " + str(suma))
```

# Ejercicio 3

```python
x = 0
for i in range( 0, 51):
  x -= i

  print(i, x)
```

# Ejercicio 4

```python
x = 0
for i in range( 50, -1, -2):
    x -= i

    print( i, x)
```

# Ejercicio 5

```python
for i in range(68+1, 120+1, 2):
  print(i)
```
