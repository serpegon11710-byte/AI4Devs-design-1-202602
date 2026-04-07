# PRD — Sistema ATS para la gestión de candidatos

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

## 4. User Stories principales

### Gestión de candidatos
- Como recruiter, quiero centralizar candidatos para evitar pérdida de información.
- Como recruiter, quiero filtrar candidatos rápidamente.

### Gestión de vacantes
- Como recruiter, quiero crear vacantes con pipelines personalizados.
- Como hiring manager, quiero visibilidad del estado.

### Pipeline de selección
- Como recruiter, quiero mover candidatos entre etapas fácilmente.
- Como equipo, quiero detectar cuellos de botella.

### Comunicación
- Como recruiter, quiero enviar emails con plantillas.
- Como candidato, quiero recibir comunicación clara.

### Evaluación
- Como entrevistador, quiero dejar feedback estructurado.
- Como hiring manager, quiero comparar candidatos.

### Reporting
- Como Head of Talent, quiero ver métricas clave.
- Como empresa, quiero identificar mejores fuentes.

### Automatización
- Como recruiter, quiero automatizar tareas repetitivas.

---

## 5. Requisitos funcionales

### 5.1 Gestión de candidatos
- Base de datos centralizada.
- Parsing automático de CV.
- Perfiles enriquecidos.
- Búsqueda avanzada.

### 5.2 Gestión de vacantes
- Creación y edición.
- Pipelines personalizados.
- Plantillas.

### 5.3 Publicación de ofertas
- Multiposting.
- Career site.
- Formularios personalizados.

### 5.4 Pipeline de selección
- Vista kanban.
- Estados configurables.
- Drag & drop.
- Automatización básica.

### 5.5 Comunicación
- Envío de emails.
- Plantillas.
- Historial.
- Notificaciones.

### 5.6 Evaluación
- Scorecards.
- Feedback estructurado.
- Ratings.
- Comparación.

### 5.7 Entrevistas
- Integración con calendarios.
- Scheduling.
- Recordatorios.

### 5.8 Reporting
- Dashboard con:
  - Time-to-hire
  - Funnel
  - Source of hire
- Exportación.

### 5.9 Automatización
- Reglas automáticas.
- Workflows.

### 5.10 Talent pool
- Base reutilizable.
- Segmentación.
- Búsqueda interna.

### 5.11 Permisos
- Roles.
- Control de acceso.

### 5.12 Integraciones
- Job boards.
- Calendarios.
- HRIS.
- API.

### 5.13 Cumplimiento legal
- GDPR.
- Retención de datos.
- Auditoría.

---

## 6. Requisitos no funcionales

### Rendimiento
- < 2s en vistas principales.
- Soporte >100k candidatos.

### Disponibilidad
- SLA ≥ 99.5%.

### Seguridad
- Encriptación.
- SSO / MFA.
- GDPR.

### Escalabilidad
- Multi-tenant.
- Multi-país / idioma.

### Usabilidad
- Curva de aprendizaje < 1 semana.
- UX optimizada.

### Fiabilidad
- Integridad de datos.
- Logs auditables.

---

## 7. Criterios de éxito

### Adopción
- % usuarios activos.
- % vacantes gestionadas en el sistema.

### Eficiencia
- Tiempo medio por candidato.
- Reducción de tareas manuales.

### Performance
- Reducción time-to-hire.
- Mejora conversiones.

### Calidad
- Tasa de aceptación de ofertas.
- Retención a 6 meses.

### Experiencia
- NPS candidato.
- Tiempo de respuesta.

### ROI
- Coste por contratación.
- Hires por recruiter.

---

## 8. Alcance MVP

### Incluido
- Gestión de candidatos.
- Pipeline básico.
- Publicación de ofertas.
- Emails.
- Reporting básico.

### Excluido
- Automatización avanzada.
- Integraciones complejas.
- Analítica avanzada.

---

## 9. Riesgos

- Resistencia al cambio.
- Baja calidad de datos inicial.
- Dependencia de integraciones.
- Complejidad UX.

---

## 10. Supuestos

- Volumen de contratación suficiente.
- Procesos estructurados.
- Disposición al cambio de herramienta.

---
