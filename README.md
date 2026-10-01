# Räisen — sitio web

Sitio estático en HTML, CSS y JS vanilla. No tiene dependencias ni paso de build.

## Estructura
- `index.html`: la página completa (one-page)
- `css/styles.css`: estilos. Los colores de marca están como variables en `:root`
- `js/main.js`: menú móvil, animaciones y formulario a WhatsApp. El número está en la constante `WHATSAPP`
- `assets/`: fuentes Metropolis (woff2), isotipo, íconos y fotos

## Ver en local
Abrí `index.html` en el navegador o serví la carpeta:

    python3 -m http.server 8000

## Publicar
Subí la carpeta tal cual a cualquier hosting estático (Netlify, Vercel, Cloudflare Pages o el mismo hosting por FTP/cPanel, en `public_html`).
