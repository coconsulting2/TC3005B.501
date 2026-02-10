# Análisis de Esfuerzo / WBS

**Equipo 1 COCONSULTIG2**
**11 de febrero del 2026**

**Planeación de sistemas de software**

**Profesor:**
Eduardo Rubinstein Meizner

---

## Diagrama de Roles

### Backend Developer's

**Función:**
Construcción de:
- APIs
- lógica de la aplicación
- base de datos
- integraciones

Responsable de rendimiento y seguridad del servidor.

**Candidatos Idóneos:** Mariano Carretero, Kevin Esquivel, Santino Im, Hector Lugo

---

### Frontend Developer's

**Función:**
Implementación de:
- interfaz de usuario
- experiencia de usuario
- integración con APIs
- alineación con estándares de accesibilidad

Responsable de usabilidad, consistencia visual y accesibilidad.

**Candidatos Idóneos:** Leonardo Rodriguez, Emiliano Deyta

---

### QA / Testing Engineer

**Función:**
Diseña y ejecuta:
- pruebas unitarias
- pruebas de integración
- pruebas funcionales
- validación UAT

Responsable de calidad antes de producción.

**Candidatos Idóneos:** Ángel Montemayor, Erick Morales, Eder Cantero, Emiliano Delgadillo

---

## 1. Capacidad del Equipo

### 1.1 Capacidad Semanal

| Rol | Personas | Horas/día | Horas/semana |
|-----|----------|-----------|--------------|
| Backend/BD | 3 | 5-6h | 75-90h |
| Frontend | 3 | 5-6h | 75-90h |
| QA/Documentación | 3 | 5-6h | 75-90h |
| Lead (incluye doc) | 1 | 5-6h | 25-30h |
| **TOTAL** | **10** | - | **250-300h** |

### 1.2 Capacidad Total del Proyecto

- **Capacidad mínima:** 15 semanas × 250h = 3,750 horas
- **Capacidad máxima:** 15 semanas × 300h = 4,500 horas
- **Capacidad promedio:** 15 semanas × 275h = **4,125 horas disponibles**

### 1.3 Capacidad Individual por Persona

| Rol | Horas totales (15 semanas) |
|-----|----------------------------|
| Backend/BD (c/u) | 375-450h |
| Frontend (c/u) | 375-450h |
| QA/Doc (c/u) | 375-450h |
| Lead | 375-450h |

---

## 2. Estrategia del Proyecto

### 2.1 Prioridades

1. **Máximo esfuerzo:** Deuda técnica
2. **Mínimo necesario:** MVP a definir
3. **Entregables obligatorios:** Documentación según asignaciones de equipo
4. **Soporte continuo:** Testing en paralelo

### 2.2 Deuda Técnica - Clasificación

**Crítica (Debe resolverse - 57h)**
- Auth endpoint upload: 15h
- Servicio Agencia de Viajes: 30h
- Sesión mock: 12h

**Media (Resolver si hay tiempo - 95h)**
- Logging estructurado: 25h
- Tests unitarios básicos: 40h
- Paginación: 30h

**Baja (No prioritaria - diferir)**
- Departamentos hardcodeados
- Protección CSRF completa
- Suite completa de tests
- Optimizaciones de performance

**Total deuda técnica máxima a abordar: 152h**

---

## 3. Estructura de Trabajo Breakdown (WBS)

### FASE 1: DEFINICIÓN Y ENTREGABLES INICIALES

**Duración:** Semana 1 (11-17 febrero 2026)
**Esfuerzo total:** 300 horas

**NOTA:** Todos los entregables de clase están programados para completarse en la Semana 1.

#### 1.1 Análisis Sistema Actual (120h)

| Actividad | Backend | Frontend | QA/Doc | Total |
|-----------|---------|----------|--------|-------|
| Estudio arquitectura y código | 40h | 40h | 40h | 120h |

**Detalle por equipo:**

**Backend/BD (40h):**
- Análisis arquitectura Express.js: 15h
- Estudio servicios existentes: 15h
- Revisión esquema BD (12 tablas + MongoDB): 10h

**Frontend (40h):**
- Análisis stack (Astro + React + TypeScript): 15h
- Estudio componentes reutilizables: 15h
- Mapeo de rutas y guards: 10h

**QA/Documentación (40h):**
- Mapeo flujos de negocio (7 etapas): 15h
- Análisis roles y permisos: 15h
- Documentación sistema actual: 10h

---

#### 1.2 Entregables Obligatorios de Clase (150h)

Todos estos entregables deben completarse en la Semana 1:

##### 1.2.1 Definición del Nombre, Misión, Visión y Valores (4h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Investigación y análisis organizacional | Lead + QA/Doc | 1h |
| Propuesta de identidad corporativa | Todo el equipo (workshop) | 2h |
| Redacción y refinamiento | Lead | 1h |

**Entregable:** Documento formal con identidad de la Oficina de Planeación de Proyectos

##### 1.2.2 Lista de Requerimientos V0.1 (30h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Levantamiento con cliente | Lead + 1 de cada equipo | 15h |
| Documentación requerimientos funcionales | Backend + Frontend | 10h |
| Documentación requerimientos no funcionales | QA/Doc | 5h |

**Entregable:** Documento con lista inicial de requerimientos del sistema

##### 1.2.3 Mapa de Arquitectura (Blueprint) (30h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Análisis arquitectura actual | Backend | 12h |
| Diseño arquitectura propuesta | Backend + Lead | 10h |
| Diagramas y documentación | Backend + QA/Doc | 8h |

**Entregable:** Diagrama de arquitectura del sistema (componentes, capas, tecnologías)

---

##### 1.2.4 Plan de Comunicación (20h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Definición de stakeholders | Lead | 6h |
| Estrategia de comunicación | Lead + QA/Doc | 8h |
| Herramientas y canales | Todo el equipo | 6h |

**Entregable:** Plan de comunicación del proyecto (interno y con cliente)

##### 1.2.5 Benthana (Plan de Riesgos) (20h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Identificación de riesgos | Todo el equipo (workshop) | 8h |
| Análisis y priorización | Lead | 6h |
| Planes de mitigación | Lead + Líderes técnicos | 6h |

**Entregable:** Documento de gestión de riesgos del proyecto

##### 1.2.6 Historias de Usuario (20h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Elaboración historias de usuario | Todo el equipo | 15h |
| Refinamiento y priorización | Lead + Cliente | 5h |

**Entregable:** Documento con historias de usuario en formato estándar

---

#### 1.3 Setup Proyecto (30h)

| Actividad | Responsable | Horas |
|-----------|-------------|-------|
| Ambientes de desarrollo | Backend/BD | 10h |
| Estructura repositorio para nuevos módulos | Frontend | 8h |
| Plan de pruebas base | QA | 7h |
| Plantillas documentación | Lead + QA | 5h |

**Resumen Semana 1:**
- Análisis sistema actual: 120h
- Entregables de clase: 150h
- Setup proyecto: 30h
- **Total Semana 1: 300h**

---

### FASE 2: DEUDA TÉCNICA CRÍTICA

**Duración:** Semanas 2-3
**Esfuerzo total:** 240 horas

#### 2.1 Backend (90h de 150h disponibles)

| Tarea | Esfuerzo | Detalle |
|-------|----------|---------|
| Auth endpoint upload | 20h | Middleware (12h) + Tests (8h) |
| Servicio Agencia de Viajes | 40h | Lógica mínima (25h) + Integración (15h) |
| Sesión mock | 15h | Solución producción |
| Preparación infraestructura | 15h | Setup base para nuevos módulos |

**Total Backend Fase 2: 90h**

#### 2.2 Frontend (70h de 150h disponibles)

| Tarea | Esfuerzo | Detalle |
|-------|----------|---------|
| Componentes base reutilizables | 40h | Forms genéricos (20h) + Tablas (20h) |
| Paginación básica | 30h | Solo vistas críticas |

**Total Frontend Fase 2: 70h**

**Tiempo restante (80h):** Setup estructura para nuevos módulos

#### 2.3 QA/Documentación (80h de 200h disponibles)

| Tarea | Esfuerzo | Detalle |
|-------|----------|---------|
| Tests regresión críticos | 40h | Solo flujos que nuevos módulos usarán |
| Documentación técnica base | 40h | Guía desarrollo (20h) + Estándares (20h) |

**Total QA/Doc Fase 2: 80h**

**Tiempo restante (120h):** Preparación testing para nuevos módulos

---

### FASE 3: DESARROLLO DE NUEVOS MÓDULOS

**Duración:** Semanas 4-12 (9 semanas)
**Esfuerzo total:** 2,700 horas

**NOTA:** El alcance específico de cada módulo se definirá con el socio formador, aún no se tiene la fecha. Las estimaciones siguientes son plantillas base que se ajustarán según la complejidad real.

#### 3.1 Tipología de Módulos (Estimaciones Base)

##### Tipo A: Módulo Simple (600-800h total)

**Características:** CRUD básico, sin flujos complejos, pocas validaciones

| Componente | Esfuerzo Estimado |
|------------|-------------------|
| Backend/BD | 200-250h |
| Frontend | 250-300h |
| QA/Documentación | 150-250h |

**Ejemplos típicos:** Catálogos administrativos, Reportes de consulta, Dashboards informativos

##### Tipo B: Módulo Medio (800-1,000h total)

**Características:** Flujo de trabajo, múltiples validaciones, estados

| Componente | Esfuerzo Estimado |
|------------|-------------------|
| Backend/BD | 250-300h |
| Frontend | 350-400h |
| QA/Documentación | 200-300h |

**Ejemplos típicos:** Procesos de aprobación, Módulos con workflow, Gestión con reglas de negocio

##### Tipo C: Módulo Complejo (1,000-1,200h total)

**Características:** Integración externa, lógica compleja, múltiples roles

| Componente | Esfuerzo Estimado |
|------------|-------------------|
| Backend/BD | 350-400h |
| Frontend | 400-500h |
| QA/Documentación | 250-300h |

**Ejemplos típicos:** Integraciones con sistemas externos, Motores de reglas, Workflows multi-nivel

---

#### 3.2 Desarrollo de 3 Módulos Principales

**Capacidad disponible:** 9 semanas × 300h = 2,700h

**Distribución propuesta (ajustable):** 3 módulos de tipo B (medio) = 900h cada uno

---

##### Módulo 1 (Semanas 4-7: 900h)

**Sprint 1 - Desarrollo Core (Semanas 4-5: 450h)**

| Equipo | Actividades | Horas |
|--------|-------------|-------|
| Backend/BD | Diseño modelo de datos y migraciones + Endpoints principales (CRUD) + Lógica de negocio core + Tests unitarios básicos | 150h |
| Frontend | Componentes principales + Formularios y validaciones + Integración con API + Navegación y rutas | 150h |
| QA/Doc | Plan de pruebas del módulo + Casos de prueba + Tests exploratorios + Documentación funcional + Manual de usuario borrador | 150h |

**Sprint 2 - Refinamiento y Cierre (Semanas 6-7: 450h)**

| Equipo | Actividades | Horas |
|--------|-------------|-------|
| Backend/BD | Endpoints secundarios + Validaciones y manejo de errores + Optimizaciones + Tests de integración | 150h |
| Frontend | Componentes secundarios + Estados y manejo de errores + Refinamiento UX/UI + Tests de componentes | 150h |
| QA/Doc | Ejecución de tests completos + Gestión de bugs y regresión + Documentación final + Videos tutoriales | 150h |

**Total Módulo 1: 900h**

---

##### Módulo 2 (Semanas 6-9: 900h)

**Estrategia:** Inicio en Semana 6 con overlap parcial

**Semanas 6-7:** Equipo dividido 50/50
- 50% finalizando Módulo 1
- 50% iniciando Módulo 2 (Sprint 1)

**Semanas 8-9:** Todo el equipo en Módulo 2 (Sprint 2)

Estructura idéntica a Módulo 1:
- Sprint 1 - Desarrollo Core: 450h
- Sprint 2 - Refinamiento: 450h

**Total Módulo 2: 900h**

##### Módulo 3 (Semanas 9-12: 900h)

**Semanas 9-10:** Sprint 1 - Desarrollo Core (450h)
**Semanas 11-12:** Sprint 2 - Refinamiento (450h)

Estructura idéntica a módulos anteriores

**Total Módulo 3: 900h**

---
