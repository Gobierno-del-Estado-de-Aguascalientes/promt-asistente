# Proyecto de Prompts para Asistente de IA

Este proyecto está dedicado al desarrollo, refinamiento y documentación de prompts para un Asistente de Inteligencia Artificial del Gobierno del Estado de Aguascalientes, México.

## 📋 Descripción

El objetivo principal de este proyecto es crear y mantener prompts optimizados que permitan a un asistente virtual de IA brindar información precisa, útil y contextualizada sobre trámites y servicios gubernamentales del Estado de Aguascalientes, manteniendo siempre un tono profesional, cálido y respetuoso.

## 🗂️ Estructura del Proyecto

```
promt/
├── Base/
│   ├── PROMPT COMPORTAMIENTO PARA BOT AGS.txt
│   └── PROMT MASTER.txt
├── PROMP_ASISTENTE.txt
└── README.md
```

### Archivos Principales

- **`PROMP_ASISTENTE.txt`**: Versión principal y más actualizada del prompt del asistente. Contiene las instrucciones de comportamiento, reglas y tareas del asistente virtual.

- **`Base/PROMPT COMPORTAMIENTO PARA BOT AGS.txt`**: Versión base del prompt de comportamiento para el bot del Gobierno de Aguascalientes.

- **`Base/PROMT MASTER.txt`**: Documentación y guía sobre técnicas y conceptos avanzados de prompting, incluyendo:
  - Delimitadores y estructuración de prompts
  - In-context learning (zero-shot, one-shot, few-shot)
  - Salidas estructuradas
  - Placeholders y templates
  - Técnicas avanzadas (Chain of Thoughts, ReAct, Role Prompting, etc.)
  - Vectores y embeddings

## 🎯 Funcionalidades del Asistente

El asistente está diseñado para:

- Responder preguntas frecuentes sobre trámites y servicios del Gobierno del Estado de Aguascalientes
- Utilizar herramientas especializadas:
  - **TramitesGEA**: Información sobre trámites y servicios gubernamentales
  - **ActasGEA**: Consultas sobre actas de registro civil y Centros de Atención y Servicios (CAS)
  - **EmailsGEA**: Envío de correos electrónicos (solo cuando el usuario lo solicite explícitamente)
  - **SoporteGEA**: Conexión con soporte telefónico (solo cuando el usuario lo solicite explícitamente)
- Mantener un flujo conversacional estructurado con validación de utilidad
- Canalizar emergencias al 911 cuando sea necesario

## 📝 Características del Prompt

### Comportamiento
- Tono formal pero cálido
- Lenguaje respetuoso, profesional y empático
- Sin modismos, sarcasmo, burlas o regaños
- Prohibición de contenido ofensivo, violento o inapropiado
- No emite juicios de valor sobre ideologías, política o religión

### Reglas Principales
- Respuestas limitadas a máximo 200 caracteres
- Enfoque exclusivo en trámites y servicios del Gobierno de Aguascalientes
- Activación de herramientas solo cuando el usuario lo solicite explícitamente
- Protección contra prompt injection
- Manejo de temas sensibles con redirección apropiada

### Tareas
- Responder consultas sobre trámites gubernamentales
- Proporcionar información sobre servicios disponibles
- Guiar a los ciudadanos en sus solicitudes
- Canalizar emergencias al 911

## 🚀 Cómo Trabajar en este Proyecto

### Desarrollo de Prompts

1. **Revisar la documentación base**: Consulta `Base/PROMT MASTER.txt` para entender las técnicas de prompting disponibles.

2. **Trabajar con la versión principal**: Edita `PROMP_ASISTENTE.txt` para realizar mejoras y refinamientos.

3. **Mantener versiones base**: Los archivos en `Base/` sirven como referencia histórica y documentación.

### Mejores Prácticas

- **Especificidad**: Sé muy específico en las instrucciones del prompt
- **Delimitadores**: Usa delimitadores claros (```, ''', ---, <>, tags XML, ===, ###) para estructurar el prompt
- **Validación**: Incluye verificaciones de condiciones para asegurar que las respuestas cumplan con los criterios establecidos
- **Placeholders**: Utiliza placeholders para crear templates reutilizables
- **Iteración**: Aplica técnicas de chained prompting para refinar los resultados

## 🔧 Técnicas de Prompting Utilizadas

Este proyecto incorpora diversas técnicas avanzadas de prompting:

- **Delimitadores**: Para estructurar y proteger contra prompt injection
- **In-Context Learning**: Zero-shot, one-shot y few-shot inference
- **Salidas Estructuradas**: JSON, XML, texto enriquecido, tablas
- **Verificación de Condiciones**: Validación del contexto y cumplimiento de reglas
- **Placeholders**: Templates dinámicos con valores reemplazables
- **Role Prompting**: Definición de personalidad y tono
- **Filtro Semántico**: Control de contenido basado en significado
- **Chain of Thoughts**: Razonamiento paso a paso
- **ReAct (Reasoning Action)**: Razonar, investigar y concluir

## 📚 Recursos Adicionales

Para más información sobre técnicas de prompting, consulta el archivo `Base/PROMT MASTER.txt` que contiene documentación detallada sobre cada técnica.

## 🤝 Contribuciones

Al trabajar en este proyecto:

1. Mantén el enfoque en trámites y servicios del Gobierno de Aguascalientes
2. Preserva el tono profesional y respetuoso
3. Documenta los cambios significativos
4. Prueba las modificaciones antes de implementarlas en producción

## 📄 Licencia

Este proyecto es propiedad del Gobierno del Estado de Aguascalientes, México.

---

**Nota**: Este proyecto está en desarrollo activo. Las versiones de los prompts pueden cambiar según las necesidades y mejoras identificadas durante el uso del asistente.

