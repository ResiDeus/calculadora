# Calculadora de Resi

Calculadora tipo PWA hecha en Puerto Rico para echar cuentas de **compras**, **salario** y **conversiones** de unidades, con recibo, temas neon y soporte ES/EN.

## Qué hace

- **Modo compras:** lista de artículos, IVU, descuento, propina y “serrucho” (dividir la cuenta).
- **Modo salario:** paga por hora, horas/semana, regímenes W-2 / 1099 / N/A, Seguro Social y Medicare.
- **Modo conversión:** peso, volumen, distancia, temperatura, moneda y más.
- **Recibo:** detalle de la cuenta listo para copiar.
- **Temas** e **idioma** que se guardan en el dispositivo.
- La lista de compras se guarda en el navegador (`localStorage`).

## Cómo usarla

1. Abre `index.html` en el navegador (Chrome, Safari, etc.).
2. O sírvela como sitio estático / PWA con un servidor local o hosting.
3. En móvil puedes “Añadir a pantalla de inicio” para usarla como app.

## Archivos típicos

- `index.html` — app completa (HTML + CSS + JS)
- `manifest.json` — metadatos PWA
- `icon.jpg` / icono de app — icono para pantalla de inicio y tiendas

## Notas técnicas

- Una sola página, sin backend.
- Persistencia local: lista de compras, tema e idioma.
- **Borrar todo** limpia la lista en pantalla y en almacenamiento local.

## Privacidad

No envía tus datos a un servidor. Todo se calcula y se guarda en el dispositivo.

## Créditos

Creado por ResiDeus. Hecha para uso en **Puerto Rico** (IVU, contextos de nómina locales, UX en español).
