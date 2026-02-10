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
