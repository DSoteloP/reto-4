# Reto-4
### David Sotelo Ing Mecatronica

1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula
```python
x : int 
x = int(input("introduzca un número entero: "))
if x == 97 or x == 101 or x == 105 or x == 111 or x == 117:
    m = chr(x)
    print(x, " pertenece a la vocal minúscula ",m)
else:
    print(x+" no pertenece a una vocal minúscula en ascii")
```

2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no
```python
x = input("ingrese un caractér: ")
if ord(x)%2 == 0:
    print("en ascii, el primer digito de la cadena de caracteres "+x+" es par")
else:
    print("en ascii, el primer digito de la cadena de caracteres "+x+" no es par")
```

3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no
```python
x = input("ingrese un caractér: ")
if ord(x) >= 48 and ord(x) <= 57:
    print(x+" es un numero")
elif ord(x) >= 97 and ord(x) <= 122 or ord(x) >=65 and ord(x) <= 90:
    print(x+" es una letra")
else:
    print(x+" es un simbolo")
```

4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
```python
x : float = float(input("Ingrese un numero"))
if x > 0:
  print("El número ", x, " es positivo")
elif x < 0:
  print("El número ", x, " es negativo")
else:
  print("El número", x, " es el neutro para la suma")
```

5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo
```python

``` 
6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo
```python
l1 : float = float(input("ingrese longitud del lado 1: "))
l2 : float = float(input("ingrese longitud del lado 2: "))
l3 : float = float(input("ingrese longitud del lado 3: "))
if l1 > 0 and l2 > 0 and l3 > 0 and l1 + l2 > l3 or l1 + l3 > l2 or l2 + l3 > l1:
  print("si se puede construir un triangulo con las lungitudes dadas")
else:
  print("no se puede construir un triangulo con las lungitudes dadas")
```
