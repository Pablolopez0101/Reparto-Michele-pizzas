# Michele Pizzas · App de reparto

App web (funciona como app móvil) para gestionar pedidos, rutas e historial de ventas a panaderías.

## Cómo publicarla en GitHub Pages (gratis)

1. Ve a https://github.com y crea una cuenta si no tienes una.
2. Pulsa **New repository** (botón verde). Ponle un nombre, por ejemplo `michele-pizzas`. Déjalo en **Public**. Crea el repositorio.
3. Dentro del repositorio, pulsa **Add file → Upload files**.
4. Arrastra estos 6 archivos (todos los que hay en esta carpeta):
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
   - `favicon-32.png`
5. Pulsa **Commit changes**.
6. Ve a **Settings → Pages** (menú lateral izquierdo).
7. En "Build and deployment", selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
8. Espera 1-2 minutos. GitHub te dará una URL parecida a:
   `https://TU-USUARIO.github.io/michele-pizzas/`

## Instalarla en el móvil como si fuera una app

- **Android (Chrome):** abre esa URL → menú (⋮) → "Añadir a pantalla de inicio" / "Instalar app".
- **iPhone (Safari):** abre esa URL → botón compartir (□↑) → "Añadir a pantalla de inicio".

Se instalará con el icono de Michele Pizzas y se abrirá a pantalla completa, sin barra del navegador.

## Importante sobre los datos

Los pedidos y el historial se guardan **en el propio móvil/navegador** donde abras la app (localStorage).
Esto significa:
- Los datos no se pierden al cerrar la app ni al reiniciar el teléfono.
- Si la abres desde otro dispositivo o borras los datos del navegador, no verás el mismo historial.
- Si en el futuro quieres que varias personas vean los mismos pedidos desde distintos móviles a la vez, hay que añadir una base de datos en la nube (puedo ayudarte con eso si lo necesitas).

## Actualizar la app en el futuro

Si quieres cambiar algo, sube de nuevo el archivo `index.html` actualizado al repositorio (Add file → Upload files, sobrescribiendo el existente) y GitHub Pages se actualizará solo en un par de minutos.
