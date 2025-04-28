# Agente_IA
Este proyecto implementa un agente conversacional turístico que permite a los usuarios obtener recomendaciones acerca de lugares turísticos, clima presente en los mismos, asi como actividades cercanas basadas en una fecha dada por el usuario. El agente utiliza un enfoque de Recuperación Aumentada por Generación (RAG) junto con la búsqueda web para proporcionar información en tiempo real.
Se ha creado una interaz interactiva usando Gradio para una mejor experiencia por parte del usuario. Se realiza una consulta sobre datos climaticos para la fecha dada por el usuario usando la API de la aplicacion web tomorrow.io

Instalacion y configuracion:
- Claves API: Este proyecto requiere de 3 claves API para acceder a información del clima (tomorrow.io), conversion de nombre del lugar a sus coordenadas (opencagedata.com) y uso de un LLM (groq).
- Entorno de ejecución: El código se encuentra diseñado para ser ejecutado en Google Colab.
- Dependencias: El código usa librerias como gradio, requests, python-dotenv, entre otras.

Instrucciones de uso:
- Colocar las claves de las APIs de las aplicaciones web mencionadas en un .env file para mantener la seguridad y acceder a las variables.
- Ejecutar todo el código presente y finalmente el código de la interfaz de gradio en Google Colab para interactuar con el agente.
- Realizar preguntas relacionadas con lugares y proporcionar la fecha en la cual se desee realizar el viaje.
