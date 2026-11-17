# Mi Dinero (PWA)

Aplicación web progresiva sencilla para registrar ingresos, gastos y presupuestos.

## Archivos
- `index.html`: aplicación completa.
- `manifest.webmanifest`: nombre e instalación.
- `sw.js`: caché básica para funcionamiento sin conexión tras la primera visita.
- `icon.svg`: icono.

## Publicación gratuita
Se puede publicar como sitio estático HTTPS. Por ejemplo, GitHub Pages permite publicar archivos HTML/CSS/JS desde un repositorio. En el plan gratuito, el repositorio debe ser público.

1. Crea una cuenta en GitHub.
2. Crea un repositorio nuevo, por ejemplo `mi-dinero`.
3. Sube los cuatro archivos de esta carpeta a la raíz del repositorio.
4. En el repositorio abre Settings > Pages.
5. En Build and deployment, selecciona Deploy from a branch, rama `main`, carpeta `/ (root)` y guarda.
6. Espera a que GitHub muestre la dirección publicada en Settings > Pages.

## Instalar
En Android: abre la dirección publicada en Chrome > menú ⋮ > `Instalar app` o `Instalar y crear acceso directo`.
En ordenador: abre la web en Chrome o Edge y utiliza el icono de instalación de la barra de direcciones o el menú del navegador.

## Datos y privacidad
Los movimientos y presupuestos se guardan únicamente en el almacenamiento local del navegador (`localStorage`). No se envían a una cuenta ni se sincronizan entre dispositivos. Si borras los datos del navegador o cambias de dispositivo, puedes perder el historial. Usa `Exportar CSV` para guardar copias de tus movimientos. El código del repositorio público es visible, pero los datos locales no se publican en GitHub.

No introduzcas claves bancarias ni datos de acceso a tu banco. Esta versión no se conecta a entidades financieras.
