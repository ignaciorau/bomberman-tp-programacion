# Bomberman
<p align="center">
  <img src="https://imgs.search.brave.com/8CztCbixblm11bxsBVGInxRagrTWupbH3ugbyY2u3xs/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWFn/ZS5hcGkucGxheXN0/YXRpb24uY29tL3Z1/bGNhbi9hcC9ybmQv/MjAyMzAzLzIyMTQv/ZDViNjE0MDg3ZGMz/YWFkOGI1MzlhZjhl/Y2UzNTdhYWEzMzVk/NjE5MTlkN2MwNzM1/LnBuZw" alt="Bomberman">
</p>

Bomberman es un juego que trata de colocar bombas para abrir caminos de manera estratégica, enfrentar enemigos y asegurar territorios.

## Historia

El planeta Tierra enfrenta una crisis energética y los humanos han descubierto un mundo subterráneo lleno de túneles y cavernas que parecen infinitos. Bomberman es enviado como pionero para explorar, conquistar y asegurar estos territorios. Sin embargo, no está solo: distintas razas y criaturas habitan las profundidades y harán todo lo posible por impedir su avance.

Tu misión es colocar bombas estratégicamente para abrir caminos, derrotar enemigos y construir bases seguras en las cavernas. Podrás decidir si cooperar con algunas razas, esclavizarlas para tu beneficio o eliminarlas por completo.

## Enemigos

- **Bomtars**: Seres sumamente resistentes a las bombas pero con una velocidad muy lenta.
- **Spectros**: Enemigos tipo fantasma con la habilidad de atravesar los muros.
- **Golems**: Enormes enemigos que se quedan inmóviles y bloquean el paso. Requieren varias bombas para derrotarlos.

## Mecánica de juego

- **Movimiento**: Teclas direccionales del teclado.
- **Colocación de bombas**: Barra espaciadora.
- **PowerUps**: Mejoras al jugador que cambian su jugabilidad o el comportamiento de las bombas (ExtraBomba, MayorAlcance, VidaExtra, etc.).
- **Recolección**: Automática al pasar sobre un PowerUp.


## Archivos de datos (formato binario)

Solo se persisten los datos que necesitan sobrevivir entre sesiones de juego:

- `Jugadores.dat` — Datos del jugador (id, nombre, vidas, posición, bombas disponibles, estado).
- `Tablero.dat` — Configuración del tablero (id, ancho, alto).
- `PowerUps.dat` — PowerUps disponibles en el mapa (id, tipo, posición, activo).
- `Ranking.dat` — Puntajes altos (id, nombre, puntos).
- `Enemigos.dat` — Enemigos (id, tipo, vidas, posición, velocidad, atraviesa paredes, inmóvil, eliminado).

## Tecnologías utilizadas

- Lenguaje: C++
- Almacenamiento: Archivos binarios (.dat)
