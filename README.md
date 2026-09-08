# Grator — Web genérica

Web corporativa de **Grator Business SL** para [www.grator.net](https://www.grator.net).

Sitio estático (HTML/CSS/JS, sin build), bilingüe:

- `/` — Inglés (idioma por defecto)
- `/es/` — Español

## Estructura

```
index.html        # Home (EN)
es/index.html      # Home (ES)
assets/style.css   # Estilos compartidos
assets/script.js   # Menú móvil + año del footer
```

## Contenido

Basado en el brief "WEB genérica Grator.net":

- Compañía de inversiones
- Origen y hilo conductor: proyectos tecnológicos
- Otras áreas: Valores y fondos, Inmobiliario, Participaciones, Soluciones tecnológicas
- Área privada (enlace de acceso a las apps internas del grupo)

> El enlace de "Área privada" apunta a `https://cuenta.grator.net` como valor por defecto (siguiendo la convención del repo `cuenta-grator`). Actualízalo en `index.html` y `es/index.html` si la URL real de acceso es distinta.

## Despliegue

Pensado para desplegarse en Vercel como sitio estático (sin framework, sin build command). Apuntar el dominio `www.grator.net` (y `grator.net`) a este proyecto de Vercel.
