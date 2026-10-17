# Sin Filtros — carpeta de trabajo

**El archivo bueno es `index.html` de esta carpeta.** Nada más.

Antes vivía en `Downloads/index.html` y el 12 de octubre una descarga de 20 MB
(una presentación "Reflectiv") lo sobrescribió: se perdió la versión parcheada y
hubo que reconstruirla. Por eso ahora tiene carpeta propia — Downloads es un buzón
de descargas, no un sitio para guardar trabajo.

## Cómo trabajar

1. Se edita **siempre** `sin-filtros/index.html`.
2. Antes de cada cambio grande se deja copia en `respaldos/index-AAAAMMDD-HHMM.html`.
3. Ese mismo `index.html` es el que se sube a GitHub Pages (mismo nombre).
4. Si bajas el archivo desde el navegador o desde el chat, **muévelo aquí** y
   reemplaza el `index.html`; no lo dejes suelto en Downloads.

## Respaldos

| Archivo | Qué es |
|---|---|
| `respaldos/index-20261011-original-sin-parches.html` | Versión original, antes de cualquier arreglo |
| `respaldos/index-AAAAMMDD-HHMM.html` | Copia de cada versión entregada |

## Backend

Google Apps Script (`/exec`), hoja de cálculo + Drive + Gemini.
La URL de la API está en la constante `API`, al principio del `<script>`.

## Fechas clave configuradas en el código

| Constante | Valor | Para qué |
|---|---|---|
| `PESAJE_LUNES` | `2026-10-19` | Desde ese lunes el pesaje es los lunes (antes, domingos) |
| `DEC` | `2026-12-15` | Arranca el modo diciembre |
| `PROG_FECHAS` | 1 oct, 1 nov, 1 dic, 31 dic | Fotos de progreso |
| `PERDON` | ver el código | Días perdonados por fallos de la app |
