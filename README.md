# practica
print("¿Quieres viajar al amazonas?")
inputUser = input()
if inputUser == "si":
    print("El viaje quedó programado")
elif inputUser == "no":
    print("el viaje quedó cancelado")
print("¿prefieres viajar a otro lugar?")
inputUser = input()
if inputUser == "si":
    print("te daré diferentes opciones")
elif inputUser == "no":
    print("No hay mas opciones")

lista_de_lugares = ["guajira", "cartagena", "termales de santa rosa"]
for listado in lista_de_lugares:
    print(listado+"\n")
print("¿cual eliges?")
inputUser = input()
if inputUser == "guajira":
    print("Viaje programado a la guajira")
if inputUser == "cartagena":
    print("Viaje programado para cartagena")
elif inputUser == "termales de santa rosa":
    print("Viaje programada para los termales de santa rosa")
