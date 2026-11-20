# Grator

Web de **Grator Business SL** para [www.grator.net](https://www.grator.net).

Sitio estático, sin framework y sin build. Inglés por defecto, español en `/es/`.

- `/` — Inicio (EN)
- `/es/` — Inicio (ES)
- `public/brand/` — Logo y archivos reutilizables
- `BRAND.md` — Guía de marca, solo en el repositorio (no se publica)

## Despliegue

Proyecto de Vercel **grator-web**, equipo **grator**. Dominio de producción `www.grator.net`. `grator.net` redirige a `www`. No hay comando de build: Vercel publica el repositorio como sitio estático.

`vercel.json` fija `outputDirectory` en `.`. Si no, la carpeta `public/` (donde están los archivos de marca) pasa a ser la raíz publicada y la home desaparece.
