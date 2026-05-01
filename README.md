🤖 AGENTE DE MARKETING AUTOMATIZADO - GRUPO #4
Este proyecto consiste en una aplicación multi-agente diseñada para automatizar la creación de propuestas comerciales de marketing personalizadas. Utiliza LangGraph para la orquestación de agentes inteligentes y Claude (Anthropic) como motor de lenguaje.


👥 Integrantes
Álvaro Augusto Andrade Quesada

Juan Pablo Ortega Vargas

Clase: Software de Automatización
Grupo: #4


🚀 Descripción del Proyecto
El sistema utiliza una arquitectura de cuatro agentes especializados que trabajan en cadena para transformar una idea de negocio en una propuesta comercial completa y profesional:

Analista de Mercado: Realiza un análisis PEST y detecta puntos de dolor.

Estratega de Marca: Define el Messaging Canvas y la identidad estratégica.

Redactor Comercial: Estructura la propuesta bajo el framework StoryBrand.

Editor Senior: Aplica una rúbrica de calidad PACT para el acabado final.


🛠️ Stack Tecnológico
Frontend: Streamlit para la interfaz de usuario.

Orquestación: LangGraph para el flujo de trabajo multi-agente.

LLM: Claude-3-5-Sonnet (vía LangChain Anthropic).

Documentación: ReportLab para la generación de propuestas en PDF.

Lenguaje: Python 3.10+.


📂 Estructura de Archivos Principal
app.py: El corazón de la aplicación (Agentes + UI).

.claude/: Configuraciones avanzadas para la asistencia de IA.

.env: Almacenamiento seguro de la API Key (No incluido en el repo).

requirements.txt: Librerías necesarias para el funcionamiento.
