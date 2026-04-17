# CROQUIS FERIA WASHINGTON — Contexto del proyecto

## Qué es este proyecto
Editor visual interactivo del croquis/mapa de la Feria Washington (predio ferial de Darwash SA).
Permite dibujar y editar corrales, caminos, zonas, áreas verdes, balanzas y referencias
sobre un plano del predio. Frontend puro sin backend.

## Archivos del proyecto
- index.html → toda la app (lógica + estilos + HTML + SVG en un solo archivo de ~72KB)
- README.md → solo el nombre del repo

## Stack
- HTML/CSS/JS vanilla
- SVG para el dibujo del croquis
- Google Fonts (Rajdhani + Courier Prime) vía CDN
- Sin backend, sin base de datos — el estado se persiste en localStorage o se exporta/importa JSON

## Themes visuales
El editor soporta 3 themes visuales (cambian las CSS variables):
- default (dorado/oscuro, inspirado en pizarra militar)
- theme-mid (azul/medio)
- theme-light (claro, tipo papel)

## Deploy
GitHub Pages → https://darwashsa-ux.github.io/croquisferiadw/

## Flujo git
git pull → editar index.html → git add → git commit → git push
