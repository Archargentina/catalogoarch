# ARCH · Catálogo
Sitio estático listo para subir a **GitHub Pages**.

## Estructura
```
arch-catalog/
├─ index.html
└─ assets/
   ├─ logo.png              # (opcional) tu logo
   ├─ placeholder1.jpg      # reemplazá por tu foto real
   ├─ placeholder2.jpg
   └─ placeholder3.jpg
```

## Cómo publicarlo en GitHub Pages (rápido)

### Opción A — Usuario/Sitio principal
1. Creá un repo llamado **tuusuario.github.io** (ej.: `santi.github.io`).
2. Subí el contenido de esta carpeta al repo (index.html y /assets).
3. Esperá 1–2 minutos y abrí: `https://tuusuario.github.io`.

### Opción B — Proyecto dentro de tu cuenta
1. Creá un repo con cualquier nombre (ej.: `arch-catalog`).
2. Subí los archivos.
3. En **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
4. La URL será: `https://tuusuario.github.io/arch-catalog/`

## Reemplazar el WhatsApp
Buscá `wa.me/54911XXXXXXXXX` en `index.html` y poné tu número en formato internacional:
- Argentina (ej. CABA): `54911TU_NUMERO`

Para personalizar el mensaje del chat, recordá url-encodear tildes/espacios.
Podés usar https://www.urlencoder.org/ para armar el texto.

## Imágenes
- Poné tus fotos en `assets/` y actualizá los `src` en `index.html`.
- El `<img>` del logo es opcional — si no existe `assets/logo.png`, no se muestra.

## Sugerencias
- Cambiá precios desde el HTML.
- Duplicá un `<article class="card">` por cada producto nuevo.
- Si más adelante querés “carrito”, podés migrar a Tiendanube o agregar links de MercadoPago a cada botón.
