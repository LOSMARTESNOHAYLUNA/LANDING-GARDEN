# Mallorca Garden Solution — Landing (ES / EN)

Landing publicitaria bilingüe de mantenimiento de jardín premium en Mallorca.
URLs separadas por idioma para campañas de Google Ads.

## Estructura
- `index.html` — versión española (URL: `/`)
- `en.html` — versión inglesa (URL: `/en`)
- `img/` — 5 imágenes del cliente (compartidas)
- `vercel.json` — URLs limpias + ruta `/en`

## URLs para Google Ads
- Campaña ES → `https://TU-DOMINIO.vercel.app/`
- Campaña EN → `https://TU-DOMINIO.vercel.app/en`

## Cookies y consentimiento (RGPD)
Banner de consentimiento previo con Google Consent Mode v2 en ambos idiomas.
Por defecto NIEGA ad_storage, ad_user_data, ad_personalization y analytics_storage
hasta que el usuario acepta. Botones: Aceptar / Rechazar / Configurar.

### ⚠️ Para activar Google Ads / Analytics
En el `<head>` de `index.html` y `en.html` hay un bloque comentado con `G-XXXXXXX`.
Descoméntalo y sustituye por tu ID real de medición (Ads: AW-XXXX / GA4: G-XXXX).
El consentimiento ya está cableado: los tags solo cargarán tras aceptar.

## Contacto configurado
- WhatsApp y llamada: 621 49 39 77
- Llamada fija: 971 96 74 13

## Pendiente
- Conectar el formulario a un destino real (ahora muestra confirmación demo, no envía).
- Enlazar la política de cookies real (ahora el enlace apunta a `#`).
