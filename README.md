movi-assistant-bot
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

🖥️ Interfaz del Agente
Movi cuenta con una interfaz de chat web intuitiva y funcional, optimizada para facilitar la consulta rápida de estados de cuenta y procedimientos técnicos. La interfaz permite la visualización clara de datos estructurados mediante tablas, garantizando una lectura ágil para el colaborador.

⚙️ Mantenimiento y Evolución
Para asegurar la relevancia y fiabilidad del agente, hemos establecido los siguientes procesos:

Sincronización en tiempo real: Movi opera conectada directamente a la fuente maestra (Google Sheets), por lo que cualquier actualización en los documentos se refleja de forma inmediata.

Ciclo de mejora continua: Se realiza un monitoreo periódico de las consultas no resueltas, utilizándolas como insumo para identificar vacíos de información y actualizar la base de conocimientos.

Curaduría de datos: Un equipo designado es responsable de auditar la veracidad de los datos cargados en la planilla para evitar inconsistencias.

☁️ Despliegue en OCI
(Aquí insertaremos la imagen o video del agente funcionando en la nube).

🛠️ Tecnologías Utilizadas

Lenguaje: Python

Orquestador: n8n

IA: Google Gemini API

Nube: Oracle Cloud Infrastructure (OCI)

Control de Versiones: GitHub
