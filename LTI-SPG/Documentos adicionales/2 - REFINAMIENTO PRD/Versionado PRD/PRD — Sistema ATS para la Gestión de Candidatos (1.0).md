# PRD — Sistema ATS para la Gestión de Candidatos

> **Versión:** 1.0  
> **Fecha:** Abril 2026  
> **Estado:** Draft  
> **Autor:** Product Management

---

## Descripción del Producto

### ¿Qué es LTI ATS?

LTI ATS es un sistema de seguimiento de candidatos (Applicant Tracking System) diseñado para empresas con procesos de selección estructurados. Centraliza, automatiza y da visibilidad a todo el ciclo de reclutamiento: desde la apertura de una vacante hasta la contratación y el análisis posterior del proceso.

El sistema elimina la fragmentación típica de los procesos de recruiting apoyados en email, hojas de cálculo o portales de empleo aislados, y los reemplaza con un flujo de trabajo unificado, colaborativo y medible.

### Valor añadido

| Problema actual | Valor que aporta LTI ATS |
|---|---|
| Información dispersa en emails y carpetas | Base de datos centralizada y perfiles enriquecidos |
| Procesos manuales y repetitivos | Automatización de tareas de bajo valor |
| Falta de visibilidad del pipeline | Vista kanban en tiempo real para todo el equipo |
| Decisiones poco estructuradas | Scorecards, comparativas y feedback estructurado |
| Mala experiencia del candidato | Comunicación automatizada, rápida y consistente |
| Dificultad para escalar el hiring | Procesos estandarizados y replicables |

### Ventajas competitivas

1. **Configurabilidad del pipeline** — Etapas, campos y automatizaciones adaptables a cada proceso, sin necesidad de desarrollo.
2. **Colaboración nativa** — Hiring managers y entrevistadores participan dentro del sistema con permisos granulares, sin fricciones.
3. **Analítica accionable** — Métricas de funnel, source of hire y time-to-hire disponibles en tiempo real, sin exportar datos.
4. **Experiencia del candidato integrada** — Portal de empleo propio, comunicación automatizada y seguimiento de estado sin herramientas externas.
5. **Cumplimiento legal desde el diseño** — GDPR y retención de datos gestionados nativamente, sin añadidos.
6. **Curva de aprendizaje corta** — UX optimizada para recruiters con onboarding funcional en menos de una semana.

---

## Funciones Principales

### 1. Gestión de candidatos
Base de datos centralizada con perfiles completos (CV, experiencia, historial de interacciones), parsing automático de CV, búsqueda avanzada y filtrado por criterios estructurados.

### 2. Gestión de vacantes
Creación y edición de vacantes con pipelines personalizados, plantillas reutilizables y configuración de fases del proceso.

### 3. Publicación y distribución de ofertas
Multiposting en portales de empleo, career site propio con formularios personalizados y activación de canales de atracción.

### 4. Pipeline de selección
Vista kanban con drag & drop, estados configurables, automatización de cambios de fase y detección de cuellos de botella.

### 5. Comunicación con candidatos
Envío de emails desde el sistema, plantillas automatizadas, historial completo de comunicaciones y notificaciones a stakeholders.

### 6. Evaluación y colaboración interna
Scorecards estructurados, feedback entre entrevistadores y hiring managers, ratings y comparativas entre candidatos.

### 7. Coordinación de entrevistas
Integración con calendarios (Google, Outlook), scheduling automático, invitaciones y recordatorios.

### 8. Reporting y analítica
Dashboard con métricas clave (time-to-hire, cost-per-hire, source of hire, conversiones del funnel), exportación de informes y vista ejecutiva.

### 9. Automatización de procesos
Reglas automáticas basadas en eventos, workflows configurables e integraciones con herramientas externas vía API y webhooks.

### 10. Talent Pool
Base de candidatos reutilizable con etiquetado, segmentación y búsqueda interna para reapertura de procesos.

### 11. Cumplimiento legal
Gestión de consentimiento GDPR, control de retención de datos, anonimización de perfiles y auditoría de accesos.

---

## Lean Canvas
```
┌─────────────────────────────────────────────────────────────────────────────────────────┐
│                                     LEAN CANVAS — LTI ATS                               │
├──────────────────────┬───────────────────────────┬──────────────────────────────────────┤
│  PROBLEMA            │  SOLUCIÓN                 │  PROPUESTA DE VALOR ÚNICA            │
│                      │                           │                                      │
│ 1. Fragmentación de  │ · ATS centralizado con    │ El sistema de recruiting que         │
│    información en    │   pipeline visual          │ conecta a recruiters, hiring         │
│    emails y hojas    │ · Automatización de        │ managers y candidatos en un          │
│    de cálculo        │   tareas repetitivas       │ único flujo, sin fricción,           │
│                      │ · Comunicación integrada   │ medible desde el día uno.            │
│ 2. Procesos manuales │   con candidatos           │                                      │
│    que no escalan    │ · Analítica accionable     │                                      │
│                      │   en tiempo real           │                                      │
│ 3. Falta de          │                           │                                      │
│    visibilidad y     ├───────────────────────────┤                                      │
│    trazabilidad      │  VENTAJA INJUSTA          │                                      │
│                      │                           │                                      │
│ 4. Mala experiencia  │ · Pipeline 100%           │                                      │
│    del candidato     │   configurable            │                                      │
│                      │ · UX < 1 semana           │                                      │
│ 5. Decisiones poco   │   de onboarding           │                                      │
│    estructuradas     │ · GDPR nativo             │                                      │
├──────────────────────┼───────────────────────────┼──────────────────────────────────────┤
│  SEGMENTO DE         │  MÉTRICAS CLAVE           │  CANALES                             │
│  CLIENTES            │                           │                                      │
│                      │ · Time-to-hire            │ · Venta directa B2B                  │
│ Primario:            │ · Cost-per-hire           │ · Partnerships con consultoras       │
│ Empresas con 50–     │ · Tasa de adopción        │   de RRHH                            │
│ 5.000 empleados      │   interna (> 85%)         │ · Marketplaces de software           │
│ con procesos de      │ · NPS del candidato       │   (G2, Capterra)                     │
│ selección            │ · Hires por recruiter     │ · Inbound (SEO, contenido)           │
│ estructurados        │ · Tasa de conversión      │ · Prueba gratuita / freemium         │
│                      │   del pipeline            │                                      │
│ Usuarios operativos: │                           │                                      │
│ Recruiters, Talent   │                           │                                      │
│ Coordinators         │                           │                                      │
│                      │                           │                                      │
│ Decisores:           │                           │                                      │
│ Head of Talent,      │                           │                                      │
│ HR Director, COO     │                           │                                      │
├──────────────────────┴───────────────────────────┴──────────────────────────────────────┤
│  ESTRUCTURA DE COSTES                    │  FUENTES DE INGRESOS                         │
│                                          │                                              │
│ · Desarrollo y mantenimiento del producto│ · Suscripción SaaS mensual/anual             │
│ · Infraestructura cloud (multi-tenant)   │   (por nº de usuarios o vacantes activas)    │
│ · Equipo de Customer Success             │ · Tier de funcionalidades (Standard,         │
│ · Ventas y marketing B2B                 │   Professional, Enterprise)                  │
│ · Integraciones con terceros             │ · Servicios de onboarding e implementación   │
│ · Soporte y SLA                          │ · API access para integraciones enterprise   │
└──────────────────────────────────────────┴──────────────────────────────────────────────┘
```

---

## 1. Problema a resolver

Las empresas con procesos de selección estructurados enfrentan:

- Fragmentación de la información (emails, hojas de cálculo, job boards).
- Procesos manuales y repetitivos.
- Falta de visibilidad sobre el pipeline de selección.
- Decisiones poco estructuradas.
- Mala experiencia del candidato.
- Dificultad para escalar el hiring.

**Problema central:**  
El proceso de selección es ineficiente, poco escalable y carece de trazabilidad, impactando en coste, tiempo y calidad de contratación.

---

## 2. Objetivos del producto (medibles)

### Objetivos de negocio
- Reducir el **time-to-hire** en ≥ 30%.
- Reducir el **cost-per-hire** en ≥ 20%.
- Alcanzar **adopción interna > 85%**.
- Incrementar la **tasa de conversión del pipeline** en ≥ 15%.

### Objetivos de usuario
- Reducir tiempo administrativo del recruiter en ≥ 40%.
- Reducir tiempo medio de screening en ≥ 50%.
- Lograr ≥ 90% de procesos con feedback estructurado.

### Objetivos de experiencia
- Incrementar **NPS de candidatos** en +20 puntos.
- Reducir tiempo de respuesta al candidato a < 48h.

---

## 3. Usuarios y stakeholders

### Usuarios operativos
- Recruiters
- Talent Acquisition Specialists
- Talent Coordinators

### Usuarios secundarios
- Hiring Managers
- Entrevistadores

### Decisores de compra
- Head of Talent / HR Director
- COO / CEO
- CFO

---

## 4. Customer Journey

El uso del ATS sigue un ciclo operativo continuo, no un funnel lineal:

| Fase | Actividad | Interacción con el ATS |
|---|---|---|
| 1. Definición de la vacante | Solicitud del hiring manager, definición del perfil | Creación de vacante, configuración del pipeline |
| 2. Publicación | Redacción y selección de canales | Multiposting, career site, formularios |
| 3. Recepción de candidaturas | Llegada de candidatos | Parsing de CV, creación de perfiles, asignación |
| 4. Screening inicial | Revisión de candidatos | Filtrado, preguntas knockout, clasificación |
| 5. Comunicación inicial | Contacto con candidatos que avanzan | Plantillas de email, automatizaciones |
| 6. Gestión del pipeline | Avance por fases | Kanban, movimiento entre etapas |
| 7. Coordinación de entrevistas | Organización con stakeholders | Calendario, invitaciones, recordatorios |
| 8. Evaluación | Recogida de feedback | Scorecards, comentarios, comparativas |
| 9. Decisión | Selección del candidato final | Comparativa, consolidación, cambio de estado |
| 10. Gestión de la oferta | Envío y negociación | Generación y tracking de oferta |
| 11. Cierre | Finalización de la vacante | Marcado como hired, rechazos automáticos |
| 12. Analítica | Evaluación del rendimiento | Métricas, cuellos de botella, informes |
| 13. Talent pool | Reutilización de candidatos | Etiquetado, búsquedas, reapertura |
| 14. Optimización | Ajuste del proceso | Modificación de pipelines, automatizaciones |

**Ciclo resumido:** Crear vacante → Atraer → Evaluar → Contratar → Analizar → Optimizar → Repetir

---

## 5. User Stories principales

### Gestión de candidatos
- Como recruiter, quiero centralizar candidatos para evitar pérdida de información.
- Como recruiter, quiero filtrar candidatos rápidamente por criterios estructurados.

### Gestión de vacantes
- Como recruiter, quiero crear vacantes con pipelines personalizados.
- Como hiring manager, quiero visibilidad del estado de cada vacante.

### Pipeline de selección
- Como recruiter, quiero mover candidatos entre etapas fácilmente.
- Como equipo, quiero detectar cuellos de botella en el proceso.

### Comunicación
- Como recruiter, quiero enviar emails con plantillas sin salir del sistema.
- Como candidato, quiero recibir comunicación clara sobre el estado de mi candidatura.

### Evaluación
- Como entrevistador, quiero dejar feedback estructurado tras cada entrevista.
- Como hiring manager, quiero comparar candidatos objetivamente.

### Reporting
- Como Head of Talent, quiero ver métricas clave del proceso de selección.
- Como empresa, quiero identificar las mejores fuentes de candidatos.

### Automatización
- Como recruiter, quiero automatizar tareas repetitivas para dedicar tiempo a lo que importa.

---

## 6. Requisitos funcionales

### 6.1 Gestión de candidatos
- Base de datos centralizada con historial completo.
- Parsing automático de CV.
- Perfiles enriquecidos (experiencia, habilidades, notas, documentos).
- Búsqueda y filtrado avanzado.

### 6.2 Gestión de vacantes
- Creación, edición y clonación de vacantes.
- Pipelines personalizados por vacante o plantilla.
- Estados y configuración de fases.

### 6.3 Publicación de ofertas
- Multiposting en portales de empleo (InfoJobs, LinkedIn, Indeed…).
- Career site propio con formularios personalizados.
- Tracking de fuente de candidatura.

### 6.4 Pipeline de selección
- Vista kanban con drag & drop.
- Estados configurables.
- Automatización de cambios de estado.
- Alertas de inactividad.

### 6.5 Comunicación
- Envío de emails desde el sistema.
- Plantillas personalizables.
- Historial de comunicaciones por candidato.
- Notificaciones internas.

### 6.6 Evaluación
- Scorecards con criterios configurables.
- Feedback estructurado por fase.
- Ratings y comentarios internos.
- Comparativa visual entre candidatos.

### 6.7 Coordinación de entrevistas
- Integración con Google Calendar y Outlook.
- Scheduling con disponibilidad del entrevistador.
- Recordatorios automáticos.

### 6.8 Reporting
- Dashboard con métricas: time-to-hire, funnel, source of hire, cost-per-hire.
- Exportación de informes (CSV, PDF).
- Filtros por vacante, equipo, periodo.

### 6.9 Automatización
- Reglas basadas en eventos (candidato avanza → enviar email).
- Workflows configurables sin código.
- Screening automático por criterios.

### 6.10 Talent Pool
- Base reutilizable de candidatos no seleccionados.
- Etiquetado y segmentación.
- Búsqueda y contacto interno.

### 6.11 Gestión de permisos
- Roles: Admin, Recruiter, Hiring Manager, Entrevistador.
- Control de acceso por vacante o equipo.

### 6.12 Integraciones
- Job boards y portales de empleo.
- Calendarios (Google, Outlook).
- HRIS (Workday, BambooHR…).
- API REST y webhooks para integraciones custom.

### 6.13 Cumplimiento legal
- Gestión de consentimiento GDPR.
- Control de retención y eliminación de datos.
- Auditoría de accesos.
- Anonimización de perfiles.

---

## 7. Requisitos no funcionales

### Rendimiento
- Carga de vistas principales < 2 segundos.
- Soporte para bases de datos > 100.000 candidatos.

### Disponibilidad
- SLA ≥ 99,5%.

### Seguridad
- Encriptación en tránsito (TLS) y en reposo (AES-256).
- SSO y MFA.
- Cumplimiento GDPR.

### Escalabilidad
- Arquitectura multi-tenant.
- Soporte multi-país e idioma.

### Usabilidad
- Curva de aprendizaje < 1 semana para usuarios operativos.
- UX optimizada para flujos de trabajo recurrentes.

### Fiabilidad
- Integridad de datos garantizada.
- Logs auditables.
- Backup automático.

---

## 8. Criterios de éxito

| Dimensión | Métrica | Objetivo |
|---|---|---|
| Adopción | % usuarios activos / vacantes en sistema | > 85% |
| Eficiencia | Reducción de tiempo administrativo | ≥ 40% |
| Eficiencia | Reducción de time-to-hire | ≥ 30% |
| Calidad | Tasa de aceptación de ofertas | Mejora ≥ 10% |
| Calidad | Retención a 6 meses de contratados | Mejora ≥ 10% |
| Experiencia | NPS del candidato | +20 puntos |
| Experiencia | Tiempo de respuesta al candidato | < 48h |
| ROI | Cost-per-hire | Reducción ≥ 20% |
| ROI | Hires por recruiter al año | Incremento ≥ 15% |

---

## 9. Alcance MVP

### Incluido en MVP
- Gestión de candidatos (base de datos + parsing de CV).
- Pipeline básico con vista kanban.
- Publicación de ofertas y career site.
- Comunicación por email con plantillas.
- Reporting básico (time-to-hire, funnel, source).
- Gestión de permisos por roles.

### Excluido del MVP (fases posteriores)
- Automatización avanzada y workflows complejos.
- Integraciones con HRIS.
- Analítica avanzada y dashboards personalizados.
- Talent pool con IA de recomendación.
- API pública para integraciones custom.

---

## 10. Riesgos

| Riesgo | Probabilidad | Impacto | Mitigación |
|---|---|---|---|
| Resistencia al cambio del equipo | Alta | Alto | Onboarding guiado y Quick Wins tempranos |
| Baja calidad de datos iniciales | Media | Medio | Herramientas de importación y limpieza de datos |
| Dependencia de integraciones externas | Media | Alto | MVP sin integraciones críticas; API en fase 2 |
| Complejidad UX percibida | Media | Alto | UX testing con recruiters reales antes de lanzar |
| Adopción baja de hiring managers | Alta | Medio | Vista simplificada y notificaciones push para HM |

---

## 11. Supuestos

- La empresa tiene un volumen de contratación suficiente para justificar un ATS (> 10 vacantes/año o procesos simultáneos recurrentes).
- Existe al menos un recruiter o responsable de RRHH dedicado.
- La empresa tiene disposición para estandarizar y documentar sus procesos de selección.
- Los decisores de compra entienden el ROI de reducir el time-to-hire y el cost-per-hire.

---

*Documento vivo — sujeto a revisión tras validación con usuarios y stakeholders.*