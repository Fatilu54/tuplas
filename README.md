#Activiad 1
meses = ("Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio", "Agosto", "Septiembre", "Ocubre", "Noviembre", "Diciembre")
while True:
    num = int(input("Ingrasar un numero entre 1 y {}(0 para slir):"(len(meses))))
    if num == 0:
        break
    elif num >=1 and num <= len(meses):
        print(meses[num-1])
    else:
        print("El numero ingresado esta uera e rango. Por favor, intenta de nuevo.")

#Actividad 2
numeros = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
num = int(input("Ingresa un numero: "))
count = numeros.count(num)
print("El numero {} aparece {} veces."(num, count(num)))


#Actividad 3
numeros = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
mayor = max(numeros)
menor = min(numeros)
print("El numero con el mayor valor es:", mayor)
print("El numero con el menor valor es:", menor)


#Actividad 4
num = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
indice = int(input("Iungrese un indice (entre 0 y 9)"))
if indice < 0 or indice >= len(num):
else:
    valor= num(indice)
    print("el valor en el indice", indice, "es:", valor)
    
