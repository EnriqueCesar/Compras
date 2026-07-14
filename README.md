# Compras Centro Norte

PWA ejecutiva, estática y 100% local para visualizar compras desde `Compras_Dtto_EC.xlsx`.

## Publicación en GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz del repositorio `Compras`.
2. En **Settings → Pages**, selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/ (root)`.
4. Guarda y espera la publicación.

## Excel

La aplicación carga automáticamente `data/Compras_Dtto_EC.xlsx` y permite reemplazarlo desde **Actualizar Excel**.

Pestañas requeridas:

- `Compras_Dtto_EC`
- `Clasificacion`

Pestaña opcional:

- `Directorio` con `CeCo`, `Tienda`, `Región` y `DM`.

La lectura se realiza por nombre de pestaña y encabezado. Los registros clasificados como `Baja` o `Baja Merch` se excluyen de toda la aplicación.
