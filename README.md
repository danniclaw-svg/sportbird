# SportBird

Aplicación web para que un jugador joven lleve la estadística de su carrera deportiva. Está en español y funciona en una sola página, sin instalar nada.

## Ajedrez
- Registro de partidas: rival, color, resultado, torneo, ELO propio y del rival, y notas.
- Carga de partidas en formato PGN (una o varias, pegadas o desde un archivo `.pgn`).
- Tablero para recrear cada partida jugada a jugada, con reproducción automática, jaque resaltado y rotación.
- Estadísticas por rival y por apertura, récords personales, gráfica de ELO y resultados por mes.
- Logros.

## Fútbol
- Registro de partidos: rival, marcador, minutos, goles, asistencias, tarjetas, posición, calificación y notas.
- Estadísticas por rival, récords, goles acumulados, goles y asistencias por mes.
- Logros.

## Cómo usarla
Abre `index.html` en el navegador, o publica el repositorio con GitHub Pages.
Los datos se guardan en el propio navegador (localStorage). Desde la pestaña Partidas hay una copia de seguridad en texto para pasar los datos a otro dispositivo.

## Tecnología
HTML, CSS y JavaScript sin dependencias propias. Usa [chess.js](https://github.com/jhlywa/chess.js) (BSD-2) para leer PGN y validar jugadas, cargada desde cdnjs.
