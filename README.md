# Mi Lifestyle

Panel personal de horario, nutricion y rutina para publicar en GitHub Pages.

## Archivos

- `index.html` - la app principal
- `manifest.json` - configuracion PWA
- `sw.js` - service worker (funciona sin internet)
- `icon-192.png` / `icon-512.png` - iconos de la app

## Funciona sin internet

Una vez cargada la primera vez, el service worker guarda todo en cache.
Los pesos y checks se guardan en localStorage del navegador.
