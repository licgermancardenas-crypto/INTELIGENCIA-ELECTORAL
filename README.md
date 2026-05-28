# Atlas Analytics — Inteligencia Electoral

Presentación interactiva del servicio **Inteligencia Electoral** de Atlas Analytics.

Construida en HTML + reveal.js, con animaciones, parallax, contadores y elementos interactivos. Diseñada para presentación en vivo a candidatos, jefes de campaña y consultores estratégicos.

## Stack

- [reveal.js 5.1](https://revealjs.com/) (CDN)
- Tipografía: Cormorant Garamond + Inter + JetBrains Mono (Google Fonts)
- Sin build step: 100% HTML/CSS/JS estático

## Estructura

```
.
├── index.html        # Presentación completa
├── assets/           # Imágenes de fondo (8 backgrounds)
└── vercel.json       # Config de cache para Vercel
```

## Uso local

Abrir `index.html` directamente en el navegador. Sin servidor necesario.

## Deploy en Vercel

```bash
# Opción A: CLI
npm i -g vercel
vercel

# Opción B: Web
# 1. vercel.com → New Project → Import desde GitHub
# 2. Seleccionar este repo → Deploy (sin build settings)
```

Vercel detecta automáticamente HTML estático en raíz. El deploy tarda ~30 segundos.

## Atajos de teclado

- `←` `→` `Espacio` — navegar slides
- `F` — pantalla completa
- `ESC` — vista general (overview)
- `S` — modo presentador (notas + reloj)
- `?` — ver todos los atajos
- URL `#/5` — saltar al slide 5

## Exportar a PDF

Agregar `?print-pdf` al final de la URL, imprimir → guardar como PDF.

## Personalización por cliente

Editar en `index.html`:
- Métricas: buscar `data-to="..."` (animan al entrar el slide)
- Contacto en cierre: buscar `mailto:contacto@atlasanalytics.ar`
- Branding: variables CSS en `:root` (paleta violeta/oro)

---

© Atlas Analytics
