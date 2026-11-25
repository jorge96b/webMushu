# Web Múshu
Sitio estático. Abrir `index.html` con un servidor (no con doble clic).
- Local: `python3 -m http.server 8000` y abrir http://localhost:8000
- Deploy: `npx vercel --prod` desde esta carpeta (o conectar el repo de GitHub en Vercel).
- Feed de Instagram: constante `BEHOLD_FEED` en index.html.
- Formularios: llegan a mushububbletea@outlook.com vía FormSubmit (activar con el primer correo).
- Imágenes: usar WebP en `assets/` (las PNG/JPG originales se convirtieron con calidad 82, logos con 90). Solo quedan `assets/stores/lagoverde.jpg` (og:image para redes) y `assets/brand/mascot-k.png` (favicon). Las imágenes fuera de la primera pantalla llevan `loading="lazy"`.
