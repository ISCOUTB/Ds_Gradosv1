# 🎓 Plataforma UTB — Estado de Grado y Gestión de Certificados  
Aplicación web desarrollada con **Oracle APEX**, diseñada para estudiantes y administradores de la Universidad Tecnológica de Bolívar (UTB).  
Permite consultar el avance académico, subir certificados obligatorios y administrar su aprobación.

---

##  Características principales

###  Para estudiantes
- Ver porcentaje de avance en el plan de estudios.
- Consultar el estado de cada certificado entregado.
- Subir certificados obligatorios:
  - Saber Pro  
  - Tesis  
  - Prácticas  
- Visualizar resumen académico:
  - Materias aprobadas  
  - Materias en curso  
  - Materias pendientes  

###  Para administradores
- Visualizar todos los certificados entregados.
- Aprobar o rechazar certificados desde un panel tipo “Cards”.
- Actualizar el estado del estudiante en tiempo real.

---

## Arquitectura del Proyecto

### **Frontend**
- Oracle APEX 24.x  
- Componentes:  
  - Cards  
  - Progress Meter  
  - Interactive Reports  
  - File Upload  
  - Dynamic Actions  

### **Backend**
- PL/SQL  
- Oracle Database 19c  
- Tablas principales:
  - `USUARIO`  
  - `MATERIA`  
  - `PLAN_ESTUDIOS`  
  - `PLAN_MATERIA`  
  - `MATERIA_ESTUDIANTE`  
  - `CERTIFICADO`  

---

##  Estructura del Repositorio
proyecto-utb
│
├─ f149984.zip # Exportación oficial de la app APEX
│
├─ database/
│ ├─ schema.sql # Tablas y relaciones
│ ├─ demo_data.sql # Datos de prueba
│
├─ screenshots/
│ ├─ dashboard.png # Capturas del dashboard
│ ├─ admin-panel.png # Panel del administrador
│
└─ README.md # Documentación del proyecto
