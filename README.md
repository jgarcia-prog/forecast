# Forecast — COFERSA Metas Q2 2026

Dashboard de cálculo de metas de ventas Q2 2026. Progressive Web App (PWA) — instalable en escritorio y móvil.

## Stack
- HTML/CSS/JS puro (sin frameworks)
- Chart.js para gráficos
- SheetJS (xlsx) para importar/exportar Excel
- Service Worker para funcionamiento offline

## Deploy
Hosted en [Vercel](https://vercel.com). Cada push a `main` despliega automáticamente.

## Uso local
```bash
# Cualquier servidor estático sirve:
npx serve .
# o
python3 -m http.server 3000
```

> ⚠️ Debe abrirse desde un servidor HTTP (no `file://`) para que el Service Worker funcione.
