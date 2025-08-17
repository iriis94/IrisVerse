# IrisVerse — Landing para Etsy (HTML estático)

Landing minimalista y mobile‑first para redirigir tráfico de redes a tu tienda de Etsy.

## Estructura
- `index.html` — página única con CSS/JS embebidos
- `assets/og-placeholder.jpg` — imagen OG para compartir en redes

## Cómo subirlo a GitHub y activar Pages
1. Crea un repositorio nuevo (por ejemplo `irisverse-landing`).
2. Sube **index.html** y la carpeta **assets**.
3. Ve a **Settings → Pages** y en *Branch* elige `main` y `/ (root)` → **Save**.
4. Tu web quedará publicada en: `https://<tu-usuario>.github.io/irisverse-landing/`

> Si usas dominio propio, añade un archivo `CNAME` con tu dominio y apúntalo a GitHub Pages.

## Cosas a personalizar
- Cambia los enlaces `https://www.etsy.com/...` por tus listings reales.
- Sustituye el placeholder del hero por tu imagen.
- Edita colores en `:root` (variables CSS).
- Conecta el formulario a Tally/MailerLite/Beehiiv (cambia `onsubmit`).

## Licencia
Este proyecto se publica bajo licencia MIT. Modifícalo libremente para tus fines.
