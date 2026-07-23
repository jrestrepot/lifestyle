# Mi Rutina de Gym - PWA

Rutina de gym personalizada: 3 dias, recomposicion corporal, adaptada a anteversion femoral.

## Archivos

- `rutina.html` - la app principal
- `manifest.json` - configuracion PWA
- `sw.js` - service worker (funciona sin internet)
- `icon-192.png` / `icon-512.png` - iconos de la app

## Instalar en el celular via GitHub Pages

1. Crea un repositorio en github.com (puede ser privado)
2. Sube todos los archivos de esta carpeta
3. Ve a Settings > Pages > Source: main branch, carpeta raiz
4. Espera 1-2 minutos, te da una URL tipo: `https://tuusuario.github.io/nombre-repo`
5. Abre esa URL desde el celular
6. En iOS (Safari): boton compartir > "Agregar a pantalla de inicio"
   En Android (Chrome): aparece un banner automatico "Instalar app"

## Funciona sin internet

Una vez cargada la primera vez, el service worker guarda todo en cache.
Los pesos y checks se guardan en localStorage del navegador.
