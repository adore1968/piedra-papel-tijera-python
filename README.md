# Piedra, Papel o Tijera en Python

Este proyecto es una implementación del clásico juego "Piedra, Papel o Tijera" en Python, donde el jugador escoge una opción (piedra, papel o tijera) y la computadora selecciona aleatoriamente una de las tres opciones. El juego determina el resultado según las reglas estándar: piedra gana a tijera, tijera gana a papel, y papel gana a piedra.

## Conceptos Utilizados

- **Funciones**: El juego está estructurado en dos funciones principales:
  - `jugar()`: Controla el flujo del juego, obtiene la opción del jugador, genera la predicción de la computadora y determina el resultado.
  - `gano_el_jugador()`: Verifica si el jugador ha ganado según las reglas del juego.
  
- **Generación de Números Aleatorios**: La computadora utiliza `random.choice()` para seleccionar aleatoriamente entre "pi" (piedra), "pa" (papel) o "ti" (tijera).
- **Condicionales**: Se emplean estructuras `if` y `else` para determinar el ganador en función de las elecciones del jugador y la computadora.
- **Entrada del Usuario**: Se usa `input()` para permitir que el jugador ingrese su opción de manera interactiva.
