# Alfa Espacio de Belleza Bot

Este directorio contiene la automatización y las integraciones para Alfa Espacio de Belleza.

## Descripción

Incluye:

- Automatización de WhatsApp usando flujos de n8n para responder consultas y enviar campañas.
- Configuraciones de Docker y docker-compose para ejecutar el bot.
- Archivo de variables de entorno de ejemplo (`.env.example`).
- Ejemplo de flujo n8n en la carpeta `workflows`.
- Estructura de proyecto Node.js (`package.json`) para código del servidor.

## Primeros pasos

1. Clona el repositorio.
2. Copia `.env.example` a `.env` y completa tus credenciales (Twilio, Google Sheets, DashScope, etc.).
3. Construye y ejecuta el contenedor usando Docker Compose:
   ```bash
   docker-compose up --build
   ```
4. Accede al panel de n8n para importar tus workflows.

Este proyecto fue creado para Alfa Espacio de Belleza con el objetivo de gestionar las comunicaciones con clientes y el análisis de datos.
