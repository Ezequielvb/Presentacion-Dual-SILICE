# Presentación dual — Sílice

**Curso:** 2º DAM (Desarrollo de Aplicaciones Multiplataforma), turno de mañana  
**Centro educativo:** CPIFP Alan Turing (Málaga — PTA)  
**Curso académico:** 2025 / 2026  
**Empresa:** [Sílice](https://silice.si/) — consultora de transformación digital, IA y soluciones omnicanal  
**Ubicación de prácticas:** Málaga Tech Park (PTA)

---

## Participantes

| Alumno/a | Ciclo | Rol en la estancia |
| :-- | :-- | :-- |
| **Vargas Berrocal, Ezequiel** | 2º DAM mañana | Desarrollo frontend en el proyecto ITACA |
| **Bellón Payer, David** | 2º DAM mañana | Desarrollo frontend en el proyecto ITACA *(personalizar rol)* |

> Si en la empresa hay varios participantes, comparten este repositorio. Cada persona tiene su propio vídeo individual y su apartado de actividad más abajo.

---

## Vídeos de la exposición

La exposición está dividida en **tres vídeos**: una parte común sobre la empresa (máx. 5 min) y una parte individual por alumno (máx. 5 min cada una).

| Parte | Contenido | Duración máx. | Enlace |
| :-- | :-- | :-- | :-- |
| **Común — Sílice** | Introducción a la empresa, sector, proyectos y contexto de las prácticas | 5 min | **https://drive.google.com/drive/folders/1DBHf10vJXbCHSDrVDhgK7tZ4AEYaIFf_?usp=sharing** |
| **Individual — Ezequiel Vargas Berrocal** | Tareas, herramientas, aprendizajes y valoración personal | 5 min | **https://drive.google.com/drive/folders/1Cgcc3ZXRRJY0Wo8XuOP4aZMJaCbN5YGh?usp=sharing** |
| **Individual — David Bellón Payer** | Tareas, herramientas, aprendizajes y valoración personal | 5 min | **https://drive.google.com/drive/folders/1dJDHbsi7iolI9mYnAIhLouPOuXCEuVU6?usp=sharing** |

**Orden recomendado de visionado:** vídeo común → vídeo individual de cada participante.

---

## Parte común — Empresa Sílice

### Presentación de la empresa

Sílice es una consultora española de transformación digital fundada en 2005, con presencia en 17 países y sedes en Mérida, Ciudad de México, Bogotá, Ciudad de Panamá y **Málaga** (Málaga Tech Park). Desarrolla soluciones omnicanal e inteligencia artificial orientadas a mejorar la experiencia del ciudadano en sectores como administración pública, salud, banca y ciudades inteligentes.

### Proyecto principal de las prácticas: ITACA

Durante la estancia en Sílice hemos participado en **ITACA**, plataforma full-stack de gestión de empleo municipal para el Ayuntamiento de Mérida. El sistema incluye:

- **Portal ciudadano:** consulta de ofertas, CV, postulaciones y recomendaciones.
- **Portal empresa:** gestión de ofertas, candidatos y perfil corporativo.
- **API REST** (PHP / Yii2) con autenticación JWT.
- **Motor de afinidad** basado en Elasticsearch.

**Stack tecnológico del proyecto:**

| Capa | Tecnologías |
| :-- | :-- |
| Frontend | Angular 21, TypeScript, Bootstrap 5 |
| Backend / API | PHP 8.1+, Yii2, JWT |
| Datos | MySQL 8, Elasticsearch 8 |
| DevOps / entorno | Docker, GitLab |
| Calidad | Jasmine/Karma, Cypress (E2E) |

### Tutoría y metodología en empresa

- Trabajo en equipo con desarrolladores de Sílice.
- Uso de **Git** y flujo de ramas (feature branches, merge requests).
- Integración continua con el resto del equipo sobre repositorios compartidos.
- Reuniones de seguimiento y revisión de código.

---

## Actividad individual — Ezequiel Vargas Berrocal

### Rol y responsabilidades

Desarrollo **frontend** en Angular dentro del proyecto ITACA, centrado en la experiencia de **autenticación**, **registro** y **área privada de empresa** (dashboard, perfil y gestión de ofertas).

### Tareas desempeñadas y temporalización

| Periodo | Tareas principales |
| :-- | :-- |
| **Semanas 1–3** | Fase inicial de adaptación: revisión de documentación técnica de la empresa, introducción al stack backend con PHP y Yii2, pruebas técnicas con Yii2 Advanced, migraciones, modelos, controladores, vistas y endpoints. Configuración del entorno local con Docker, Git, GitLab, MySQL y phpMyAdmin. |
| **Semanas 4–8** | Primer contacto con el proyecto ITACA. Desarrollo de una versión inicial propia del frontend para experimentar con diseño, flujos de usuario y consumo de la API real. Pruebas de endpoints con Hoppscotch/Postman, revisión de respuestas JSON, detección de inconsistencias y comunicación de errores encontrados en la API. |
| **Semanas 9–13** | Trabajo sobre repositorios reales del proyecto, conectado al backend de la empresa y al entorno Dockerizado. Desarrollo y mejora de la parte de **empresa**: dashboard, perfil corporativo, gestión de ofertas, candidatos, mis ofertas y navegación entre apartados. |
| **Semanas 14–17** | Refactorización y mejora de mantenibilidad: separación de servicios y modelos por dominio, validadores reutilizables, gestión centralizada de errores, uso de variables CSS, revisión de componentes compartidos, corrección de incidencias visuales y funcionales, pruebas de integración con backend y preparación de la exposición dual. |

### Herramientas utilizadas

- **IDE:** Visual Studio Code / Cursor
- **Lenguajes y frameworks:** TypeScript, Angular 21, HTML, SCSS/CSS, Bootstrap 5
- **Control de versiones:** Git, GitLab
- **APIs:** Consumo de REST con `HttpClient`, interceptores JWT
- **Testing:** Jasmine, Karma; Cypress para pruebas E2E
- **Entorno:** Docker Compose, Node.js, npm

### Conocimientos adquiridos por módulo profesional

| Módulo | Aprendizajes en la estancia |
| :-- | :-- |
| **ADA** (Acceso a Datos) | Consumo de API REST, serialización JSON, gestión de respuestas y errores HTTP desde el cliente Angular. |
| **DI** (Desarrollo de Interfaces) | Diseño e implementación de interfaces responsivas, formularios reactivos, componentes modulares y mejora de UX en dashboard y perfil de empresa. |
| **PMDM** (Programación Multimedia y Dispositivos Móviles) | Adaptación de layouts y componentes a distintos viewports; criterios de usabilidad en aplicaciones web. |
| **PSP** (Programación de Servicios y Procesos) | Integración frontend–backend, autenticación con tokens JWT, flujos asíncronos y manejo de estados de carga y error. |
| **SGE** (Sistemas de Gestión Empresarial) | Comprensión del ciclo de vida de ofertas de empleo, perfiles de empresa y procesos de selección dentro de una plataforma de gestión. Creación de **usuarios de prueba** para validar flujos de negocio, limpiando y preparando datos con **pandas** antes de cargarlos en el entorno de pruebas. |
| **IPE / FCT** | Trabajo en entorno profesional real, metodología ágil en equipo, comunicación con compañeros y tutoría, y planificación de tareas en un proyecto de producción. |

### Valoración personal

La experiencia dual en Sílice me ha permitido aplicar en un proyecto real lo aprendido en el ciclo, especialmente en **interfaces web** y **integración con servicios**. Destaco el trabajo en ITACA sobre autenticación y el área de empresa, donde he visto de cerca cómo se organiza un producto con varios desarrolladores, ramas y revisiones.

**Aspectos positivos:** entorno profesional, proyecto con stack actual (Angular 21), tutorización del equipo y sensación de aportar código que se integra en el producto.

**Dificultades superadas:** adaptación a una codebase grande ya existente, resolución de conflictos en Git y alineación con convenciones del equipo.

**Proyección:** me gustaría seguir especializándome en desarrollo frontend y, en el futuro, profundizar en arquitectura de aplicaciones web y buenas prácticas de testing.

---

## Actividad individual — David Bellón Payer

### Rol y responsabilidades

Desarrollo **frontend** en Angular dentro del proyecto ITACA, centrado principalmente en la parte de **ciudadano** del portal: perfil del candidato, currículum, datos personales, seguridad, foto de perfil, completitud del perfil y navegación entre secciones.

También participé en tareas comunes del frontend, como organización de servicios y modelos por dominio, validaciones reutilizables, gestión de errores de API, componentes compartidos, estilos globales y mejora visual de pantallas.

### Tareas desempeñadas y temporalización

| Periodo | Tareas principales |
| :-- | :-- |
| **Semanas 1–3** | Fase inicial de adaptación: revisión de documentación técnica de la empresa, introducción al stack backend con PHP y Yii2, pruebas técnicas con Yii2 Advanced, migraciones, modelos, controladores, vistas y endpoints. Configuración del entorno local con Docker, Git, GitLab, MySQL y phpMyAdmin. |
| **Semanas 4–8** | Primer contacto con el proyecto ITACA. Desarrollo de una versión inicial propia del frontend para experimentar con diseño, flujos de usuario y consumo de la API real. Pruebas de endpoints con Hoppscotch/Postman, revisión de respuestas JSON, detección de inconsistencias y comunicación de errores encontrados en la API. |
| **Semanas 9–13** | Trabajo sobre repositorios reales del proyecto, conectado al backend de la empresa y al entorno Dockerizado. Desarrollo y mejora de la parte de ciudadano: perfil, datos personales, seguridad, foto de perfil, currículum, completitud del perfil y navegación entre apartados. |
| **Semanas 14–17** | Refactorización y mejora de mantenibilidad: separación de servicios y modelos por dominio, validadores reutilizables, gestión centralizada de errores, uso de variables CSS, revisión de componentes compartidos, corrección de incidencias visuales y funcionales, pruebas de integración con backend y preparación de la exposición dual. |

### Herramientas utilizadas

- **IDE:** Visual Studio Code / Cursor
- **Lenguajes y frameworks:** TypeScript, Angular, HTML, CSS, Tailwind, PHP, Yii2
- **Control de versiones:** Git, GitLab
- **APIs:** Consumo de API REST, autenticación JWT, pruebas con Hoppscotch/Postman
- **Entorno:** Docker Compose, Node.js, npm, MySQL, phpMyAdmin
- **Buenas prácticas:** variables de entorno, separación por dominios, validaciones reutilizables, componentes compartidos y gestión de errores

### Conocimientos adquiridos por módulo profesional

| Módulo | Aprendizajes en la estancia |
| :-- | :-- |
| **Desarrollo Web en Entorno Cliente** | Trabajo con Angular, componentes, rutas, formularios reactivos, servicios, consumo de APIs, validaciones, gestión de errores y actualización de vistas con datos reales del backend. |
| **Desarrollo Web en Entorno Servidor** | Refuerzo de PHP y Yii2 mediante pruebas técnicas, migraciones, modelos, controladores, endpoints y comprensión de respuestas JSON, validaciones y errores backend. |
| **Despliegue de Aplicaciones Web** | Uso de Docker y Docker Compose para levantar servicios del proyecto, configuración de puertos, variables de entorno, conexión con API, base de datos y servicios auxiliares. |
| **Diseño de Interfaces Web** | Mejora visual de pantallas del portal ciudadano, diseño responsive, formularios, modales, tarjetas, mensajes de usuario, uso de Tailwind y variables CSS para mantener coherencia visual. |
| **Inglés profesional** | Consulta de documentación técnica de Angular, Yii2, Docker y librerías; interpretación de errores; uso de terminología técnica en código, ramas, commits, servicios y modelos. |
| **Itinerario Personal para la Empleabilidad II** | Adaptación a un entorno profesional real, comunicación de incidencias, petición de feedback, responsabilidad sobre cambios en un proyecto compartido e iniciativa para proponer mejoras. También reflexión sobre el impacto de la digitalización y soluciones tecnológicas como las de gobierno inteligente y ciudades digitales. |
| **Módulo optativo — Desarrollo Full-Stack** | Comprensión del flujo completo de una funcionalidad: frontend, API, backend, base de datos, validaciones, errores, entorno Docker y pruebas con datos reales. |

### Valoración personal

La experiencia dual en Sílice me ha permitido aplicar en un proyecto real muchos de los contenidos del ciclo, especialmente en **desarrollo frontend**, integración con APIs y diseño de interfaces.

Destaco el trabajo en ITACA sobre la parte de ciudadano, donde he podido mejorar pantallas, conectar funcionalidades con el backend, revisar errores reales y entender mejor cómo se organiza un proyecto profesional con varios desarrolladores, ramas y repositorios compartidos.

**Aspectos positivos:** trabajar en un entorno real, usar tecnologías actuales, recibir feedback técnico, aprender de una codebase existente y ver cómo se integran frontend, backend, base de datos y Docker en un mismo proyecto.

**Dificultades superadas:** adaptación a una arquitectura grande, consumo de APIs reales, detección de errores backend/frontend, organización del código para que fuera mantenible y coordinación con el flujo de trabajo del equipo.

**Proyección:** me gustaría seguir especializándome en desarrollo frontend, profundizando en Angular, arquitectura de aplicaciones web, buenas prácticas de código y desarrollo full-stack.
