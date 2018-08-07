# Camino-del-Tardígrado
Este programa simula un tablero lineal de la cantidad de casillas que quiera el usuario que se juega con un dado (que el usuario puede elegir) donde el jugador 1 tiene que decidir una estrategia que va a mantener por el resto del juego.

El juego consiste en tirar un dado y decidir si quedarse con el valor que salió y avanzar esa cantidad de casillas o volver a tirar y avanzar esa cantidad de casillas, despúes el otro jugador hace lo mismo. Gana el que llega primero al último casillero del tablero.

En este programa primero se le pide al usuario que elija el tamaño del tablero y que tipo de dado quiere utilizar (elige cuantos valores va a tener el dado).

Luego te permite ponerle nombre a los jugadores.

Después el usuario debe elegir con qué estrategia va a jugar el jugador 1.
La estrategia es un Integer que lo que interpreta el programa es que si al tirar el dado, el valor del dado es menor a la estrategia elegida, se vuelve a tirar el dado y el jugador avanza la cantidad sacada por ese lanzamiento. Si no, el jugador avanza el valor sacado por esa primera tirada.

Luego el programa juega 5000 partidas con la estrategia elegida por el jugador 1 y va iterando sobre la estrategia del jugador 2 hasta que juega con todas las estrategias posibles.

El programa devuelve, para cada estrategia utilizada, el porcentaje de victorias del jugador 1 y del jugador 2.
