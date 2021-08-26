
# Rutas en Next js

Nuestras rutas estan basada en el file system. Solo tengo que agregar un archivo en pages y lo toma como una ruta. La ruta base en / es `index.js`.

## Rutas dinamicas

Ejemplo cuando creo una carpeta en `pages` llamada `products` y un archivo  llamado `[id].js` puedo sustituir en mi path la ruta `products/erycydh` siendo `erycydh` tomado como el `id ` de uno de mis componentes. 

Para capturar los `id` hago uso del hook `{ useRouter } ` de `next/router`.

