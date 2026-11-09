# Atlético Deportivo Farallones · Landing page

Página pública de la escuela de fútbol (Cali). HTML, CSS y JavaScript en un solo archivo, sin dependencias.

## Antes de publicar
Abre `index.html` y edita el bloque `CONFIG` al final del archivo:

| Campo | Qué poner |
|---|---|
| `whatsapp` | Número con indicativo, sin + ni espacios. Ej.: `573101234567` |
| `appUrl` | URL de la app en Render. Ej.: `https://farallones-app.onrender.com` |
| `instagram` | Enlace del perfil de Instagram |
| `address` | Dirección o nombre de la cancha |

Foto del director: reemplaza el bloque marcado en la sección "La escuela" por
`<img src="assets/director.jpg" alt="Juan Sebastián Trujillo Espinal">` y sube la foto a `assets/`.

## Publicar en Render
1. Sube esta carpeta a un repositorio nuevo de GitHub (por ejemplo `farallones-landing`).
2. En Render: **New → Blueprint** y elige el repositorio. Render lee `render.yaml` y crea el sitio estático.
3. (Opcional) En **Settings → Custom Domains** conecta tu dominio, por ejemplo `farallones.co`.

## Tipografía y colores
- Títulos: Big Shoulders Display (800–900) · Texto: Barlow (400–700)
- Carmesí `#B0122C` · Carmesí profundo `#6E0A1A` · Negro `#000000` · Niebla `#F4F1F2`
