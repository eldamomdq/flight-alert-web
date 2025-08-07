# Buscador de vuelos automático ✈️

Este proyecto es un pequeño formulario HTML para registrar búsquedas de vuelos (origen, destino, fechas y cantidad de pasajeros). Los datos se envían a un webhook de n8n, que luego los procesa cada 3 horas y notifica por Telegram si encuentra buenos precios.

## Instrucciones

1. Edita el archivo `index.html` y reemplaza `https://TU_WEBHOOK_DE_N8N` con la URL de tu webhook.
2. Subí este repo a GitHub.
3. Conectalo a [Netlify](https://netlify.com) para desplegar la página.
