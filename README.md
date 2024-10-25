# Manejo_archivos_1217_sosa_luis_omar_3-W
Manejo de archivos
# PROGRAMA 1:
print() #para una linea en blanco
print("Sosa Luis Omar 1217: MI PRACTICA DE MANEJO DE ARCHIVOS") #el nombre del creador
print() #para una linea en blanco
archivo = open("practica 1_sosa_luis_omar_1217_3-W.txt", "r") #lo que se mostrara en pantalla
print(archivo.readable()) #menciona o llama al arvchivo
contenido = archivo.read() #menciona que el contenido mostrado sera degun el archivo ingresado
print(contenido) #imprime el contenido
archivo.close() #el archivo finaliza
print() #para una linea en blanco

![image](https://github.com/user-attachments/assets/fca50c49-e56e-47b3-831e-a664a172679d)
![image](https://github.com/user-attachments/assets/86fbcbaa-4c7b-4e3f-9a55-5c40a0ebf07e)

# PROGRAMA 2:
print() #para una linea en blanco
print("SOSA LUIS OMAR 1217: MI PRACTICA DE MANEJO DE ARCHIVOS") #nombre del credor
print() #para una linea en blanco
with open("Practica 2.txt", "r") as f:  #imprime la practica 2
    contenido = f.read() 
    print(contenido) #imprimira el contenido ingresado previamente
print() #para una linea en blanco

![image](https://github.com/user-attachments/assets/3c76c37d-a8d2-4fb5-bcbc-a1280ce323ca)
![image](https://github.com/user-attachments/assets/b7a637bb-b356-4ea2-9207-c16051a45ddf)

# PROGRAMA 3:
print() #para una linea en blaco al ejecutar
print("SOSA LUIS OMAR 1217 3-W: MI PRACTICA DE ARCHIVOS") #el nombre del creador
print() #para una linea en blaco al ejecutar
archivo = open("Practica 3_sosa.txt", "r") #la practica que mostrara en pantalla
print(archivo.read(5)) #indica que solo 5 digitos de la primera palabra
archivo.close() #termina le archivo al colocar los 5 digitos
print() #para una linea en blaco al ejecutar

![image](https://github.com/user-attachments/assets/f363bac9-3aa4-4d1c-8114-23a0084ca14c)
![image](https://github.com/user-attachments/assets/e4fa7c59-dbe9-4f09-8c31-5d4b9565b1b3)

# PROGRAMA 4:
print() #dejar una linea en blanco
print("SOSA LUIS OMAR 1217 3-W: MI PRACTICA DE ARCHIVOS") #nombre del creador
print() #dejar una linea en blanco
archivo = open("Practica 4_sosa.txt", "a") #la practica que se mostrara
archivo.write("Now the file has more content!\n") #lo que mostrara en la ejecucion
archivo.close() #cerrar al terminar la ejecucion
print() #dejar una linea en blanco

![image](https://github.com/user-attachments/assets/e4e13b8f-3b9e-402c-9cc9-74a8647d2be7)
![image](https://github.com/user-attachments/assets/5ef01e45-a1d3-448f-abb9-21026ee667c7)

# PROGRAMA 5:
print() #para deja un espacio 
print("SOSA LUIS OMAR 1217_3-W: MI PRACTICA DE ARCHIVOS") #nombre del creador
print() #para deja un espacio 
archivo = open("Practica numero 5.txt", "w") #la practica que se mostrara
archivo.write("Woops! I have deleted the content!\n") #lo que mostrara en la lista de archivos
archivo.close() #cerrar al mostrar lo indicado
print() #para deja un espacio 

![image](https://github.com/user-attachments/assets/99366c6a-eada-4add-a47f-23910475d36b)
![image](https://github.com/user-attachments/assets/7579621b-2fa4-4978-9fb8-6a00e6e11f16)

# PROGRAMA 6:
print() #para une linea en blanco
print("SOSA LUIS OMAR 1217 3-W: MI PRACTICA DE ARCHIVOS") #nomnbre del creador
print() #para une linea en blanco
archivo = open("Practica 6_bandas.txt", "w") #la practica que en este caso se borrara
archivo.write("Este archivo será eliminado.\n") #indica que la practica de borrara
archivo.close() #cierra cuando el objetivo se cumpla
print() #para une linea en blanco

![image](https://github.com/user-attachments/assets/cbe1d6a4-6b0e-452d-bb92-0b4aa7ac05fa)
![image](https://github.com/user-attachments/assets/29c9e238-e8a9-4f51-b220-aada6fbdc7b1)

# PROGRAMA 7:
print() #Para una linea en blanco
print("SOSA LUIS OMAR 1217_3-W: MI PRACTICA DE ARCHIVOS") #nombre del crador
print() #Para una linea en blanco
print("(\"Practica 7_sosita.txt\")'.") #la paractica que se mostrara
print() #Para una linea en blanco

![image](https://github.com/user-attachments/assets/be9e6e03-a65e-473f-929e-5f70065ceeea)
![image](https://github.com/user-attachments/assets/96b6856a-fe81-4bbc-8efc-99de5c46e5fa)

# PROGRAMA 8:
print()
print("SOSA LUIS OMAR 1217_3-W: MI PRACTICA DE ARCHIVOS")
print()
archivo=open("Practica 8_omar.txt", "r")
print(archivo.read())
archivo.close()
print()

![image](https://github.com/user-attachments/assets/679fbfe0-0053-40c7-995a-679ea72b8779)
![image](https://github.com/user-attachments/assets/efea07fd-cfa3-450e-ae8e-873fcdb3d776)

# PROGRAMA 9:
print()
print("SOSA LUIS OMAR 1217_3-W: MI PRACTICA DE ARCHIVOS")
print()
archivo = open("Practica 9_omarcin.txt", "w") 
archivo.write("Este archivo será eliminado.\n")
archivo.close()
print("Para eliminar el archivo, usa 'os.remove(\"Practica 9_omarcin.txt\")'.")
print()

![image](https://github.com/user-attachments/assets/125e9939-fde3-407e-b57b-2da9bcbcc147)
![image](https://github.com/user-attachments/assets/957aec70-6c83-4121-914f-dfe085689198)
