# Programa-para-determinar-si-un-a-o-es-bisiesto-o-no
El siguiente programa sirve para determinar si un año es o fue bisiesto o no

Año=int(input("Introduzca el año:"))
print(type(Año))

i=1

if type(Año/4)=int:
	i==i+1

if type(Año/100)=int:	
	i=i+1

if type(Año/400)=int:
    i=i+1	

if i==1 or i==3:
	print("El año es bisiesto")

