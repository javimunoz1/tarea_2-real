# tarea_2-real

for x in range(100):
  print(x+1)


for x in range(100):
  if(x+1) % 3 == 0:
    print(x+1)


numero_1 = int(input("ingresa un numero"))
numero_2 = 5
suma = numero_1 + numero_2
resultado = ""

if(suma<100):
  resultado = "menor a 100"
elif(suma>=100 and suma<150):
  resultado = "mayor a 100"
elif(suma>=150):
  resultado = "mayor a 150"

print(resultado)