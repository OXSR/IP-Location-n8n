# IP Location API Workflow with n8n

Este repositorio contiene un flujo de trabajo de **n8n** que permite obtener la ubicación de una dirección IP, procesar los datos con **OpenAI (ChatGPT)** y personalizar la respuesta con **CSS y JavaScript** antes de enviarla al usuario.

## Flujo del Proceso

1. **Webhook (GET)** - Recibe solicitudes externas con una dirección IP como parámetro.
2. **Consulta a API Externa** - Envía la IP a un servicio externo de geolocalización para obtener datos.
3. **Procesamiento con OpenAI** - Utiliza ChatGPT para analizar y mejorar la respuesta JSON.
4. **Modificación con CSS y JS** - Personaliza la respuesta final con estilos y scripts antes de enviarla.
5. **Respuesta al Usuario** - Devuelve el resultado final a través del webhook.

## Tecnologías Utilizadas

- **[n8n](https://n8n.io/)** - Plataforma de automatización del flujo de trabajo.
- **API de Ubicación de IP** - Servicio de geolocalización basado en IP.
- **OpenAI (ChatGPT)** - Mejora y análisis de datos JSON.
- **CSS & JavaScript** - Personalización visual y funcional de la respuesta.
- **Webhooks** - Entrada y salida de datos en tiempo real.

## Cómo Usarlo

3. **Proporciona tu clave de OpenAI** en el nodo de procesamiento.
5. **Envía solicitudes GET al Webhook** con una IP como parámetro y recibe la respuesta enriquecida.
6. **Tiempo total de implementación** 5 minutos.
