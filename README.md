# numeros
tarea de los numeros
import random
numero = input ("escriba un numero: ")
Numero = int(numero)
Y = random.randint(1,100)
intento = (0)
while(Numero != Y):
    if (Numero < Y):
        print("mas grande")
        intento += 1
        numero = input ("escriba un numero: ")
        Numero = int(numero)
    else:
        print("mas pequeño")
        intento += 1
        numero = input("escriba un numero: ")
        Numero = int(numero)
print("Acertaste el numero en " , intento ," intentos")
