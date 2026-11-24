# ¡Muévete! · Juego de fiesta con movimientos

Juego para 1 o 2 jugadores. La cámara del móvil detecta el cuerpo (MediaPipe Pose) y el juego se ve en la TV.

## Minijuegos
- 🫧 **Burbujas**: revienta burbujas con las manos (⭐ +30, 💣 −15).
- 🦘 **Salta y agáchate**: salta los troncos y agáchate bajo los rayos.
- 💃 **Baile**: copia la postura del muñeco al ritmo de la música.
- 🎉 **Fiesta**: los tres seguidos, con marcador total.

## Cómo publicarlo (GitHub Pages, gratis)
1. Crea un repositorio nuevo (por ejemplo, `muevete`) y sube `index.html`.
2. Ve a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
3. En un minuto tendrás la dirección `https://TU_USUARIO.github.io/muevete/`.
   La página necesita **https** para poder usar la cámara.

## Cómo jugar
**Opción A, duplicar pantalla:** abre la página en el móvil, pulsa «Jugar en este dispositivo» y duplica la pantalla en la TV (Smart View, Chromecast…).

**Opción B, navegador de la Smart TV:**
1. En la TV, abre la página y pulsa «Esta es la pantalla de la TV». Aparecerán un código y un QR.
2. En el móvil, escanea el QR (o abre la página, pulsa «Usar este móvil como cámara» y escribe el código).
3. Apoya el móvil en horizontal, a la altura de la cintura y a 2–3 m. Se os tiene que ver de cuerpo entero.

Para elegir en los menús, deja la mano sobre un botón durante un segundo.
El jugador 1 se pone a la izquierda y el jugador 2 a la derecha.

## Requisitos
- El móvil y la TV con conexión a Internet. La conexión entre ellos se hace con WebRTC (PeerJS).
- Navegador moderno (Chrome en Android). Algunas Smart TV antiguas no admiten WebRTC; en ese caso, usa la opción A.
