# 11 Decisiones Arquitectónicas — Jorge Antonio Rodríguez García

Cada caso: el reto, mi decisión, la alternativa descartada y el trade-off.

[← Volver al perfil principal](README.md)

---

### 1. Periscope — Pipeline ML con Dataset Sucio (2025)
**Reto:** Clasificar incidencias en ética deportiva (agresiones, bullying, discriminación). Dataset con etiquetas inconsistentes y categorías desbalanceadas.
**Decisión:** Pipeline iterativo por sprints: primero limpiar el dataset, luego reentrenar. No tiene sentido optimizar hiperparámetros sobre datos sucios.
**Descartado:** Entrenar modelos más potentes sobre el dataset original. Más compute, mismos errores sistémicos.
**Trade-off:** Más tiempo en limpieza manual, pero Macro-F1 de 0.35 a 0.41 (+17%) solo con la primera fase. El modelo es tan bueno como los datos.

### 2. Framework Agéntico — Gobernanza de Agentes IA (2024)
**Reto:** La IA genera código rápido pero impredecible. ¿Cómo escalar agentes IA sin perder control arquitectónico?
**Decisión:** Máquina de estados con planificador gobernado. Los agentes siguen un plan canónico compilado desde especificaciones (BDD, OpenAPI) con origin tracking. Cada paso auditable.
**Descartado:** Agentes con prompts ad-hoc y revisión manual. Funciona solo; ingobernable en equipo.
**Trade-off:** Más estructura inicial (compilar plan antes de ejecutar), pero trazabilidad completa. Si un agente falla, rastreas qué especificación lo causó.

### 3. Hub Productividad IA — Integración Empresarial con MCP (2024)
**Reto:** Gestionar tareas, reportes y comunicaciones integrando Jira, Gmail, Slack sin depender de cada API específica.
**Decisión:** PWA con proxy IA y servidor MCP que abstrae las integraciones. Los agentes controlan herramientas a través del protocolo MCP, no de APIs directas.
**Descartado:** Integración directa API-a-API. Cada cambio en una herramienta rompe la integración.
**Trade-off:** Más capas de abstracción, pero desacoplamiento total: añadir una herramienta nueva no requiere tocar las existentes.

### 4. NIMROD — Plataforma IoT para Dominios Distintos (2017–2026)
**Reto:** Monitorización y alertas que sirva igual para centros de salud (agresiones), transporte ferroviario (meteorología) y mutuas (SOS laboral). Dominios diferentes, misma necesidad.
**Decisión:** DDD puro: cada despliegue tiene su Bounded Context con reglas específicas, pero comparte infraestructura de alertas y motor de reglas dinámico. CQRS para separar ingesta de consulta.
**Descartado:** Monolito parametrizable. Más rápido inicialmente, pero cada dominio contamina el modelo de los anteriores.
**Trade-off:** Más esfuerzo en el core abstracto, pero 5 organizaciones en producción independientes. Nuevos clientes en semanas, no meses.

### 5. Conforcat — IA en Producción bajo Presión Extrema (2024)
**Reto:** Entregar plataforma de formación autonómica con retraso acumulado y presión de tiempo extrema.
**Decisión:** Adopción masiva de IA generativa en todo el ciclo (código, tests, refactor, documentación). Integración asíncrona con RabbitMQ para desacoplar APIs lentas. Chatbot RAG para soporte.
**Descartado:** Más personas (desarrollo convencional). El cuello de botella no era fuerza bruta sino time-to-market.
**Trade-off:** Riesgo de deuda técnica por velocidad IA, mitigado con pipeline de auditoría arquitectónica. Resultado: ×5 TTM sin degradación.

### 6. DIBA — Visión por Computador para Boletines Históricos (2023)
**Reto:** Digitalizar ~60.000 boletines (1833-1997). OCR de baja calidad, Google Vision fallaba en maquetaciones multi-columna.
**Decisión:** Usar el OCR para obtener coordenadas de caracteres, no para leer texto. Dibujar bloques en posiciones detectadas y aplicar histogramas sobre la imagen sintética.
**Descartado:** Mejorar OCR o post-procesar con NLP. Asumían texto recuperable — no lo era.
**Trade-off:** Doble pasada de OCR (más lento), pero precisión muy superior. El cuello de botella era calidad, no velocidad.

### 7. Expedion — Metaprogramación para Expedientes (2023)
**Reto:** Cada expediente administrativo se construía a medida, requiriendo meses. ¿Cómo permite a no-técnicos construir programas completos?
**Decisión:** Motor de metadatos: cabeceras, formularios dinámicos, flujos de trabajo, generación de documentos desde plantillas. Arquitectura Hexagonal para aislar core.
**Descartado:** Generador de código estático. Más rápido pero imposible de mantener: cada cambio requiere regenerar todo.
**Trade-off:** Inversión alta en motor de metadatos, pero meses → semanas. Otros equipos construyen sin mi intervención.

### 8. NIMROD Alertas — Motor de Reglas Reutilizable (2022)
**Reto:** Motor de alertas que procese eventos heterogéneos y notifique por múltiples canales sin acoplar la lógica de cada canal al core.
**Decisión:** Motor de reglas dinámico con umbrales configurables + CQRS para separar ingesta de evaluación. Canales (VoIP, SMS) como puertos de Arquitectura Hexagonal.
**Descartado:** Switch/case por tipo de alerta y canal. Funcionaba con 2 canales, ingobernable con 5+.
**Trade-off:** Más abstracción en el diseño, pero añadir un canal es implementar un adaptador, no tocar el core.

### 9. The Switchers — Meta-aplicación Multilingüe LTR/RTL (2019)
**Reto:** Generar toolboxes interactivos para programa de emprendimiento mediterráneo con idiomas RTL (árabe, hebreo) y LTR.
**Decisión:** Meta-aplicación que genera toolboxes desde configuración por país/idioma. Motor de plantillas con soporte bidireccional nativo.
**Descartado:** Crear toolbox manualmente por país. Inviable con 10+ países y 2 direcciones de texto.
**Trade-off:** Motor de generación más complejo, pero cada país nuevo se configura en horas, no semanas.

### 10. ERP SERIDA — Sistema que Sobrevive 15+ Años (2002–2017)
**Reto:** Unificar inventario, incidencias, facturación y RRHH con motor contable de análisis jerárquico ilimitado para organismo público de I+D.
**Decisión:** Árboles recursivos (Nested Sets) para centros de coste y conceptos de gasto con bloqueo transaccional presupuestario. Comunicación automática entre módulos con integridad referencial absoluta.
**Descartado:** Contabilidad plana sin jerarquía. Más simple pero sin capacidad analítica por centro de coste.
**Trade-off:** Modelo de datos más complejo, pero 15+ años en producción sin reescrituras. La inversión en diseño compensa.

### 11. RAD Framework — Metaprogramación desde el PFC (2012–2020)
**Reto:** ¿Cómo generar una aplicación web completa desde un fichero de definición, sin código manual?
**Decisión:** Motor MVC que interpreta ficheros de definición y genera CRUDs, formularios, validaciones, listados y exportación. Metaprogramación pura.
**Descartado:** Scaffolding (generador de código estático). Genera código pero actualizar el generador rompe lo generado.
**Trade-off:** Motor interpretado más lento que código nativo, pero evolucionable: actualizar el motor mejora todas las aplicaciones. Explotado comercialmente 8+ años.

