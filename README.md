# Bomberman
![Bomberman](link-a-imagen-ilustrativa)
Bomberman es un juego inspirado en el clásico de estrategia y acción. El jugador explora un mundo subterráneo lleno de túneles y cavernas, colocando bombas estratégicamente para abrir caminos, derrotar enemigos y construir bases seguras.
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
## Diagrama de Clases
> *(Pendiente: insertar imagen del diagrama de clases)*
## Archivos de datos (formato binario)
- `Jugadores.dat` — Datos del jugador (id, nombre, vidas, posición, bombas disponibles, estado).
- `Tablero.dat` — Configuración del tablero (id, ancho, alto).
- `Bombas.dat` — Estado de bombas (id, posición, potencia, tiempo restante, activa).
- `Explosiones.dat` — Registro de explosiones (id, bomba origen, posición, radio, finalizada).
- `PowerUps.dat` — PowerUps disponibles (id, tipo, posición, activo).
- `Ranking.dat` — Puntajes altos (id, nombre, puntos).
- `Enemigos.dat` — Enemigos (id, tipo, vidas, posición, velocidad, atraviesa paredes, inmóvil, eliminado).
## Tecnologías utilizadas
- Lenguaje: C++
- Almacenamiento: Archivos binarios (.dat)
