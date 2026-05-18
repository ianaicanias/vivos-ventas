# Registro de Vivos — Sistema de Ventas

Sistema de registro de ventas para vivos de Instagram.

## Estructura

```
vivos-ventas/
├── index.html    # Web app para cargar vivos
├── webapp.gs     # Apps Script (Web App en Google Sheets)
└── README.md     # Este archivo
```

## Cómo usar

1. Abrí la web: https://ianaicanias.github.io/vivos-ventas/
2. Pegá la lista del vivo
3. Revisá el resumen
4. Guardá en Sheet

## Formato de la lista

```
GOLD 89 (99) — 30/04/2026
_______________
TG3022 28X790 490
TG3118 19X790 490
...
_______________
TOTAL 99
```

## Google Sheet

Los datos se guardan en: https://docs.google.com/spreadsheets/d/1UL5XguNxx_HPr4wqtpx_UXFYqn_P1t8a71-fx1N43TE

### Hojas
- **VENTAS** — registro de todos los vivos
- **COSTOS** — costos por código de producto (completar por papá)
- **ESTADÍSTICAS** — resumen por producto (automático)
- **RESUMEN MENSUAL** — resumen por mes (automático)

## Actualizar costos

Cuando lleguen productos nuevos, agregar el código y costo en la hoja COSTOS del Sheet.
También actualizar la tabla `COSTOS` en `index.html`.
