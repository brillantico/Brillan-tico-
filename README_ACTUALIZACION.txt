BRILLAN'TICO V6.1 — ACTUALIZACIÓN VERCEL

Subir TODO el contenido de esta carpeta a la raíz del mismo proyecto Vercel.

Archivos:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

Cambios:
- WhatsApp configurado en 50664212884, exactamente como fue solicitado.
- Envío directo a https://wa.me/NUMERO?text=... para evitar bloqueos de ventanas emergentes.
- Validación del número antes de registrar el pedido.
- PWA completa: manifest + service worker + iconos.
- Botón "Instalar app" mediante beforeinstallprompt.
- Caché v6.1 y actualización automática para sustituir la versión anterior.
- Pedidos guardan el _id real del producto.
- Reparado el puente de clientes/inventario que apuntaba a sendOrder aunque la app utiliza sendWhatsApp.

IMPORTANTE:
50664212884 quedó configurado como el número oficial de WhatsApp de BRILLAN'TICO para esta versión.
