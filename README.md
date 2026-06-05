# HR Buddy 🍫 - Asistente Virtual de RR.HH. para Chocola Tech

[![n8n](https://img.shields.io/badge/Orchestration-n8n-FF6C37?style=flat-square&logo=n8n)](https://n8n.io/)
[![Cohere](https://img.shields.io/badge/LLM-Cohere-A480FC?style=flat-square)](https://cohere.com/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Railway](https://img.shields.io/badge/Hosting-Railway-131313?style=flat-square&logo=railway)](https://railway.app/)
[![Telegram](https://img.shields.io/badge/UI-Telegram_Bot-26A5E4?style=flat-square&logo=telegram)](https://telegram.org/)

**HR Buddy** es un agente de Inteligencia Artificial y asistente virtual de Recursos Humanos desarrollado como proyecto práctico para el **Curso de Inmersión en Agentes IA**. El sistema fue diseñado para resolver consultas operativas y consultar datos personales de los empleados de la empresa ficticia *Chocola Tech*, utilizando un enfoque híbrido de bajo código y desarrollo de agentes avanzados.

---

## 🚀 Características Principales

*   🤖 **Agente de IA Cognitivo:** Orquestado en **n8n** utilizando el modelo **Cohere Chat Model** con memoria de conversación integrada (`Simple Memory`).
*   📚 **Arquitectura RAG (Retrieval-Augmented Generation):** Búsqueda semántica sobre políticas internas de la empresa utilizando `Cohere Embeddings` y `Simple Vector Store`.
*   🗄️ **Integración de Datos Relacionales:** Conexión en tiempo real con una base de datos **MySQL** alojada en **Railway** para consultar saldos de vacaciones, banco de horas y datos contractuales.
*   📱 **Interfaz Omnicanal:** Desplegado directamente como un Bot de **Telegram**.

---

## 📐 Arquitectura del Sistema

El flujo de trabajo implementa un patrón robusto que optimiza tanto el coste de los tokens como la seguridad del acceso a los datos:
