# Nicode.js · Página del sistema de gestión

Página de venta del sistema de gestión para distribuidoras, pollerías, carnicerías y otros rubros. Es un sitio estático: `index.html` y la carpeta `img/`, sin nada que compilar.

## Publicarla gratis con GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `nicodejs`), público.
2. Subí el contenido de esta carpeta:
   ```
   git init
   git add .
   git commit -m "Página de Nicode.js"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/nicodejs.git
   git push -u origin main
   ```
3. En GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guardar.
4. En un par de minutos queda en `https://TU_USUARIO.github.io/nicodejs/`.

Si el repositorio se llama exactamente `TU_USUARIO.github.io`, la página queda en `https://TU_USUARIO.github.io/`.

## Cambiar datos

- **WhatsApp y mensaje automático:** en `index.html`, la línea `const WA = 'https://wa.me/5493815507992?text=...'`.
- **Teléfono, email y ubicación visibles:** sección `id="contacto"`.
- **Capturas:** carpeta `img/`. Las de computadora miden 1600 px de ancho y las de celular 640 px.

Las capturas son del sistema real con datos de ejemplo (clientes, productos e importes inventados).
