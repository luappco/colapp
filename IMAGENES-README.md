# 📁 LUAPP — Estructura de Imágenes

## Carpetas y qué va en cada una

### 📂 images/logo/
- `logo-color.png`       → Logo principal (fondo claro)
- `logo-blanco.png`      → Logo en blanco (para fondo oscuro)
- `logo-icono.png`       → Solo el ícono llama+corazón
- `logo-color.svg`       → Logo vectorial (mejor calidad)
- `favicon.ico`          → Ícono del navegador 32x32
- `favicon.svg`          → Ícono SVG del navegador
- `apple-touch-icon.png` → Ícono para iPhone 180x180

### 📂 images/app/
Capturas de pantalla de la app (mockups):
- `screen-home.png`      → Pantalla explorar perfiles
- `screen-chat.png`      → Pantalla de chat
- `screen-perfil.png`    → Pantalla de perfil
- `screen-creditos.png`  → Pantalla de créditos
- `screen-registro.png`  → Pantalla de registro

### 📂 images/banner/
- `hero-banner.jpg`      → Imagen principal del hero (1920x1080)
- `og-image.jpg`         → Imagen para redes sociales (1200x630)
- `banner-mobile.jpg`    → Banner versión móvil (768x1024)

### 📂 images/social/
Posts y contenido para redes sociales:
- `post-frase-01.jpg`
- `post-meme-01.jpg`
- `post-encuesta-01.jpg`
- `post-estadistica-01.jpg`

### 📂 images/icons/
Íconos de la interfaz:
- `icon-lock.svg`
- `icon-heart.svg`
- `icon-flame.svg`
- `icon-chat.svg`

## 📐 Tamaños recomendados

| Imagen | Tamaño | Formato |
|---|---|---|
| Logo principal | 800x200px | SVG o PNG |
| Ícono app | 512x512px | PNG |
| Favicon | 32x32px | ICO + SVG |
| Apple Touch | 180x180px | PNG |
| OG Image | 1200x630px | JPG |
| Hero Banner | 1920x1080px | JPG/WebP |
| Screenshots app | 390x844px | PNG |

## 🚀 Cómo subir a Hostinger

1. Abre el **File Manager** en hPanel de Hostinger
2. Ve a la carpeta `public_html`
3. Crea la carpeta `images` con estas subcarpetas
4. Sube cada imagen en su carpeta correspondiente
5. Las rutas en el HTML serán: `/images/logo/logo-color.png`
