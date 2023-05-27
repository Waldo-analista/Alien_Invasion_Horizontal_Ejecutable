Este repositorio contiene el proyecto <b>Alien Invasion</b> en su <b>versión horizontal</b> ejecutable listo para jugar y utilizar. 

En el nivel 1 cada alien borrado equivale a 50 puntos y en cada nuevo nivel cada alien borrado crece en un factor 1.5. A medida que se avanza en el juego se incrementa l velocidad de los aliens, la velocidad de la nave y la velocidad de los bullet en el factor de 1.1. La velocidad de movimiento hacia la izquierda es siempre constante igual a 4 pixeles.

En el juego se permite disparar 3 bullets a la vez (solo mantener 3 bullets en pantalla)

Además le he agregado las siguientes características adicionales del juego original:

-Nuevo posicionamiento de elementos de información y cambio de colores (scoreboard)

-Nuevo elemento del scoreboard que informa naves en reserva (3 en total)

-Dos nuevos elementos que informan del High Score y del High Level. Cuando el jugador utiliza el juego por primera vez y pierde sus 3 naves en reserva y se finaliza el juego, se crea un archivo .txt que guarda el puntaje máximo y el nivel máximo logrado. Para cuando el jugador abra nuevamente el juego, el juego lee de ese archivo los puntajes máximos y los muestra en los respectivos indicadores. Si el archivo no existe en el directorio el juego reinicia los puntajes máximos a 0 para high score y level 1 para high level.
Se agrega archivo 'high score and high level.txt' en el cual se guarda el high score de 1791156066761547 y el high level de 66

-Música de fondo y sonido de disparo de "misiles"

<b>La imagen del juego cuando se inicia es</b>:

![alt text](/VistaInicialAlienInvasion.png?raw=true "Imagen de Inicio del Juego")