# movi-assistant-bot

🚀 Movi: Asistente Operativo de MoviTrack Py
📝 Descripción del Proyecto
Movi es un agente de inteligencia artificial diseñado para optimizar la gestión operativa y administrativa de MoviTrack Py. Este asistente actúa como una base de conocimiento centralizada para los empleados, permitiendo una resolución ágil de consultas técnicas, gestión de clientes y aplicación de políticas contractuales.

Movi está diseñado para estandarizar procesos críticos como la resolución de fallas técnicas, la verificación de estados de cuenta antes de asistencias de emergencia y la gestión de activos.

🏗️ Arquitectura
El agente utiliza una arquitectura RAG (Retrieval-Augmented Generation):

Ingesta: Procesamiento de manuales técnicos (PDF), políticas de contratación (Word) y protocolos de asistencia (Markdown).

Orquestación: n8n para la gestión de flujos de trabajo y lógica de consultas.

Inteligencia: Google Gemini como LLM para el razonamiento operativo.

Infraestructura: Despliegue en Oracle Cloud Infrastructure (OCI).

📂 Capacidades del Agente
Movi está capacitado para asistir a los colaboradores en:

Soporte Técnico: Diagnóstico de dispositivos GPS con mal funcionamiento.

Gestión de Clientes: Creación de usuarios nuevos y búsqueda rápida de vehículos mediante número de chapa.

Búsqueda Administrativa: Localización de clientes por número de cédula.

Políticas de Recuperación: Aplicación de protocolos para la recuperación de equipos por morosidad o finalización de servicio.

Protocolos de Asistencia: Verificación obligatoria de estado de cuenta (al día) para asistencia en casos de robo, bajo el marco de contratos mínimos de 12 meses.

☁️ Despliegue en OCI
(Aquí insertaremos la imagen o video del agente funcionando en la nube).

🛠️ Tecnologías Utilizadas
Lenguaje: Python

Orquestador: n8n

IA: Google Gemini API

Nube: Oracle Cloud Infrastructure (OCI)

Control de Versiones: GitHub
