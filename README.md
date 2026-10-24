# Liga del Sur · All Stars ⚽

Simulador de carrera de fútbol ambientado en Bahía Blanca. De las inferiores de un club de barrio a la vitrina de la Liga del Sur.

Juego de una sola página (HTML + CSS + JS, sin dependencias). El progreso se guarda en el `localStorage` del navegador.

## Estructura

```
index.html            # el juego completo
assets/escudos/       # escudos de los clubes (PNG con fondo transparente)
```

Los clubes del Torneo Promocional todavía no tienen escudo y muestran sus iniciales. Para agregarlo, subí `assets/escudos/<id>.png` (ids: `ddh`, `dlg`, `ugc`, `pgs`, `aec`) y sumá el id a la lista `CON_ESCUDO` en `index.html`.

## Dificultad

Ganar títulos es difícil: el jugador solo no carga al equipo. Lo que más pesa es el **clima del equipo** (barra en tu ficha), que sube o baja con tus decisiones, tu moral y tu relación con el técnico y la hinchada. Una mala decisión en un momento clave cuesta mucho más de lo que suma una buena, y una temporada mal manejada se arrastra a la siguiente. Si tu club es el más fuerte de su liga, todos juegan a muerte contra vos ("Candidato"), y cada título aumenta la presión para el siguiente.

Si llevás 4 o más temporadas en un club y venís bien con el técnico y la hinchada, puede estallar una **crisis en el club**: tres eventos seguidos (pelea de vestuario, choque entre el técnico y la dirigencia, ruptura total). En la mitad de los casos terminás obligado a salir en el mercado de pases.

Las **lesiones** pueden bajarte 10 puntos en todos los atributos, y son mucho más probables si venís de dos temporadas seguidas con promedio alto. Los **malos gestos** (rojas y escándalos) te suspenden y te hacen perder partidos y goles.

## Publicarlo con GitHub Pages

1. Creá un repositorio nuevo en GitHub y subí todo el contenido de esta carpeta.
2. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En un minuto queda online en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Probarlo en local

Abrí `index.html` en el navegador. Si querés un servidor local: `python3 -m http.server` y entrá a `http://localhost:8000`.

## Créditos

Creado por Julián Gutiérrez. Todos los derechos reservados © 2026.
