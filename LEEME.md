# Bio-Bomba: Desactivación Celular

App web de Biología 1° inspirada en Keep Talking and Nobody Explodes.

## Archivos
- `index.html` — la app completa (bomba, manual, historial, registro).
- `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png` — hacen que se pueda instalar y que funcione sin internet.

## Publicar en GitHub Pages
1. En tu repositorio `gabrielgjg.github.io` crea la carpeta `biobomba`.
2. Sube ahí los 5 archivos (sin meterlos en otra subcarpeta).
3. Abre `https://gabrielgjg.github.io/biobomba/`.

## Conectar a tu registro único de juegos
1. En la app, abre «Registro en Google Sheets».
2. Pega la URL /exec de tu registro único (la misma de tus otros juegos) y presiona «Guardar URL».
3. Al terminar la primera ronda se crea sola la pestaña «BioBomba».

Si quieres que la URL venga puesta en cualquier computadora, pégala en `CONFIG.urlAppsScript` al inicio del código de `index.html`.

## Actualizar la app
Si cambias `index.html`, cambia también el número de versión (`biobomba-v4`, `v3`…) en `sw.js` para que las computadoras descarguen la versión nueva.
