# CARRY · instalar gratis en el móvil, sin Claude

Esta carpeta es la app completa. Funciona sin conexión y guarda los datos en tu móvil.
Para tenerla en el iPhone, súbela una vez a un alojamiento gratuito (GitHub Pages) y fíjala en la pantalla de inicio desde Safari.

## 1. Publicarla gratis con GitHub Pages (unos 10 minutos, una sola vez)

1. Crea una cuenta gratuita en https://github.com (si no la tienes).
2. Arriba a la derecha, **+ → New repository**.
   - Nombre: `carry` (o el que quieras).
   - Visibilidad: **Public**. En el plan gratuito, Pages solo funciona con repositorios públicos.
     El repositorio solo contiene el código de la app: **tus datos no se suben nunca**, se quedan en tu móvil.
   - Pulsa **Create repository**.
3. En la página del repositorio: **Add file → Upload files**.
   Arrastra **todo el contenido de esta carpeta** (index.html, sw.js, manifest.webmanifest y las carpetas `fonts` e `icons`). Pulsa **Commit changes**.
4. **Settings → Pages**. En *Build and deployment*: Source **Deploy from a branch**, Branch **main** y carpeta **/ (root)**. Pulsa **Save**.
5. En uno o dos minutos la app estará en `https://TU-USUARIO.github.io/carry/`.

## 2. Instalarla en el iPhone

1. Abre esa dirección en **Safari**.
2. Botón **Compartir** → **Añadir a pantalla de inicio** → **Añadir**.
3. Ábrela siempre desde el icono **CARRY**: a pantalla completa, sin barra de Safari y sin conexión.

Abierta desde el icono, iOS trata la app aparte de Safari y no le aplica el borrado de datos por 7 días sin uso.

## 3. Tus datos

- Se guardan en el propio móvil. No hay cuenta ni servidor.
- **Haz una copia** de vez en cuando: Bolsa → **Descargar copia** y guárdala en iCloud Drive o en tu correo.
- Si cambias de móvil o borras la app: **Importar copia** y eliges ese archivo.
- Para pasar lo que tengas en la versión de Claude: allí, Bolsa → **Copiar copia**; aquí, **Importar copia** → pegar el texto.
- Si borras la app de la pantalla de inicio, iOS borra también sus datos: haz antes una copia.

## 4. Actualizar la app

Sube los archivos nuevos al mismo repositorio (Add file → Upload files, se sustituyen). La app se actualiza sola la próxima vez que la abras con conexión. Tus datos no se tocan.

## Alternativas igual de gratuitas

Netlify o Cloudflare Pages: arrastras la carpeta y te dan una dirección. Necesitan cuenta, como GitHub.
