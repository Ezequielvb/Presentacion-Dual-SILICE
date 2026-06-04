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
| **[Nombre del segundo participante]** | 2º DAM | **[Rol / área en Sílice — completar]** |

> Si en la empresa hay varios participantes, comparten este repositorio. Cada persona tiene su propio vídeo individual y su apartado de actividad más abajo.

---

## Vídeos de la exposición

La exposición está dividida en **tres vídeos**: una parte común sobre la empresa (máx. 5 min) y una parte individual por alumno (máx. 5 min cada una).

| Parte | Contenido | Duración máx. | Enlace |
| :-- | :-- | :-- | :-- |
| **Común — Sílice** | Introducción a la empresa, sector, proyectos y contexto de las prácticas | 5 min | **[URL del vídeo común — completar]** |
| **Individual — Ezequiel Vargas Berrocal** | Tareas, herramientas, aprendizajes y valoración personal | 5 min | **[URL del vídeo individual de Ezequiel — completar]** |
| **Individual — [Nombre del segundo participante]** | Tareas, herramientas, aprendizajes y valoración personal | 5 min | **[URL del vídeo individual — completar]** |

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
| **Semanas 1–4** | Integración en el equipo, configuración del entorno local (Angular, Docker), familiarización con la arquitectura ITACA y el flujo Git del proyecto. |
| **Semanas 5–10** | Desarrollo de **login y registro** (ciudadano y empresa): formularios reactivos, validaciones, manejo de errores de backend e integración con la API REST y JWT. |
| **Semanas 11–16** | Implementación y mejora del **dashboard de empresa** y del **perfil de empresa**: diseño de interfaz, componentes reutilizables, cabeceras y navegación del área privada. |
| **Semanas 17–22** | Refactorización UI/UX del dashboard y perfil, integración de **captcha** en flujos de autenticación, corrección de incidencias y merges con la rama de desarrollo del equipo. |
| **Semanas 23–28** | Pruebas funcionales, revisión de código con el equipo, ajustes de accesibilidad y consistencia visual, documentación de cambios y preparación de la exposición dual. |

> Ajusta las semanas si tu calendario real de FCT fue distinto.

### Herramientas utilizadas

- **IDE:** Visual Studio Code / Cursor
- **Lenguajes y frameworks:** TypeScript, Angular 21, HTML, SCSS/CSS, Bootstrap 5
- **Control de versiones:** Git, GitLab
- **APIs:** Consumo de REST con `HttpClient`, interceptores JWT
- **Testing:** Jasmine, Karma; Cypress para pruebas E2E
- **Entorno:** Docker Compose, Node.js, npm
- **Comunicación y gestión:** [Teams / Slack / Jira — completar si aplica]

### Conocimientos adquiridos por módulo profesional

| Módulo | Aprendizajes en la estancia |
| :-- | :-- |
| **ADA** (Acceso a Datos) | Consumo de API REST, serialización JSON, gestión de respuestas y errores HTTP desde el cliente Angular. |
| **DI** (Desarrollo de Interfaces) | Diseño e implementación de interfaces responsivas, formularios reactivos, componentes modulares y mejora de UX en dashboard y perfil de empresa. |
| **PMDM** (Programación Multimedia y Dispositivos Móviles) | Adaptación de layouts y componentes a distintos viewports; criterios de usabilidad en aplicaciones web. |
| **PSP** (Programación de Servicios y Procesos) | Integración frontend–backend, autenticación con tokens JWT, flujos asíncronos y manejo de estados de carga y error. |
| **SGE** (Sistemas de Gestión Empresarial) | Comprensión del ciclo de vida de ofertas de empleo, perfiles de empresa y procesos de selección dentro de una plataforma de gestión. |
| **IPE / FCT** | Trabajo en entorno profesional real, metodología ágil en equipo, comunicación con compañeros y tutoría, y planificación de tareas en un proyecto de producción. |

### Valoración personal

La experiencia dual en Sílice me ha permitido aplicar en un proyecto real lo aprendido en el ciclo, especialmente en **interfaces web** y **integración con servicios**. Destaco el trabajo en ITACA sobre autenticación y el área de empresa, donde he visto de cerca cómo se organiza un producto con varios desarrolladores, ramas y revisiones.

**Aspectos positivos:** entorno profesional, proyecto con stack actual (Angular 21), tutorización del equipo y sensación de aportar código que se integra en el producto.

**Dificultades superadas:** adaptación a una codebase grande ya existente, resolución de conflictos en Git y alineación con convenciones del equipo.

**Proyección:** me gustaría seguir especializándome en desarrollo frontend y, en el futuro, profundizar en arquitectura de aplicaciones web y buenas prácticas de testing.

---

## Actividad individual — [Nombre del segundo participante]

> **Completar** este apartado con la información del segundo alumno. Debe incluir las mismas secciones: rol, tareas por semanas, herramientas, módulos y valoración personal.

### Rol y responsabilidades

[Completar]

### Tareas desempeñadas y temporalización

| Periodo | Tareas principales |
| :-- | :-- |
| **Semanas 1–X** | [Completar] |
| **Semanas X–Y** | [Completar] |

### Herramientas utilizadas

[Completar]

### Conocimientos adquiridos por módulo profesional

| Módulo | Aprendizajes en la estancia |
| :-- | :-- |
| **ADA** | [Completar] |
| **DI** | [Completar] |
| **PMDM** | [Completar] |
| **PSP** | [Completar] |
| **SGE** | [Completar] |
| **IPE / FCT** | [Completar] |

### Valoración personal

[Completar]

---

## Material adicional en este repositorio

| Recurso | Descripción |
| :-- | :-- |
| `docs/` | Diapositivas, capturas o documentación complementaria *(añadir archivos si procede)* |
| Proyecto ITACA (frontend) | Código desarrollado durante las prácticas — repositorio interno de Sílice / GitLab *(enlace interno; no publicar si la empresa no lo autoriza)* |

---

## Cumplimiento de requisitos (checklist)

- [x] `README.md` en la raíz con información para evaluar la estancia
- [x] Parte común de la empresa documentada
- [x] Actividad individual por participante (tareas, semanas, herramientas, módulos, valoración)
- [ ] Enlaces a los vídeos insertados en la tabla superior
- [ ] Material complementario subido al repositorio (si aplica)

---

## Contacto

- **Alumno:** Ezequiel Vargas Berrocal — `ezequielvargasb11@gmail.com`
- **Repositorio de entrega:** [github.com/Ezequielvb/Presentacion-Dual-SILICE](https://github.com/Ezequielvb/Presentacion-Dual-SILICE)
