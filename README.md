# Kratos Analytics — Site

Sitio público de Kratos Analytics LLC: score-as-a-service con datos alternativos (tipo Bre-B) para cooperativas de ahorro y crédito de la región del Llano / Orinoquía, Colombia.

**En vivo:** https://kratos-analytics.com

## Qué es esto

`index.html` es un componente autocontenido (bilingüe ES/EN, un solo archivo) construido con [Claude Design](https://claude.ai/design). `support.js` es el runtime `dc-runtime` generado que lo hace funcionar — no se edita a mano, se regenera desde la fuente del proyecto de diseño.

## Estructura

- `index.html` — el sitio completo (hero con video de fondo, secciones de producto, demo de scoring, oferta, manejo de datos, contacto).
- `support.js` — runtime generado (bundle de renderizado del componente).
- `assets/` — wordmark y favicon en SVG.

## Deploy

Hosteado como sitio estático en Cloudflare Pages, dominio `kratos-analytics.com` (con redirect 301 desde `www`). Cualquier hosting estático sirve: no hay build step, `index.html` + `support.js` + `assets/` es todo lo que se necesita.

## Marca

Sigue la identidad de marca de Kratos Analytics LLC: Obsidiana `#0D0D0D` / Ceniza `#EDEAE3` / Oro `#C9A227` (acento único por vista) / Carbón `#2C2C2A`. Tipografía Space Grotesk (títulos), Inter (cuerpo), IBM Plex Mono (números/datos).
