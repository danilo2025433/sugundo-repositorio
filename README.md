# segundo-repositorio
APRENDIENDO A PROGRAMAR
En este blog voy a implementar un programa que dibuje las lineas que el usuario le indique
#Este programa  le pregunta al usuario cuantas casillas quiere avanzar y dibuja - las veces que el usuario le indique.
'''phyton
casillas = int(input("¿Cuántas casillas quieres avanzar? "))

# Creamos una línea vacía con "_" para representar casillas
tablero = ["_"] * (casillas + 1)

# Recorremos cada casilla y dejamos un "-"
for i in range(casillas + 1):
    tablero[i] = "-"
  
# Mostramos el tablero completo en una sola línea
print("".join(tablero))
'''
