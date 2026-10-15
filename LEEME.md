# Monserrate también es su gente

Micrositio de las familias vendedoras del sendero a Monserrate.

## Cómo publicarlo en GitHub Pages

1. En github.com, cree un repositorio **público** (por ejemplo `monserrate`).
2. Pulse **Add file → Upload files** y arrastre **todo el contenido de esta carpeta**
   (`index.html`, `LEEME.md` y la carpeta `img`). Pulse **Commit changes**.
3. Vaya a **Settings → Pages**. En *Branch* elija `main` y `/ (root)` y pulse **Save**.
4. Espere 1 o 2 minutos. El sitio queda en `https://SU-USUARIO.github.io/monserrate/`.

## Qué cambiar después de publicar

**El QR y los botones de compartir no necesitan cambios:** usan automáticamente
la dirección donde esté publicado el sitio.

**La vista previa al compartir (foto y título en WhatsApp o Facebook):** abra
`index.html` en GitHub (ícono del lápiz) y, al comienzo del archivo, reemplace
las 2 apariciones de `https://SU-USUARIO.github.io/SU-REPOSITORIO/` por la
dirección real del sitio.

**Redes y logos de quienes acompañan:** busque en `index.html` el bloque
`CONFIGURACIÓN`. Ahí puede cambiar enlaces de redes (las que queden vacías
no se muestran). Los logos están en `img/logos/`.

**Si quiere fijar otra dirección para el QR** (por ejemplo un dominio propio),
escríbala en `const SITE_URL = "";`, dentro del mismo bloque.

## Imprimir el QR

Abra el sitio publicado: al final de la sección "Compártelo ahora" aparece el
QR con la dirección correcta. Tome una captura o use cualquier generador de QR
con la dirección del sitio.
