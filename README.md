# Jorge Antonio Rodríguez García

### Ingeniero de Software Senior · Arquitecto de Soluciones Symfony · DevOps ·IA aplicada al desarrollo · 25 años liderando proyectos complejos
**Oviedo, Asturias · 686 61 70 71 · jorge@rodriguez-garcia.es**

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/jorge-antonio-rodríguez-garcía-740a7b55)
&nbsp;
[<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:jorge@rodriguez-garcia.es)

---


## 🧭 Resumen Profesional

Ingeniero de Software y Licenciado en ADE con 25 años de experiencia liderando el ciclo de vida completo de soluciones tecnológicas para el sector público. Mi doble perfil técnico y de negocio me permite transformar requisitos funcionales complejos en arquitecturas robustas y escalables. Soy experto en modernizar sistemas, optimizar procesos y guiar equipos remotos hacia la excelencia técnica y la entrega continua de valor.

- **Liderazgo Técnico:** Experiencia demostrada en la dirección de más de 50 proyectos de tamaño medio y grande (hasta 200.000 €), gestionando equipos y definiendo arquitecturas de software para ministerios, comunidades autónomas y ayuntamientos.
- **Arquitectura y Calidad de Software:** Especializado en el diseño de arquitecturas limpias y escalables aplicando principios SOLID, TDD, DDD y CQRS. Fomento prácticas de Extreme Programming y Pair Programming para garantizar la calidad del código y la mentoría del equipo.
- **Innovación con IA:** Desde 2023, integro activamente herramientas de IA (Cursor, Claude) en el flujo de desarrollo para mejorar la productividad y la calidad del software. Desarrollo soluciones inteligentes para clasificación automática, extracción de datos y generación de contenido.
- **Visión de Negocio:** Mi formación en Administración y Dirección de Empresas me proporciona una perspectiva estratégica para alinear las soluciones técnicas con los objetivos de negocio y la normativa de la administración pública.
- **Visión 360° (Desarrollo y Operaciones):** Combino el liderazgo en el desarrollo de software con la administración experta de la infraestructura subyacente. Mi experiencia abarca desde el diseño de arquitecturas de software hasta el despliegue y mantenimiento de los servidores (Linux, correo, web), redes y sistemas de virtualización que las soportan, aplicando una mentalidad DevOps para garantizar soluciones robustas y de alto rendimiento.
---

## 🛠️ Competencias Técnicas

- **Lenguajes**: PHP, Python, SQL  
- **Frameworks y Tecnologías**: Symfony, Doctrine, API REST, Twig  
- **Arquitectura y Metodologías**: DDD, CQRS, TDD, Clean Architecture, SOLID, Ágiles (XP, Scrum), Pair Programming, DevOps  
- **Bases de Datos**: MySQL/MariaDB, Oracle, PostgreSQL  
- **IA y Machine Learning**: Desarrollo asistido por IA (Cursor, Claude), Modelos de clasificación, Extracción de datos  
- **DevOps y Administración de Sistemas**: Administración de Servidores Linux, Zimbra, Samba, VMWare, XenCenter, Apache, etc.

---

## 💼 Experiencia Profesional

### **TEAM LEADER y PROGRAMADOR SENIOR – Prometeo Innovations**
**2017 – Actualidad · Oviedo / Remoto**

Responsable del diseño y liderazgo técnico de soluciones digitales para la Administración Pública, cumpliendo normativas como la Ley 39/2015 y el ENS. He impulsado la adopción de arquitecturas modernas (DDD, hexagonal, CQRS), el uso de inteligencia artificial para clasificación de datos, y herramientas propias para acelerar el desarrollo.

**Ámbitos clave:** Symfony, IA aplicada a OCR y clasificación, metaprogramación, automatización de trámites, plataformas educativas, APIs REST, RabbitMQ, integración con sistemas públicos (Cl@ve, Firma Digital).

🔽 *Ver proyectos destacados en la sección de portfolio.*

---

### **JEFE DE PROYECTOS Y PROGRAMADOR SENIOR – Eurolynx**
**2002 – 2017 · Asturias**

Lideré el desarrollo y mantenimiento de un ERP para un organismo público de I+D, abarcando contabilidad, RRHH, inventario y presupuestos. Además, gestioné la infraestructura crítica: correo (Zimbra), archivos, virtualización (Xen, VMWare), redes y backups.

**Ámbitos clave:** PHP nativo, sistemas Linux, Oracle, virtualización, integración de servicios internos, soporte a usuarios.

---

### **PROGRAMADOR SENIOR – Autónomo**
**1999 – 2002 · Asturias**

Desarrollé soluciones web y backends para instituciones públicas como el Servicio Regional de Investigación, adaptándome a requerimientos técnicos diversos y entornos con recursos limitados.

**Ámbitos clave:** Desarrollo web a medida, PHP, bases de datos, despliegue de portales públicos.


---

## 🎓 Educación

- **Ingeniería Técnica en Informática de Gestión**  
  *Universidad de Oviedo (2009–2012)*

- **Licenciatura en Administración y Dirección de Empresas**  
  *Universidad de Oviedo (2006–2010)*

---

## 📁 Portfolio de Proyectos

---

# Expedion – Generador de Procedimientos Administrativos (2023)

### _Plataforma de metaprogramación en Symfony y Arquitectura Hexagonal para la creación visual de sistemas completos de gestión de expedientes._

**Nota:** El código fuente de esta plataforma es un activo estratégico y no puede ser publicado. Este repositorio sirve como un caso de estudio detallado sobre su arquitectura y mi rol en el proyecto.

---

### 🎯 El Reto

El desarrollo de software de gestión de expedientes para la Administración Pública es tradicionalmente un proceso a medida, lento y repetitivo. Cada cliente y cada ley requieren una solución específica. El reto fundamental era doble:

1.  **Dejar de construir expedientes uno a uno.** Necesitábamos una forma de industrializar y acelerar drásticamente la creación y despliegue de estas soluciones.
2.  **Resolver el problema de la metaprogramación.** ¿Cómo se diseña y construye un programa cuya única función es permitir a otros usuarios, sin conocimientos técnicos, construir programas funcionales y completos? El desafío era crear las estructuras de metadatos y las interfaces capaces de representar la lógica de otro software.

### 🛠️ La Solución y mi Rol como Arquitecto

Como **Arquitecto de Software**, diseñé y desarrollé el motor principal de **Expedion**, una plataforma que permite la construcción de sistemas de expedientes desde una interfaz de configuración. La solución se basó en los siguientes pilares:

* **Arquitectura Hexagonal (Puertos y Adaptadores):** Utilicé Symfony como un detalle de implementación dentro de una arquitectura hexagonal. Esto aisló por completo la lógica de negocio (el "core" de la definición de expedientes) de la infraestructura (framework, base de datos, etc.), garantizando la mantenibilidad y escalabilidad a largo plazo.

* **Motor de Metadatos:** El corazón de Expedion es un sofisticado sistema de metadatos que permite definir:
    * La **estructura de la cabecera** de un expediente.
    * **Formularios dinámicos** para cada trámite, con sus campos y validaciones.
    * **Procesos y flujos de trabajo** que dictan el comportamiento del expediente.
    * La conexión entre los datos de los formularios y **plantillas de documentos (.DOT)** para la generación automática de oficios, resoluciones y notificaciones.

### 💡 Stack Tecnológico y de Arquitectura

* **Backend:** Symfony, PHP
* **Arquitectura:** Arquitectura Hexagonal, Domain-Driven Design (DDD)
* **Conceptos Clave:** Metaprogramación, Diseño de Metadatos, Generación Dinámica de Formularios, Generación de Documentos (a partir de plantillas .DOT).

### ✅ Resultados y Evolución del Rol

El éxito de la plataforma transformó mi función y el modelo de negocio:

* **Producto Core Creado:** Se finalizó con éxito el desarrollo de la herramienta base "Expedion", convirtiéndose en un activo estratégico de la compañía.
* **Industrialización del Desarrollo:** Se pasó de proyectos a medida de meses de duración a la generación de soluciones completas en cuestión de semanas o incluso días.
* **Evolución a Líder Técnico:** Mi rol evolucionó desde ser el arquitecto y desarrollador principal de la herramienta a **coordinar a otros equipos técnicos** que la utilizaban para construir y entregar las soluciones finales a los clientes, asegurando la calidad y el correcto uso de la plataforma que había diseñado.
---
# DIBA – Procesamiento de Boletines Oficiales Históricos (1833-1997)

### _Pipeline de Visión por Computador e IA en Python y Symfony para la extracción y clasificación de datos de ~60.000 boletines históricos._

**Nota:** El código y los modelos generados para este proyecto son propiedad del cliente. Este repositorio sirve como un caso de estudio sobre la arquitectura del sistema y las soluciones técnicas implementadas.

---

### 🎯 El Reto

El Boletín Oficial de la Provincia de Barcelona poseía un archivo histórico masivo, con cerca de 60.000 boletines que abarcaban más de 160 años. El objetivo era transformar este corpus de documentos en una base de datos estructurada, separando cada boletín en sus anuncios individuales y clasificándolos. El reto técnico era inmenso y se dividía en dos problemas principales:

1.  **Datos Pre-digitalizados de Baja Calidad:** Una gran parte de los boletines ya había sido procesada con Tesseract OCR por un tercero, pero el resultado era de muy mala calidad y multilingüe. El texto estaba tan degradado que las técnicas estándar de Procesamiento de Lenguaje Natural (NLP), como el Reconocimiento de Entidades (NER), eran completamente ineficaces.
2.  **Análisis de Maquetación Compleja:** Los boletines más antiguos, que se entregaron como simples escaneos, presentaban maquetaciones complejas de varias columnas. Herramientas potentes como la API de **Google Vision** fallaban al no poder interpretar correctamente el flujo de lectura del texto, mezclando columnas y haciendo el texto inutilizable.

### 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto y desarrollador principal, diseñé y construí un pipeline de procesamiento completo que combinaba **Python** para la visión y el pre-procesamiento, y **Symfony** para la lógica de negocio y clasificación. La solución se articuló en tres fases clave:

#### Fase 1: Visión por Computador para el Análisis de Maquetación (Python)
Para resolver el problema de la detección de columnas donde Google Vision fallaba, inventé un método no convencional:
* Primero, se realizaba un OCR preliminar no para leer el texto, sino únicamente para obtener las **coordenadas de cada carácter** en la página.
* A continuación, se generaba una imagen en blanco y se **dibujaba un cuadro negro** en la posición de cada carácter detectado.
* Sobre esta nueva imagen de "bloques de texto", se aplicaba un **análisis de histogramas**. Este enfoque ofrecía umbrales mucho más claros y fiables para detectar los espacios en blanco y, por tanto, **separar las columnas a la perfección** de forma automática.
* Una vez ordenado el flujo textual, se pasaba a un OCR de alta calidad.

#### Fase 2: Reparación de OCR y Extracción (Python)
Para tratar con el texto de baja calidad, desarrollé un conjunto de herramientas a medida en Python, ya que las librerías estándar no eran suficientes:
* Implementé **expresiones regulares muy avanzadas** para la detección de patrones de anunciantes y tipos de anuncios.
* Desarrollé funciones personalizadas para la **comparación y reparación de strings**, capaces de corregir errores comunes de OCR y calcular porcentajes de similitud, portando lógicas más avanzadas que no existen de forma nativa en otros lenguajes.

#### Fase 3: Segmentación y Clasificación Flexible (Symfony + CQRS)
Una vez que teníamos un texto limpio y ordenado, el proceso final de división en anuncios y clasificación se gestionó con una aplicación en Symfony:
* Se diseñó con una **arquitectura CQRS** (Command and Query Responsibility Segregation).
* Este patrón permitió crear un sistema muy limpio y abierto donde, en función de ciertos parámetros del boletín (año, formato detectado), se podía **seleccionar dinámicamente el algoritmo o la estrategia de detección específica** a utilizar. Esta flexibilidad fue crucial, ya que no había dos boletines exactamente iguales.

### 💡 Stack Tecnológico

* **Lenguajes:** **Python**, PHP
* **Visión por Computador y OCR:** Python, **Google Vision API**, OpenCV (para histogramas y manipulación de imágenes)
* **Procesamiento de Datos:** Motores de Expresiones Regulares, Algoritmos de Similitud de Strings
* **Framework Backend:** **Symfony**
* **Arquitectura de Software:** **CQRS**

### ✅ Resultados

* Se procesó con éxito el archivo completo de ~60.000 boletines, transformando un archivo histórico inaccesible en un recurso digital estructurado y consultable.
* Se desarrolló una solución innovadora de visión por computador que superó las limitaciones de las herramientas comerciales estándar para el análisis de maquetación.
* El uso de CQRS en Symfony demostró ser una estrategia altamente eficaz para gestionar la complejidad y variabilidad de las reglas de negocio en un pipeline de procesamiento de datos.
---

# Baix Empordà – Modernización Híbrida de Sistema Legacy (2021)

### _Estrategia de coexistencia para un sistema de los años 90, ejecutando código PHP nativo dentro de una aplicación Symfony moderna para permitir su ampliación y corrección._

**Nota:** El código fuente de este proyecto es propiedad del Consell Comarcal del Baix Empordà. Este repositorio sirve como un caso de estudio sobre la arquitectura de modernización implementada.

---

### 🎯 El Reto

El cliente, el Consell Comarcal del Baix Empordà, necesitaba ampliar y corregir errores críticos en su sistema principal de gestión, una aplicación de grandes dimensiones desarrollada en los años 90. El reto era mayúsculo por varias razones:

1.  **Restricción Contractual:** El pliego de prescripciones técnicas del concurso público definía el proyecto explícitamente como una **ampliación**, no como un desarrollo nuevo. A pesar de que el código se encontraba en muy mal estado, una reescritura completa quedaba descartada por limitaciones presupuestarias.
2.  **Riesgo Técnico:** El código legacy era frágil. Cualquier modificación directa corría el riesgo de introducir nuevos errores en cascada.
3.  **Modelo de Datos Intocable:** Para minimizar el riesgo, se debía preservar el modelo de datos existente, sin modificar las tablas, relaciones o cardinalidades originales de la base de datos.

El desafío era: ¿Cómo se puede construir sobre cimientos tan antiguos y frágiles, añadiendo funcionalidades modernas como APIs y corrigiendo fallos de seguridad, sin demoler la estructura existente?

### 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto del proyecto, propuse y lideré la implementación de una **arquitectura híbrida de coexistencia**, inspirada en un *paper* técnico sobre modernización de software. La estrategia consistió en hacer que el código legacy pasara a ser gestionado desde dentro de una aplicación **Symfony** nueva.

La solución se implementó de la siguiente manera:

* **Symfony como "Host" o "Wrapper":** Modifiqué el comportamiento del kernel de Symfony para que, en lugar de manejar solo sus propias rutas, pudiera "envolver" y ejecutar los scripts del código PHP legacy. El sistema antiguo se ejecutaba dentro del contexto de la aplicación moderna.
* **Servicios Centralizados con el Contenedor de Dependencias:** El mayor beneficio de este enfoque fue poder ofrecer servicios modernos al código antiguo. Funcionalidades críticas como la **autenticación y la autorización de usuarios** se desarrollaron como servicios de Symfony. El código legacy fue refactorizado mínimamente para consumir estos servicios a través del **Contenedor de Dependencias de Symfony**, centralizando la seguridad y eliminando las vulnerabilidades del sistema antiguo.
* **Estrategia de "Microportales":** De cara al usuario, se unificó la apariencia visual de las páginas legacy y las nuevas para que la experiencia fuera totalmente transparente, como si se tratara de una única aplicación.
* **Nuevas Funcionalidades en Symfony:** Todo el nuevo desarrollo, incluyendo un conjunto de **APIs REST** para una nueva aplicación móvil de control de transporte, se construyó de forma nativa en Symfony, utilizando componentes de **Sonata** para las interfaces de administración.
* **Ampliación Aditiva de la Base de Datos:** Se respetó la regla de no modificar el esquema original. Todas las nuevas estructuras de datos se implementaron en tablas nuevas, conviviendo con las antiguas sin alterar sus relaciones.

### 💡 Stack Tecnológico

* **Backend:** **PHP**, **Symfony**, **Sonata Admin Bundle**
* **Base de Datos:** **MySQL**
* **Arquitectura:** **Arquitectura Híbrida (Legacy-in-Symfony)**, Microportales
* **Conceptos Clave:** Inyección de Dependencias en código Legacy, Refactorización de "Wrapper", API REST

### ✅ Resultados y Valor Estratégico

* **Cumplimiento del Contrato sin Sacrificar Calidad:** Se cumplieron las estrictas limitaciones del pliego público, entregando una solución robusta y moderna en lugar de simplemente "parchear" el código antiguo.
* **Extensión de la Vida Útil del Legacy:** El sistema crítico del cliente pudo seguir funcionando, pero ahora con errores corregidos, mayor seguridad y nuevas capacidades.
* **Ruta de Migración Progresiva:** Este enfoque híbrido sentó las bases para una migración futura. El cliente ahora puede reemplazar módulos legacy uno por uno, de forma paulatina y controlada, dentro del mismo framework de Symfony.
* **Reducción de Riesgo y Coste:** Se evitó el enorme coste y el alto riesgo asociados a un proyecto de reingeniería completo ("big bang rewrite").
---
# Librería de Autogeneración de API REST para Symfony (2020)

### _Proyecto personal de I+D desarrollado en Prometeo para generar automáticamente interfaces API REST a partir de entidades de Doctrine, que fue adoptado y explotado comercialmente en múltiples proyectos._

---

### 🎯 El Reto

Dentro de la empresa, existía una necesidad recurrente: la mayoría de los proyectos debían exponer sus datos a través de APIs para ser consumidos por una empresa de movilidad del mismo grupo. El enfoque histórico tenía dos problemas fundamentales:

1.  **Cuello de Botella:** Se creaban APIs a medida para cada proyecto, muy acopladas a la vista y a las necesidades puntuales. Esto generaba una fuerte dependencia del equipo de movilidad con el equipo backend, retrasando los desarrollos.
2.  **Coste de Desarrollo:** Dedicar horas a desarrollar, documentar y mantener estas APIs a medida en cada proyecto era costoso y repetitivo.

El reto era: ¿Podemos crear una solución única que genere una API rica, flexible y estandarizada para cualquier entidad de Doctrine con un esfuerzo de implementación cercano a cero?

### 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto y desarrollador, diseñé y construí una librería interna para Symfony que resolvía este problema de raíz. La librería inspecciona las anotaciones de las entidades de Doctrine y, haciendo un uso avanzado del componente **Serializer de Symfony**, genera automáticamente una interfaz API REST completa.

Las características clave de la librería son:

* **Generación Automática de CRUD:** Proporciona de serie los endpoints para las operaciones `GET`, `POST`, `PUT` y `DELETE` para cualquier entidad, sin necesidad de escribir código de controlador.
* **`GET` Supervitaminado:** El endpoint `GET` fue potenciado para dar autonomía a los desarrolladores frontend/móvil:
    * **Filtros Avanzados:** Permite filtrar por cualquier campo con múltiples operadores (`eq`, `ne`, `gt`, `lt`, etc.).
    * **Grupos de Serialización Dinámicos:** El consumidor de la API puede especificar qué grupos de datos quiere recibir, permitiendo ampliar los resultados con entidades relacionadas bajo demanda.
    * **Parámetros de Caché y Compresión:** Incluye flags para optimizar el rendimiento de las peticiones.
* **Operaciones Anidadas en `POST` y `PUT`:** Permite crear o actualizar entidades relacionadas en la misma petición, simplificando enormemente las interacciones desde el cliente.
* **Arquitectura Extensible con Patrón "Template Method":** Para evitar la rigidez, diseñé la librería usando el patrón *Template Method*. La clase principal contiene métodos vacíos en puntos clave del proceso (ej. `prePersist`, `postFlush`). Un desarrollador puede extender la clase y sobrescribir estos métodos para añadir lógica de negocio personalizada (enviar un email, registrar un log, etc.) sin tener que modificar ni una línea del código de la librería, garantizando la mantenibilidad.

### 💡 Stack Tecnológico

* **Lenguaje y Framework:** **PHP**, **Symfony**
* **Componentes Clave:** **Doctrine ORM**, **Symfony Serializer Component**, Introspección de PHP (Reflection)
* **Patrones de Diseño:** **Template Method**
* **Conceptos:** API REST, Generación de código, Serialización Avanzada

### ✅ Resultados e Impacto

* **Reducción Drástica de Costes:** La librería fue utilizada con éxito en numerosas aplicaciones, reduciendo los costes y tiempos de implementación de las APIs de manera generalizada en toda la empresa.
* **Desacoplamiento y Agilidad:** Eliminó el cuello de botella entre los equipos de backend y movilidad, permitiendo que trabajaran en paralelo y que el equipo de movilidad fuera mucho más autónomo.
* **Producto Interno Estratégico:** La librería se convirtió en un acelerador de desarrollo estándar para los nuevos proyectos.
* **Desafío Técnico Superado:** El mayor reto fue la necesidad de comprender en profundidad el funcionamiento interno del componente Serializer de Symfony para manejar casos complejos como las referencias circulares y la serialización de entidades relacionadas, lo cual fue un gran aprendizaje técnico.
---
# O.A.R. Badajoz – Arquitectura de Integración para Sede Electrónica (2022)

### _Rol de arquitecto especialista para resolver los retos de Firma Digital, Cl@ve y procesamiento de formularios complejos dentro de un proyecto Drupal, implementando una capa de abstracción de servicios en PHP._

**Nota:** Este proyecto fue una colaboración donde mi rol no fue el de desarrollador Drupal, sino el de arquitecto especialista en PHP/Symfony, encargado de diseñar e implementar las soluciones a los problemas técnicos más complejos que la plataforma base no podía resolver.

---

### 🎯 El Reto

El proyecto principal era la construcción de una Sede Electrónica para el Organismo de Recaudación (O.A.R.) de Badajoz sobre la plataforma **Drupal**. Sin embargo, el equipo de desarrollo se encontró con varios obstáculos críticos donde las capacidades nativas de Drupal eran insuficientes para cumplir con los exigentes requisitos de la administración pública española. Fui asignado al proyecto para:

1.  **Integrar Sistemas de Identidad y Firma del Estado:** Drupal no disponía de soluciones robustas y fiables para la integración del sistema de autenticación **Cl@ve** ni para los flujos de **Firma Digital** con certificados de la FNMT, incluyendo la resolución de problemas técnicos con el DNI electrónico.
2.  **Gestionar Formularios Dinámicos y Complejos:** El cliente requería que los **Webforms** de Drupal tuvieran comportamientos avanzados: pre-llenado de datos desde servicios externos, procesamiento post-envío, previsualización y firma. Ciertos formularios, además, debían ser semi-automáticos.
3.  **Conectar con un Ecosistema de Datos Heterogéneo:** La Sede debía comunicarse con múltiples sistemas de la Diputación para obtener datos fiscales o registrar documentos. Estos sistemas eran muy variados: bases de datos **Oracle**, servicios **SOAP** y **APIs REST**. Se necesitaba una forma de integrar estos datos sin acoplar fuertemente el código de Drupal a cada tecnología.

### 🛠️ La Solución y mi Rol como Arquitecto Especialista

Mi trabajo consistió en diseñar e implementar una serie de "soluciones quirúrgicas" que se integraban con Drupal, pero que se basaban en principios de software más robustos y agnósticos a la plataforma.

#### 1. Módulo de Autenticación y Firma
* **Cl@ve:** Desarrollé un módulo para Drupal, pero extraje toda la lógica de negocio a una **librería orientada a objetos independiente** que mejoraba el código original de la administración pública. Esto no solo resolvió el problema, sino que creó un componente reutilizable para futuros proyectos.
* **Firma Digital:** Orquesté la instalación y configuración de un **servidor Tomcat** dedicado para el procesamiento de firmas y lo integré de forma transparente con Drupal.
* **Certificados DNIe:** Diagnostiqué y solucioné los problemas de validación de certificados de DNI electrónico directamente en la configuración del servidor **Apache**.

#### 2. Sistema de "Handlers" para Webforms
Para dar respuesta a la complejidad de los formularios, intervine el **sistema de hooks de Drupal** para crear una arquitectura de manejadores (handlers) más flexible y potente:
* Desarrollé un sistema que permitía registrar servicios "handler" para los formularios. Cada handler tenía un método `supports()` que determinaba si debía ejecutarse para un formulario concreto.
* Creé manejadores de tipo `pre-form` para conectarse a servicios externos y rellenar los campos del formulario antes de que el usuario lo viera.
* Creé manejadores `post-form` para procesar los datos tras el envío, conectarse al sistema de Registro de Entrada, generar justificantes de presentación (PEDOAR), etc.

#### 3. Capa de Abstracción de Datos
Para independizar a los desarrolladores Drupal de la complejidad de los sistemas externos, diseñé una **capa de abstracción**:
* Creé un conjunto de servicios simples en PHP. Por ejemplo, `ServicioFiscal::getDatos(nif)` o `Registro::registrar(documento)`.
* Estos servicios eran los únicos que el equipo de Drupal necesitaba usar. Internamente, mis servicios se encargaban de saber si tenían que atacar a un API REST, a una base de datos Oracle o a un servicio SOAP.
* **Prueba de Éxito:** Durante el proyecto, un sistema backend migró de Oracle a una API REST. Gracias a la capa de abstracción, **el código de Drupal no requirió ni una sola modificación**.

### 💡 Stack Tecnológico y de Integración

* **Plataforma Base:** **Drupal**, **PHP**
* **Integraciones Clave:** **Cl@ve** (con librería OO propia), **Firma Digital** (con servidor **Tomcat**), Certificados FNMT
* **Servidores:** **Apache**
* **Principios de Arquitectura:** **Capa de Abstracción (Abstraction Layer)**, Patrón Strategy/Handler sobre el sistema de Hooks de Drupal
* **Sistemas Externos:** SOAP, Oracle, REST APIs

### ✅ Resultados

* Se desbloqueó el proyecto principal, permitiendo que la plataforma Drupal cumpliera con todos los requisitos técnicos del cliente.
* La capa de abstracción protegió la inversión en desarrollo, haciendo la aplicación resiliente a cambios futuros en la infraestructura de sistemas de la Diputación.
* Se crearon componentes reutilizables (como la librería Cl@ve) que pudieron ser aprovechados en otros proyectos, optimizando costes futuros.
* Demostré la capacidad de aportar soluciones de alta arquitectura en entornos tecnológicos diversos, actuando como un especialista que resuelve los problemas de mayor complejidad.

---
# Conforcat – Plataforma de Gestión de Formación Continua (2024)

### _Arquitectura de una plataforma a gran escala en Symfony y DDD, entregada en un tiempo récord gracias a la adopción masiva de IA en el desarrollo y a un sistema de integración asíncrono con RabbitMQ._

---

### 🎯 El Reto

El Consorci per a la Formació Contínua de Catalunya (Conforcat) necesitaba una nueva plataforma integral para gestionar toda su oferta formativa. El proyecto presentaba una triple dificultad:

1.  **Plazo de Entrega Extremadamente Agresivo:** Debido a la carga de trabajo previa, el proyecto comenzó muy tarde. Se requería entregar una solución grande y compleja en una fracción del tiempo habitual.
2.  **Complejidad Funcional y de Roles:** La plataforma debía dar servicio a un ecosistema de usuarios muy diverso: participantes, formadores, empresas que gestionan la formación de sus empleados y el propio personal del consorcio. Esto implicaba gestionar cursos, convocatorias, inscripciones y expedientes con lógicas de negocio complejas.
3.  **Integración con Sistemas Múltiples:** La solución debía consumir datos de una API REST principal, pero también interactuar con un sistema legacy interno y con otros servicios preconstruidos de la empresa (calendario, chat, etc.).

### 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto y líder técnico, mi estrategia para superar estos retos se centró en la innovación tanto en la arquitectura de software como en la propia metodología de desarrollo.

#### 1. Desarrollo Acelerado por Inteligencia Artificial
Para cumplir con el plazo imposible, lideré la **adopción masiva y sistemática de agentes de IA** en el flujo de trabajo del equipo. Esta estrategia de "desarrollo aumentado por IA" fue clave para:
* Acelerar la generación de código, tests y documentación.
* Optimizar algoritmos y refactorizar código de manera mucho más eficiente.
* **Resultado:** Multiplicamos nuestra velocidad de desarrollo por un factor estimado de 3x a 5x, lo que nos permitió llegar a tiempo a la entrega.

#### 2. Arquitectura Asíncrona con RabbitMQ
La integración con "Hermes", un sistema de comunicación interno de la empresa que gestiona usuarios y propietarios de contenido, históricamente se realizaba mediante llamadas API síncronas. Para este proyecto, diseñé una solución más moderna y resiliente:
* Se implementó un **sistema asíncrono basado en eventos**, utilizando una cola de mensajes **RabbitMQ**.
* Dentro de Conforcat, creé una **capa de abstracción de repositorios** que hacía que esta comunicación en segundo plano fuera totalmente transparente para el resto de la aplicación, que seguía operando con normalidad sin notar la asincronía.

#### 3. Chatbot Inteligente con RAG
Para mejorar el soporte a los usuarios, se implementó un chatbot de ayuda. En lugar de un sistema simple basado en reglas, desarrollé un **sistema RAG (Retrieval-Augmented Generation)**, que permite al chatbot consultar una base de conocimiento para dar respuestas mucho más precisas y contextualizadas.

#### 4. Núcleo Robusto con DDD y Symfony
Toda la plataforma se construyó sobre una base sólida de **Symfony** y los principios de **Domain-Driven Design (DDD)**. Esta elección fue fundamental para modelar correctamente la alta complejidad del negocio y mantener el código organizado y escalable.

### 💡 Stack Tecnológico

* **Backend:** **Symfony**, PHP
* **Arquitectura:** **Domain-Driven Design (DDD)**, Arquitectura Orientada a Eventos
* **Mensajería y Asincronía:** **RabbitMQ**
* **Inteligencia Artificial:** **RAG (Retrieval-Augmented Generation)** para Chatbot, Desarrollo asistido por Agentes de IA
* **Integraciones:** REST APIs, Sistemas Legacy

### ✅ Resultados e Impacto

* **Entrega Exitosa Bajo Presión Extrema:** Se entregó un proyecto de gran envergadura en un plazo extraordinariamente corto, demostrando que con las herramientas y metodologías adecuadas se pueden superar las limitaciones de tiempo tradicionales.
* **Transformación del Proceso de Desarrollo:** El proyecto sirvió como catalizador para la adopción de la IA como una herramienta fundamental en el ciclo de desarrollo de la empresa, estableciendo un nuevo estándar de productividad.
* **Modernización de la Arquitectura de Integración:** Se migró una integración crítica de un modelo síncrono frágil a uno asíncrono, escalable y resiliente, mejorando la robustez general del ecosistema de aplicaciones.
* **Implementación de IA de Vanguardia:** La creación del chatbot con RAG demostró la capacidad de aplicar técnicas de IA modernas para mejorar directamente la experiencia del usuario final.
---
# Intranet de Valladolid – Arquitectura Hexagonal sobre API REST (2021)

### _Diseño de una arquitectura de persistencia sin Doctrine, basada en una API REST externa y un sistema de caché multi-capa para solucionar problemas críticos de rendimiento._

---

### 🎯 El Reto

El objetivo era desarrollar una nueva intranet para el Ayuntamiento de Valladolid, con un frontend de noticias y un área privada para empleados (mensajería, nóminas, formularios, etc.). El proyecto presentaba tres desafíos fundamentales:

1.  **Dependencia de un Sistema Externo:** El requisito principal era que la intranet debía ser una nueva "cara" para un sistema de gestión interna preexistente en la empresa. Toda la lógica de negocio y los datos residían en este sistema, accesible únicamente a través de una API REST. No se podía usar una base de datos local.
2.  **Abstracción para el Desarrollador:** ¿Cómo construir una aplicación Symfony compleja de forma productiva si los desarrolladores no pueden usar el ORM de Doctrine? El equipo necesitaba poder trabajar con Repositorios y Entidades de forma natural, sin tener que pensar en las complejidades de las llamadas HTTP a la API.
3.  **Bajo Rendimiento Crítico de la API:** El principal obstáculo técnico era que la API del sistema central tenía un rendimiento muy pobre, mucho más lento que una consulta directa a base de datos. Esto amenazaba con hacer que la nueva intranet fuera inusablemente lenta.

### 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto, diseñé una solución basada en una **Arquitectura Hexagonal** para aislar el núcleo de la aplicación de la infraestructura externa (la API) y para resolver el problema de rendimiento con una estrategia de caché a medida.

#### 1. Arquitectura de Persistencia Virtual sobre la API
Para que los desarrolladores pudieran trabajar de forma natural, "simulé" una capa de persistencia completa:
* **Entidades Virtuales:** Creé clases PHP que actuaban como entidades, pero en lugar de mapear a columnas de una base de datos, sus propiedades correspondían a los campos del JSON de la API.
* **Capa de Repositorios Personalizada:** Implementé una capa de repositorios que imitaba la interfaz de los repositorios de Doctrine. Una llamada como `$repositorio->find($id)` era traducida de forma transparente por una capa de servicio (`APIService`) a una petición `GET /recurso/{id}`. Un `save($entidad)` se convertía en un `POST` o `PUT`.
* **Traducción de Criterios:** El `APIService` era capaz de recibir objetos `Criteria` (similares a los de Doctrine) y construir con ellos las queries complejas (con filtros, ordenación, etc.) que se enviaban a la API.

#### 2. Sistema de Caché Multi-Nivel
Para solucionar el bajo rendimiento de la API, implementé una estrategia de caché con varias capas:
* **Caché Reactiva:** Las respuestas de las peticiones `GET` a la API se cacheaban. Cuando se realizaba una operación de escritura (`POST` o `PUT`), se implementó una lógica de **invalidación inteligente** que borraba únicamente las entradas de caché afectadas, manteniendo la consistencia de los datos.
* **Caché Proactiva ("Background Warming"):** Para las consultas más frecuentes y pesadas, se creó un **proceso en segundo plano (background)** que refrescaba la caché de forma periódica. De este modo, cuando un usuario accedía a estas vistas, los datos ya estaban pre-calentados y se servían al instante desde la caché, ocultando por completo la latencia de la API.

#### 3. Diseño para la Reutilización (Multi-Tenant)
Anticipando futuras necesidades, diseñé la capa de presentación (CSS y plantillas) de forma desacoplada, permitiendo una fácil adaptación a un entorno multi-empresa.

### 💡 Stack Tecnológico

* **Backend:** **Symfony**, PHP
* **Arquitectura:** **Arquitectura Hexagonal**, Patrón Repositorio, Patrón Data Mapper
* **Caché:** Estrategias de Caché Multi-Nivel (Reactiva y Proactiva)
* **Integraciones:** API REST

### ✅ Resultados e Impacto

* **Éxito en la Integración:** Se entregó una intranet moderna y funcional construida sobre un sistema externo sin necesidad de modificarlo, cumpliendo con el requisito principal del proyecto.
* **Experiencia de Usuario Óptima:** El sistema de caché multi-nivel resolvió con éxito el problema de rendimiento de la API, proporcionando a los usuarios una experiencia fluida y rápida.
* **Arquitectura Reutilizable:** El diseño fue un éxito rotundo. Toda la arquitectura (capa de abstracción, caché y frontend multi-empresa) fue **reutilizada con mínimas modificaciones en otros dos proyectos** que compartían el mismo sistema de gestión interno, ahorrando miles de horas de desarrollo.
* **Productividad del Equipo:** Los desarrolladores pudieron trabajar de manera eficiente y natural dentro del ecosistema de Symfony, completamente ajenos a la complejidad de la API subyacente.
---
# NIMROD – Arquitectura de una Plataforma de Alertas Reutilizable (2022)

### _Diseño de un sistema de eventos en tiempo real en Symfony, concebido desde su origen como un producto genérico y desplegado con éxito en los sectores sanitario y de seguridad industrial._

---

### 🎯 El Reto

El proyecto nació de una necesidad crítica en el sector sanitario (clientes como el **Servicio Extremeño de Salud** y la **Mutua de Accidentes de Zaragoza (MAZ)** ): proteger al personal médico en riesgo. Sin embargo, como arquitecto, mi reto iba más allá de resolver este caso de uso específico. El verdadero desafío era:

1.  **Diseñar un Núcleo Genérico:** En lugar de crear una solución a medida, el objetivo fue abstraer el problema para construir un motor de alertas reutilizable que pudiera aplicarse a futuros clientes con necesidades completamente diferentes.
2.  **Procesamiento de Eventos en Tiempo Real:** La plataforma debía ser capaz de ingerir y procesar un flujo constante de eventos desde diversas fuentes, aplicando reglas complejas para determinar si se debía disparar una alarma.
3.  **Garantizar la Notificación:** La respuesta a una alarma tenía que ser infalible, lo que requería la integración con múltiples canales de comunicación (SMS, VoIP, etc.) para asegurar que el mensaje llegara a su destino.

### 🛠️ La Solución y mi Rol como Arquitecto

Mi rol fue diseñar y desarrollar el backend completo de esta plataforma, a la que llamamos **NIMROD**. Las decisiones clave de la arquitectura fueron:

* **Abstracción Total del Dominio:** El núcleo del sistema no sabe qué es un "médico" o un "sensor de incendios". En su lugar, diseñé conceptos genéricos:
    * **"Estación":** Cualquier dispositivo o entidad capaz de emitir eventos.
    * **"Evento":** Cualquier suceso que ocurre en una estación, con sus datos asociados.
      Esta abstracción fue la clave que permitió la enorme flexibilidad del producto final.

* **Motor de Reglas Parametrizable:** Creé un motor donde, para cada implementación, se podían definir las reglas que convertían una secuencia de eventos en una alarma. Estas reglas permitían configurar precondiciones, umbrales de repetición, etc., haciendo que la lógica de negocio fuera totalmente personalizable por cliente.

* **Orquestador de Notificaciones:** Diseñé un servicio que, una vez activada una alarma, se encargaba de orquestar el envío de notificaciones a través de diversos canales, integrándose con gateways de **SMS** y sistemas de telefonía **VoIP** para realizar llamadas automatizadas.

* **Persistencia Agnóstica:** La capa de datos se implementó utilizando el Data Abstraction Layer de Doctrine, lo que permitió que la plataforma funcionara sin cambios sobre **MySQL**, **Oracle** o **Microsoft SQL Server**, adaptándose a la infraestructura de cada cliente.

### ✅ Resultados y Reutilización en Proyectos Reales

El éxito del diseño arquitectónico se demostró en su capacidad para ser adaptado y desplegado en múltiples escenarios con un esfuerzo mínimo:

* **Seguridad Sanitaria:** Se implementó como un sistema de **"Botón de Pánico"** para el **SES** y el **Hospital Militar de Zaragoza (MAZ)**, cumpliendo el objetivo original de proteger al personal.
* **Seguridad Industrial:** El mismo motor de NIMROD se configuró para la **gestión de accesos y alarmas de incendios**, tratando a los sensores de hardware como "Estaciones".
* **Evolución Continua:** Actualmente, la plataforma está siendo adaptada para su uso en la **gestión de sistemas de aguas**, lo que demuestra la vigencia y flexibilidad de la arquitectura original.

---
# The Switchers – Generador de Plataformas Formativas (2019)

### _Arquitectura de un sistema de metaprogramación en Symfony para crear "Toolboxes" interactivas de emprendimiento, con soporte multi-idioma completo (incluyendo RTL) y un complejo sistema de mentoring._

---

### 🎯 El Reto

Este proyecto, de grandes dimensiones y duración, fue un encargo para una agencia de las Naciones Unidas. Su misión era crear una plataforma online para el programa "The Switchers", destinado a ayudar a emprendedores de toda la cuenca del Mediterráneo (Europa y África) a lanzar empresas verdes.

Los desafíos técnicos y funcionales eran considerables:

1.  **Crear Herramientas, no solo Contenido:** El requisito no era construir una plataforma con 5 herramientas formativas fijas, sino construir una **plataforma capaz de generar nuevas "Toolboxes"** interactivas en el futuro. Se necesitaba una meta-aplicación.
2.  **Soporte Multi-idioma Real:** La plataforma debía dar servicio a una audiencia internacional muy diversa. Esto implicaba no solo traducir textos, sino ofrecer un soporte completo para idiomas que se escriben de derecha a izquierda (RTL) como el árabe, afectando a toda la maquetación y la interfaz de usuario.
3.  **Interacción y Mentoring Complejos:** El sistema debía facilitar una interacción profunda entre los emprendedores y sus mentores, permitiendo un ciclo de feedback continuo sobre tareas y respuestas específicas.

### 🛠️ La Solución y mi Rol como Arquitecto

Mi rol fue el de **Arquitecto de Software** de toda la solución. Mi principal responsabilidad fue diseñar y desarrollar el núcleo de la plataforma: el "Generador de Toolboxes".

La arquitectura se centró en los siguientes pilares:

* **El Generador de "Toolboxes" (Meta-aplicación):** En lugar de codificar las herramientas a mano, diseñé un sistema donde los administradores del programa podían definir:
    * La estructura completa de una "Toolbox": menús, textos, tareas y flujos de navegación.
    * Formularios complejos con sus campos y validaciones.
    * Reglas de negocio como precondiciones y poscondiciones para avanzar entre tareas.
    * Tablas de resumen y sistemas de puntuación (*scoring*).
    * Generación de documentos de salida (PDF/Word) basados en los datos introducidos por el usuario.

* **Sistema de Mentoring Integrado:** Diseñé un sistema de comunicación asíncrono donde los mentores podían dejar comentarios y feedback directamente asociados a cada tarea o respuesta de un alumno. El dashboard del alumno centralizaba estas conversaciones y le permitía volver al punto exacto de la "Toolbox" para refinar su trabajo.

* **Implementación Multi-idioma (con RTL):** Me encargué de asegurar que toda la arquitectura, desde el backend hasta las plantillas del frontend, fuera compatible con la direccionalidad del texto, garantizando que el árabe y otros idiomas RTL se renderizaran y funcionaran correctamente.

* **Módulo de Gestión de Convocatorias:** De forma paralela, el sistema incluía un módulo construido con **Symfony y Sonata** para gestionar todo el ciclo de vida del usuario: registro en las convocatorias, selección, asignación a cursos, etc.

### 💡 Stack Tecnológico

* **Backend:** **Symfony**, **Sonata Admin Bundle**
* **Arquitectura:** Meta-aplicación, Arquitectura modular
* **Frontend:** Soporte Multi-idioma (LTR/RTL)
* **Funcionalidades:** Sistema de Mentoring (Comentarios Asíncronos), Generación de Documentos (PDF/Word)

### ✅ Resultados e Impacto

* Se entregó con éxito una plataforma formativa a gran escala, cumpliendo con todos los requisitos de complejidad y alcance internacional.
* El enfoque de "meta-aplicación" otorgó al cliente una autonomía total para crear y evolucionar sus programas formativos sin necesidad de nuevos desarrollos, lo cual fue el mayor éxito del proyecto.
* La plataforma fue capaz de dar servicio a una base de usuarios diversa y multi-idioma, logrando la misión del programa "The Switchers".


* **Backend:** **Symfony**, PHP

---
# Plataforma de Integración de Datos (Middleware ETL) (2021)

Diseño de un sistema ETL genérico, basado en arquitectura CQRS y un motor de mapeo por configuración, para la integración y transformación de datos desde fuentes heterogéneas.

---

## 🎯 El Reto

Dentro de la empresa, existía una necesidad de negocio constante y repetitiva: importar y transformar datos desde una gran variedad de sistemas de origen (APIs de terceros, ficheros Excel, bases de datos, etc.) hacia nuestros propios sistemas.

El enfoque tradicional de escribir un script de importación a medida para cada nueva fuente era:

- **Lento y Costoso**: Requería horas de desarrollo para cada nueva integración.
- **Propenso a Errores**: La lógica se duplicaba y era difícil de mantener, introduciendo inconsistencias.
- **Poco Escalable**: No ofrecía una solución a largo plazo al problema fundamental.

El reto era claro: necesitábamos diseñar una única plataforma de middleware que pudiera orquestar cualquier proceso de integración de datos de forma genérica, sin necesidad de escribir nuevo código, simplemente mediante un fichero de configuración.

---

## 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto de la solución, diseñé un middleware de tipo **ETL (Extract, Transform, Load)** basado en una arquitectura **CQRS (Command and Query Responsibility Segregation)** y un sistema de *handlers* o módulos conectables.

La plataforma se componía de varios tipos de handlers, cada uno con un método `supports()` que le permitía actuar sobre un tipo de dato o fuente específica:

- **Connectors (Extractores)**:  
  Se encargan de conectar con una fuente de datos (API, Excel, base de datos) y extraer la información, transformándola a una estructura estandarizada interna.

- **Transformers (Transformadores)**:  
  Aplican transformaciones a nivel de campo individual, como cambiar formatos de fecha, concatenar strings, realizar cálculos, etc.

- **Comparers (Comparadores)**:  
  Comparan los datos de origen con los de destino, permitiendo, por ejemplo, importaciones diferenciales (solo registros nuevos o modificados).

El flujo completo se orquestaba a través de un fichero de configuración `.ini`, donde la sección principal era `[mapping]`. En esta sección, un desarrollador podía definir, para cada campo de destino, qué `Transformer` aplicar y de qué campo de origen obtener los datos.

Gracias a esta arquitectura, un proceso de importación complejo se reducía a crear un fichero `.ini` que definía qué `Connector`, `Comparer` y `Transformer` utilizar para cada caso.

---

## 💡 Stack Tecnológico y de Arquitectura

- **Arquitectura**: CQRS, ETL (Extract, Transform, Load), Patrón Strategy/Handler
- **Lenguaje**: PHP / Symfony
- **Configuración**: Ficheros INI

---

## ✅ Resultados e Impacto

- **Productización Interna**:  
  La plataforma se convirtió en la herramienta estándar de la empresa para cualquier tarea de importación de datos, reutilizada en innumerables ocasiones, ahorrando miles de horas de desarrollo.

- **Agilidad Radical**:  
  El tiempo necesario para integrar una nueva fuente de datos se redujo de días o semanas a, en muchos casos, unas pocas horas, simplemente creando un nuevo fichero de configuración.

- **Fiabilidad y Mantenibilidad**:  
  Al centralizar la lógica en handlers bien definidos y testeados, se redujo drásticamente el número de errores en las importaciones y se facilitó el mantenimiento y la extensión del sistema.

- **Autonomía para los Desarrolladores**:  
  Permitió que cualquier desarrollador del equipo pudiera configurar e implementar procesos de integración complejos sin necesidad de ser un experto en la fuente de datos original.
---

# ERP a Medida para Centro de Investigación (SERIDA) (2012)

Diseño y desarrollo de un sistema de gestión integral (ERP) con un motor de contabilidad analítica y un sistema de centros de coste jerárquico. En producción ininterrumpida desde hace más de 14 años.

---

## 🎯 El Reto

El **SERIDA** (Servicio Regional de Investigación y Desarrollo Agroalimentario) necesitaba una solución de software única y centralizada para gestionar la totalidad de sus procesos administrativos. El desafío no era solo crear módulos individuales, sino construir un sistema cohesionado con dos grandes retos:

- **Integración Profunda entre Módulos**:  
  La plataforma debía asegurar que las operaciones en un área se reflejaran de forma lógica y automática en otras. Por ejemplo, la solicitud de una dieta de viaje debía generar una entrada en el sistema de facturación, o una revisión de un vehículo en el gestor de inventario debía poder generar una tarea en el gestor de incidencias.

- **Contabilidad Analítica y Control Presupuestario Complejo**:  
  El requisito más exigente era la creación de un motor de contabilidad analítica a partir de la facturación. Este motor debía permitir un análisis de costes extremadamente granular y, a la vez, aplicar restricciones de gasto basadas en múltiples criterios jerárquicos.

---

## 🛠️ La Solución y mi Rol como Arquitecto

Como arquitecto y desarrollador principal de la solución, diseñé un ERP a medida compuesto por múltiples módulos interconectados, con un especial énfasis en el motor financiero.

Las decisiones clave de la arquitectura fueron:

- **Plataforma Modular Altamente Integrada**:  
  Desarrollé un conjunto completo de módulos administrativos (Gestión de Inventario, Incidencias, Facturas, Permisos, Biblioteca, etc.). La clave fue el diseño de un núcleo que permitía una comunicación fluida y lógica entre ellos, asegurando la consistencia de los datos en todo el sistema.

- **Motor de Contabilidad Analítica Jerárquica**:  
  Esta fue la pieza central y más compleja del proyecto. La diseñé sobre dos estructuras de datos en árbol:

    - Un árbol para los **Centros de Coste** de la organización.
    - Un árbol para los **Conceptos de Gasto** y sus anualidades.

  Este motor permitía realizar cálculos de costes agregados en cualquier nivel de ambos árboles. Un director podía ver el coste total de un departamento (nodo del árbol de centros de coste) o el gasto total en un concepto específico (nodo del árbol de conceptos), con la capacidad de desglosar los datos hasta el nivel más bajo.

- **Sistema de Restricciones Presupuestarias**:  
  Sobre el motor analítico, implementé una funcionalidad crítica de control de gasto. El sistema permitía a los administradores aplicar un bloqueo de gasto a cualquier combinación granular de `nodo de centro de coste + nodo de concepto + año`, impidiendo que se pudieran imputar nuevas facturas si se superaba el presupuesto asignado a esa intersección específica.

---

## 💡 Stack Tecnológico y Arquitectura

- **Arquitectura**: Arquitectura Modular, Contabilidad Analítica, Modelado de Datos Jerárquico (Árboles)
- **Tecnología**: Desarrollo a medida en PHP

---

## ✅ Resultados e Impacto

- **Centralización y Eficiencia**:  
  El ERP unificó con éxito todos los procesos administrativos del SERIDA, eliminando silos de información y optimizando la operativa interna.

- **Control Financiero sin Precedentes**:  
  El motor de contabilidad analítica proporcionó a la dirección una herramienta de análisis y control presupuestario extremadamente potente y detallada.

- **Testimonio de Robustez y Calidad**:  
  El mayor éxito del proyecto es su longevidad. El hecho de que la plataforma, desarrollada hace aproximadamente 13 años, siga en pleno funcionamiento hoy en día es la mejor prueba de una arquitectura sólida, un diseño escalable y una implementación de alta calidad.
---

# Proyecto Fin de Carrera: Framework de Desarrollo Rápido (RAD) (2012)

Creación de una herramienta de metaprogramación que genera aplicaciones de gestión completas (MVC) a partir de ficheros de definición, sentando las bases de mi especialización en arquitectura y siendo explotado comercialmente con posterioridad.

---

## 🎯 El Reto

Como Proyecto Fin de Carrera, el objetivo era explorar un concepto avanzado de la ingeniería de software que fuera más allá del desarrollo de una aplicación convencional. El reto que me planteé fue atacar la naturaleza repetitiva de la creación de aplicaciones de gestión empresarial.

El desafío era diseñar un framework que pudiera abstraer los componentes comunes de cualquier aplicación de gestión (formularios, informes, procesos de negocio) y automatizar su construcción, permitiendo un desarrollo mucho más rápido y consistente.

---

## 🛠️ La Solución y Arquitectura Diseñada

La solución fue el diseño y desarrollo de mi primera herramienta de metaprogramación: un **Framework de Desarrollo Rápido (RAD)** sobre un stack **LAMP**. Su propósito era generar aplicaciones web completas a partir de una especificación de alto nivel.

La arquitectura del generador seguía un proceso en dos fases:

- **Fase de Definición**:  
  El desarrollador creaba un fichero de definición donde especificaba la estructura de la aplicación: los modelos de datos, la composición de los formularios, el diseño de los informes y la lógica de los procesos de negocio.

- **Fase de Generación**:  
  Mi herramienta procesaba este fichero de definición y generaba un "código intermedio". Este código no era un prototipo, sino una **aplicación PHP completa, funcional y autónoma**.

La aplicación resultante quedaba perfectamente estructurada bajo el patrón arquitectónico **MVC (Modelo-Vista-Controlador)**, garantizando un código limpio y mantenible que se podía entregar directamente al cliente final.

---

## 💡 Stack Tecnológico y Arquitectura

- **Arquitectura**: Metaprogramación, Generación de Código, MVC (Model-View-Controller)
- **Stack**: LAMP (Linux, Apache, MySQL, PHP)

---

## ✅ Resultados e Impacto a Largo Plazo

- **Aplicación Comercial Real**:  
  El framework no fue un mero ejercicio teórico. Fue la herramienta utilizada para construir el **ERP a medida para el SERIDA** y varios proyectos comerciales más, siendo explotado con éxito durante casi una década (2012–2020).

- **La Semilla de mi Especialización**:  
  Este proyecto fue el germen de mi carrera en arquitectura de software. La fascinación por resolver problemas a través de la abstracción y la metaprogramación, que exploré aquí por primera vez, se convirtió en el pilar de mis futuros desarrollos, como la plataforma **Expedion** o el **Middleware ETL**.

---
# Arquitectura de Sistemas e Infraestructura para Centro de I+D (SERIDA)

Diseño, despliegue y gestión integral de la infraestructura de TI para los 4 centros del organismo, abarcando servidores, redes, virtualización y seguridad durante más de 15 años.

---

## 🎯 El Reto

A principios de mi trayectoria en el SERIDA, además de mis responsabilidades como desarrollador, me encontré con un desafío de infraestructura. El organismo, distribuido en cuatro centros de investigación, carecía de una infraestructura de TI unificada y gestionada profesionalmente.

El reto era construir desde cero y mantener una infraestructura completa que fuera:

- **Robusta y Fiable**: Para dar servicio ininterrumpido a más de 125 investigadores y personal administrativo.
- **Segura**: Protegiendo las comunicaciones internas y el acceso desde el exterior.
- **Escalable y Eficiente**: Optimizando el uso de los recursos de hardware y facilitando el crecimiento futuro.
- **Completa**: Abarcando todas las necesidades: red, almacenamiento, correo electrónico y servidores de aplicaciones.

---

## 🛠️ La Solución y mi Rol como Arquitecto de Sistemas

Asumí el rol de arquitecto y administrador principal de toda la infraestructura. Mi trabajo no fue un único proyecto, sino una **responsabilidad continua** de diseño, implementación y evolución tecnológica a lo largo de más de una década.

Las implementaciones clave incluyeron:

- **Diseño y Gestión de la Red**:  
  Planifiqué y mantuve la topología de red de los cuatro centros, incluyendo la configuración de la electrónica de red (routers, switches). Diseñé una solución de enrutamiento avanzado con **balanceo de carga sobre múltiples IPs externas** para garantizar la disponibilidad y optimizar el tráfico.

- **Implantación de Servidores Críticos**:  
  Desplegué y administré todos los servidores clave del organismo sobre **Linux**:

    - **Servidores de Correo**: Implantación inicial con *Sendmail*, migración posterior a *Zimbra*.
    - **Servidores de Ficheros**: Configuración de *Samba* para colaboración y almacenamiento centralizado.
    - **Comunicaciones y Seguridad**: *Iptables* y *Squid* para cortafuegos, proxy y control de acceso a internet.

- **Estrategia de Virtualización**:  
  Fui pionero en la adopción de la virtualización en el organismo, implementando plataformas **VMware** y posteriormente **XenCenter**. Esto permitió consolidar servidores, optimizar el hardware, simplificar la administración y establecer un plan de recuperación ante desastres.

---

## 💡 Stack Tecnológico de Sistemas (DevOps)

- **Sistemas Operativos**: Linux
- **Virtualización**: VMware, XenCenter
- **Servidores de Correo**: Sendmail, Zimbra
- **Servidores de Ficheros**: Samba
- **Redes y Seguridad**: Iptables, Squid, configuración avanzada de routers/switches, balanceo de carga
- **Servidores Web**: Apache

---

## ✅ Resultados e Impacto a Largo Plazo

- **Infraestructura Estable y Duradera**:  
  El resultado fue una infraestructura de TI completa y extremadamente estable que ha soportado la operativa de un centro de investigación multi-sede durante más de 15 años.

- **Consolidación del Perfil DevOps**:  
  Esta responsabilidad fue fundamental para forjar mi perfil híbrido, dándome un profundo conocimiento práctico de cómo las aplicaciones que desarrollo se comportan y operan en un entorno de producción real.

- **Continuidad de Negocio**:  
  Las soluciones implementadas (virtualización, balanceo de carga, seguridad) garantizaron la continuidad del negocio y la protección de los datos del SERIDA.

- **Liderazgo Tecnológico**:  
  Demostré la capacidad no solo de desarrollar software, sino de gestionar **todo el ciclo de vida tecnológico**, desde el cableado de red hasta la aplicación final, una visión que ha sido clave en toda mi carrera posterior.


# Historial Adicional de Proyectos

Además de los casos de estudio detallados, he participado y liderado una amplia variedad de proyectos para clientes de primer nivel en el sector público y privado, demostrando una gran versatilidad y capacidad de adaptación. Entre ellos se incluyen:

---

## 🛠️ Plataformas y Aplicaciones de Gestión a Medida

- **CAA (Consorcio de Aguas de Asturias)**:  
  Plataforma integral para la gestión de contadores, flotas de vehículos, facturación, inventario y mantenimiento, incluyendo la conexión con el ERP corporativo.

- **Acción Cultural Española (ACE)**:  
  Sistema para la gestión de subvenciones y candidaturas.

- **Aragón (Gestión EPIS)**:  
  Aplicación para la gestión y control de Equipos de Protección Individual (EPIs) para empleados.

- **ArcelorMittal**:  
  Desarrollo de un sistema de control de presencia de empleados (Proyecto COK).

- **CODEPA (Colegio de Enfermería de Asturias)**:  
  Desarrollo de la intranet corporativa.

- **CRL (Consell de Relacions Laborals)**:  
  Solución de gestión de expedientes basada en la plataforma "Expedion".

- **CSC (ConnectaCSC)**:  
  Plataforma de servicios para el sector hospitalario.

- **Junta de Castilla y León (JYCL)**:  
  Desarrollo de aplicaciones y software de gestión.

- **JyD (Pedidos Ortopedia)**:  
  Aplicación para la gestión de pedidos en el sector de la ortopedia.

- **ONCE**:  
  Desarrollo y mantenimiento de software de gestión interna.

- **Rula de Avilés**:  
  Sistema de gestión documental.

- **SADEX / SUBEMA**:  
  Aplicaciones web para la gestión de partes de trabajo en tiempo real.

- **SECUDAMED**:  
  Plataforma para la monitorización de aplicaciones y servicios.

- **VISESA**:  
  Desarrollo de software de formación a medida.

- **Ziving**:  
  Software de gestión para clínicas de ortodoncia.

- **Zoo de Barcelona**:  
  Desarrollo de aplicaciones y software de gestión.

---

## 📋 Consultoría Especializada y Soporte

- **IDAE (Instituto para la Diversificación y Ahorro de la Energía)**:  
  Consultoría especializada en Symfony para el equipo Drupal.

- **SERIDA (Servicio Regional de Investigación)**:  
  Soporte y mantenimiento de sistemas (2000–Actualidad), incluyendo planificación y desarrollo de múltiples aplicaciones de gestión (I+D, permisos, incidencias) y portales web.

- **Centro Tecnológico de la Madera**:  
  Planificación y consultoría de sistemas informáticos.

- **Alcalá de Henares (Proyecto Franklin)**:  
  Consultoría de seguridad y soporte técnico.

- **ethics4sports**:  
  Refactorización, modificación y mejora de una aplicación legacy.

- **Enabilities**:  
  Instalación y configuración de plataforma e-learning Moodle.

- **Hermes**:  
  Evolutivo y optimización de la aplicación interna de comunicaciones.

---

## 🔌 Integración, Middleware y Desarrollo de API

- **Ecoticket / Phototicket**:  
  Backend y API para digitalización de tickets, integración con TPV y motor analítico.

- **Astuaire**:  
  Middleware para la integración y publicación de datos en el portal web de Calidad del Aire.

- **Camino del Cid**:  
  Desarrollo del backend y la API de servicios.

- **Ferrocarriles**:  
  Middleware y API para sistemas de gestión ferroviaria.

- **Galvan**:  
  Diseño y desarrollo de API de servicios.

- **LexNet**:  
  Conectores para la plataforma de comunicación con la Administración de Justicia.

- **Ruta Vía de la Plata**:  
  API para la aplicación móvil de rutas culturales.

---

## 🌐 Portales Web y Gestión de Contenidos (CMS)

- **Antifraude (Oficina Antifraude de Cataluña)**:  
  Desarrollo del portal web corporativo.

- **ACA (Agència Catalana de l'Aigua)**:  
  Aplicación web para la monitorización del estado de las playas.

- **Biodiversidad (Fundación Biodiversidad)**:  
  Portal web para el proyecto "LIFE IP INTEMARES".

- **Cabildo de Tenerife**:  
  Rediseño y mejora del portal web corporativo.

- **Icairos / Comerzia**:  
  Plataforma de e-commerce para producto único.

- **Mallorca / Sierra de Tramontana**:  
  Portales web para rutas culturales y turísticas.

- **Mancoeduca (Gobierno de Navarra)**:  
  Desarrollo y mantenimiento del portal educativo sobre Drupal.

- **Entidades Públicas y Privadas Adicionales**:  
  Portales y aplicaciones para diversas entidades:  
  *Ayto. de Burgos, Salamanca, Gabias, Huesca, Autoridad Portuaria de Valencia, etc.*

- **Páginas Web para Eventos y Asociaciones**:  
  Desarrollo de portales para congresos y asociaciones:  
  *Congreso de Mejora Genética, SEAE, BTT Sierra de Tineo, etc.*

---


