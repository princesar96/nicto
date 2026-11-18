# NICTO

EPK web de NICTO. Sitio estático: `index.html` y `assets/`.

## Actualizar contenido

- **Fotos de presentaciones en vivo:** agregarlas al arreglo `GALLERY` al final de `index.html` (hay un ejemplo comentado). Mientras esté vacío, la galería no se muestra.
- **Correo de booking:** `BOOKING_EMAIL` al final de `index.html` (el formulario y los enlaces lo usan).
- **Prensa y kit de prensa:** no existen todavía; el kit será este mismo sitio convertido a PDF.
- **Imágenes:** `assets/` (WebP optimizado; los logos son PNG con transparencia).

## Despliegue

Vercel, conectado a este repositorio. Cada push a `main` publica una nueva versión.
