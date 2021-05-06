# Snake-Game-Mod
Continuar con una aplicación que implica una inteligencia muy sencilla conocida por la mayoría pero que requiere una actualización para manejar una funcionalidad adicional.

JUEGO DE SNAKE
Se mejoro un codigo ya establecido de un juego llamado "Snake". Estas mejoras sugieren nuevas funciones para el juego en si, que en total sería unas 2 nuevas funciones:
- Mover la comida
- Cambiar de color la comida y el Snake cada vez que se coma la comida

Mover la Comida
Se escogió hacer un vector para los posibles movimientos de la comida. Con la función de randrange, se programó con el commando "move" una nueva instrucción para el vector food, haciendolo mover solo en una dirección a la vez. 
De igual forma se dio una validación para demostrar que la comida debe de estar dentro de los limites o que no atraviese al vector Snake mediante una serie de comandos ya preestablecidos en el programa principal. Esta validación resulta en el terminado del juego cuando una de estas dos cosas ocurra, junto a un mensaje que diga el motivo del Game Over.


Cambiar de color la comida y el Snake cada vez que se coma la comida
La serpiente/Snake y la comida cambiaran de color cada vez que la Snake se coma la comida. Esta misma como el snake puede ser de cualquier color exceptuando el rojo, que simboliza en este juego como el Game Over. Se utilizo los conceptos de listas y el comando random.choice para poder abarcar e implementar esta área, tanto para el Snake como la comida.
