# RETO08
## Funciones - segunda parte
Se realizaron diferentes tipos de funciones según lo que requería el ejercicio.
## 1. De los retos anteriores selecione 3 funciones y escribalas en forma de lambdas.
El reto que escogí para este punto fué:  **"diseñe una función que calcule la cantidad de carne de aves en kilos si se tienen N gallinas, M gallos y K pollitos cada uno pesando 6 kilos, 7 kilos y 1 kilo respectivamente"**  
  
La función anterior es la siguiente
  ```
def calcular_cantisas_carne(n_gallinas, m_gallos, k_pollitos):
    peso_gallinas = 6
    peso_gallos = 7
    peso_pollitos = 1

    kilos_carne = (n_gallinas * peso_gallinas) + (m_gallos * peso_gallos) + (k_pollitos * peso_pollitos)
    return kilos_carne

#ingreso de datos por teclado
n = int(input("Ingrese el numero de gallinas: "))
m = int(input("Ingrese el numero de gallos: "))
k = int(input("Ingrese el numero de pollitos: "))

total_carne = calcular_cantisas_carne(n, m, k)

#resultado
print("La cantidad de carne de aves en kilos es:", total_carne)
```
calcular_cantidad_carne = lambda n, m ,k: (n * 6) + (m + 7) + (k + 1)
n = int(input("Ingrese el numero de gallinas: "))
m = int(input("Ingrese el numero de gallos: "))
k = int(input("Ingrese el numero de pollitos: "))
total_carne = calcular_cantidad_carne (n, m, k)
print("La cantidad de carne de aves en kilos es:", total_carne)
