# SARA ROM — versión web (estática)

Este repositorio contiene una conversión **estática** del PDF a **HTML/CSS/JS**.
Cada página del PDF se renderiza como imagen y se acompaña del texto extraído para accesibilidad.

## Estructura
- `index.html` — página principal con navegación por páginas y modo *scroll* continuo.
- `style.css` — estilos mínimos, sin dependencias externas (ideal para GitHub Pages).
- `assets/` — imágenes renderizadas de cada página del PDF (`page-1.jpg`, `page-2.jpg`, ...).

## Despliegue en GitHub Pages
1. Crea un repositorio nuevo en GitHub y sube todos los archivos de esta carpeta a la **raíz** del repo.
2. En **Settings → Pages**, elige **Deploy from a branch** con la rama `main` y la carpeta `/root`.
3. Guarda. Tu sitio estará en `https://TU_USUARIO.github.io/TU_REPO/`.

> Consejo: si ya tienes un dominio personalizado, añade un archivo `CNAME` con tu dominio en la raíz del repo.

## Créditos
- Origen PDF: `SR_D+UX_25.pdf`
- Conversión: PyMuPDF · 1 páginas procesadas.
