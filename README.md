# grillandsmoke — sitio de Grill and Smoke Studio

Sitio estático (GitHub Pages) que piden TikTok, Google (YouTube) y Meta para la app de publicación:

- `index.html` — qué es la herramienta
- `terms.html` — términos de servicio
- `privacy.html` — privacidad: datos que se usan, que no se comparten ni venden, cómo pedir borrado
- `callback.html` — recibe el `code` de OAuth y lo muestra para pegarlo en el servidor (no lo manda a ningún lado)
- `publicar.html` — pantalla de publicación según las guías UX de Content Posting API, en Sandbox (para el video demo)

Sin secretos: los tokens y el client secret viven solo en el `.env` del servidor.
