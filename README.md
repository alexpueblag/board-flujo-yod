# Board Flujo · YoDesarrollo

Board de flujo con bolsas por proyecto, sincronizado con Google Sheets ("YOD - Flujo 2026").

## URL en vivo
https://alexpueblag.github.io/board-flujo-yod/

## Cómo funciona
- Acceso por palabra clave (vive en Config!B2 del Sheet; se puede cambiar desde el board con 🔑).
- Datos: Google Sheet vía Apps Script (pestañas Movimientos, PagosPlanificados, IngresosEsperados, Bolsas, Config, Historial).
- Nada se borra: historial append-only.
- Los movimientos de WhatsApp ("Yod: Flujo 2026") los sincroniza Claude y los escribe al Sheet.
