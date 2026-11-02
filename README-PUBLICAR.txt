SIBERIAN VARIEDADES - estructura del proyecto
=============================================
index.html          Página principal (pequeña, solo la estructura)
css/styles.css      Estilos (colores, tipografías, diseño)
js/config.js        DATOS QUE EDITAS: CONFIG (WhatsApp, contacto, redes), categorías, rutas de fotos (IMG) y productos (PRODUCTS)
js/app.js           Lógica de la tienda (carrito, filtros, WhatsApp). No necesitas editarlo.
images/             Todas las fotos, ordenadas por categoría (formato WebP). Logo e iconos en images/
_headers            Configuración de caché para Netlify / Cloudflare Pages (opcional en otros hostings)

PARA PUBLICAR: sube TODO el contenido de esta carpeta (index.html, css, js, images y _headers) manteniendo la estructura.
No subas la carpeta "originales-respaldo" (es solo tu copia de seguridad).

PARA CAMBIAR O AGREGAR UNA FOTO:
1. Guarda la foto (idealmente cuadrada, 440x440 px, WebP o JPG) en images/<categoria>/
2. En js/config.js agrega o cambia su ruta en el bloque IMG (por ejemplo: miFoto: "images/cumpleanos/mi-foto.webp")
3. En el producto, usa img:IMG.miFoto
