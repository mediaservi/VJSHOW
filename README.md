# VJSHOW — despliegue en Netlify
1. Arrastra esta carpeta completa a https://app.netlify.com/drop (o súbela a Git y conecta el repo).
2. Imágenes (PNG con transparencia para `gente/` y `objetos/`):
   - `fondos/fondo1.jpg … fondo60`, `gente/gente1.png … gente60`, `objetos/objeto1.png … objeto60` (jpg, jpeg, png, webp, gif, avif).
   - Alternativa: rellena `media-manifest.json` con rutas, p. ej. {"gente":["gente/ana.png"]}.
   - Nombres con "pajaro/bird" o "pelota/ball" tienen movimiento propio.
3. Audio: micrófono (HTTPS), archivo MP3/WAV, audio de pestaña (Chrome/Edge de escritorio) o `?audio=/audio/set.mp3`.
4. Parámetros URL: `?preset=vinyl&bpm=128&autostart=true`.
5. Usa solo imágenes y audio de los que tengas derechos si publicas el sitio.

## Almacenamiento y Loops
- Lo que el público añade con "Mis archivos" se guarda en su navegador (IndexedDB). Nunca se sube a Netlify.
- Las listas de Loops de YouTube también se guardan en cada navegador. Las listas del campo "loops" de `media-manifest.json` aparecen en todos con ★ (solo las gestionas tú). Sustituye el vídeo de ejemplo o borra ese bloque.
- La cabecera CSP de `_headers` ya permite YouTube (youtube-nocookie). No quites `frame-src` ni `script-src` de YouTube o los loops no cargarán.
- YouTube puede mostrar anuncios en vídeos monetizados de terceros y no se pueden ocultar. Usa vídeos propios o sin monetizar.
- La lista por defecto del sitio es la playlist `[MS] VJ LOOPS` (PLKMpvvSZDRY8), definida en el código (`DEFAULT_LOOP_LIST`). Aparece con ★ en todos los navegadores. Las de `media-manifest.json` se suman a ella.

## Contenido por defecto vs. contenido del usuario
- El contenido por defecto lo gestionas tú: sube o cambia imágenes en `fondos/`, `gente/` y `objetos/` y vuelve a desplegar. La app las carga sola, sin mostrar nada de carpetas ni de Netlify.
- Cada visitante puede añadir sus propias imágenes en la capa correspondiente; se guardan solo en su navegador. También puede desactivar las imágenes por defecto del sitio.
