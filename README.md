![n8n](https://img.shields.io/badge/n8n-FF6D5B?style=for-the-badge&logo=n8n&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Llama3.2](https://img.shields.io/badge/Llama_3.2-041E42?style=for-the-badge&logo=meta&logoColor=white)
# 🚀 AI-Driven Automation Agent (Self-Hosted)

Este proyecto demuestra la implementación de un **Agente de Inteligencia Artificial totalmente autónomo** y privado, capaz de procesar información compleja, razonar sobre ella y ejecutar acciones de comunicación en tiempo real.

## 🧠 Arquitectura del Sistema
El flujo de trabajo (Workflow) integra tres capas tecnológicas fundamentales:

1. **Capa de Entrada (Ingestion):** Captura de datos estructurados/no estructurados.
2. **Capa de Inteligencia (Inference):** Procesamiento de lenguaje natural utilizando **Llama 3.2** ejecutado localmente, garantizando privacidad y latencia mínima.
3. **Capa de Acción (Delivery):** Notificación automática y formateada a través de la API de **Telegram**.

## 🛠️ Stack Tecnológico
- **Orquestador:** n8n (Node-based Automation Tool).
- **Motor de IA:** Ollama (Local LLM Runtime).
- **Modelo:** Llama 3.2.
- **Comunicación:** Telegram Bot API.

## 🌟 Características Principales
- **Zero-Cloud Dependency:** Todo el procesamiento de IA ocurre en hardware local, eliminando costes de API (OpenAI/Claude) y protegiendo la privacidad de los datos.
- **Prompt Engineering:** Configuración avanzada de instrucciones para obtener respuestas estructuradas y accionables.
- **Real-Time Alerts:** Notificaciones push inmediatas basadas en el análisis del agente.

## 📊 Flujo de Datos


1. Se recibe un input a través de un disparador manual o webhook.
2. El modelo **Llama 3.2** analiza la carga útil (payload) bajo un contexto predefinido.
3. El resultado se formatea dinámicamente.
4. Se despacha un mensaje enriquecido al usuario vía Telegram.

---
**Desarrollado por Víctor Chaves** *Especialista en Automatización y Tecnologías de IA Aplicada.*