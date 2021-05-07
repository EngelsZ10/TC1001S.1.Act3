# TC1001S.1.Act3
Actividad 3. Juego de Pacman: modificamos el script pacman.py del paquete freegames de python para:
- Los fantasmas siguen a pacman si estan en el mismo eje y no hay paredes entre ellos
- Cambiar el tablero
- Hacer que los fantasmas vayan mas rápido

Integrantes:
- Engels Emiliano Miranda Palacios A01423398
- Ronaldo Jesús Ruíz Álvarez A01424337

Log Emiliano:

lineas 127 a 136 comprueban para cada fantasma si estan en el mismo eje (x o y) que pacman estan en el mismo eje que pacman y cambian la dirección dependiendo de si pacman esta arriba, abajo, a la izquierda o la derecha. 


Log Ronaldo:

De la línea 28 a la 49 me di cuenta que las tiles se modificaban cambiando 1 y 0, donde el 0 representaba un obstáculo y el 1 un lugar por donde podía pasar Pac-Man, lo que hice aquí fue modificar estos números para cambiar el mapa.

En la línea 138 donde se establece el movimiento de los fantasmas con la variable "course", lo que hice fue mutiplicarla por tres para que así se incrementara la velocidad de los fantasmas.
