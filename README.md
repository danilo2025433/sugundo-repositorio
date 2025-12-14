# segundo-repositorio
APRENDIENDO A PROGRAMAR
En este blog voy a implementar un programa que dibuje las lineas que el usuario le indique
#Este programa  le pregunta al usuario cuantas casillas quiere avanzar y dibuja - las veces que el usuario le indique.

Reto1: simula el comportamiento de la tortuga usando solo print() e input().

Intenta recrear el movimiento de la tortuga únicamente con texto, usando funciones, print() y input() para pedir valores al usuario.
'''readme.md
casillas = int(input("¿Cuántas casillas quieres avanzar? "))

# Creamos una línea vacía con "_" para representar casillas
tablero = ["_"] * (casillas + 1)

# Recorremos cada casilla y dejamos un "-"
for i in range(casillas + 1):
    tablero[i] = "-"
  
# Mostramos el tablero completo en una sola línea
print("".join(tablero))
'''




#EJEMPLO EN PHYTON


<img width="1115" height="628" alt="Captura de pantalla 2025-12-13 191927" src="https://github.com/user-attachments/assets/eb69054b-2f47-43a6-80ad-d18a1ba2ea6d" />

Reto 2: Tortuga bajando

Crea el rastro de una tortuga moviéndose hacia abajo usando únicamente print() e input().

#Este programa pide al usuario cuantas posiciones quiere que baje  la barra y  dibuja un (|) las posiciones que el usuario le indique.

'''phyton
posicion = 0      # posición inicial
meta = 10         # número de casillas (puedes cambiarlo)

while posicion < meta:
    pasos = int(input("¿Cuántas posiciones quieres que baje la barra? "))
    posicion += pasos
    if posicion > meta:
        posicion = meta
    
    # Dibujar todas las casillas desde arriba hasta la posición actual
    for i in range(posicion):
        print("|")
        '''
    
    
        
        
        

    
    
















        


        

        
        


