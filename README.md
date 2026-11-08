# Marie · Depilación descartable y pedicuría

App de turnos para clientas. Es una página web: un solo archivo (`index.html`), sin instalar nada.

## Subirla a GitHub y publicarla gratis (GitHub Pages)

1. Entrá a https://github.com y creá una cuenta (o iniciá sesión).
2. Tocá **New repository**. Nombre: `marie-turnos`. Dejalo en **Public**. Tocá **Create repository**.
3. Tocá **uploading an existing file** y subí todos los archivos de esta carpeta:
   `index.html`, `manifest.json`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`.
4. Tocá **Commit changes**.
5. Andá a **Settings > Pages**. En **Branch** elegí `main` y la carpeta `/ (root)`. Tocá **Save**.
6. En 1 o 2 minutos tu página queda en: `https://TU-USUARIO.github.io/marie-turnos/`

Ese link es el que se le pasa a las clientas (por WhatsApp o Instagram).

## Instalarla en el celular como app
- **Android (Chrome):** menú de 3 puntitos > Agregar a la pantalla principal.
- **iPhone (Safari):** botón Compartir > Agregar a inicio.

## Qué cambiar
- Número de WhatsApp: buscá `5491163243549` en `index.html` (aparece varias veces).
- Servicios y precios: buscá `var CATS=` en `index.html`.
- Horarios: están en el texto de la pantalla de inicio y en la función `drawHours`.
