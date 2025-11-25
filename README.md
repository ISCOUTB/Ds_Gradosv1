# Ds_Gradosv1
prototipo, plataforma de gestión de requisitos de grados
Plataforma de Gestión de Requisitos de Grado (Oracle APEX)

Este repositorio contiene la exportación completa de la aplicación Oracle APEX desarrollada para gestionar certificados y entregas académicas (Saber Pro, Tesis y Prácticas), así como el seguimiento del progreso académico de los estudiantes.

--Contenido del repositorio
Archivo	Descripción
f149984.zip	Exportación completa de la aplicación APEX (ID 149984). Incluye páginas, procesos, autenticación, navegación y objetos de apoyo.

--Descripción funcional

La aplicación permite:

--Para estudiantes

Registrar la entrega de:

Certificados Saber Pro

Trabajo de grado (Tesis)

Prácticas profesionales

Subir archivos PDF como evidencia

Consultar el estado de cada entrega (pendiente, aprobada, rechazada)

Revisar el avance académico por semestre

Visualizar materias aprobadas, pendientes y en curso

Para administradores

Revisar entregas de estudiantes

Aprobar o rechazar documentos

Visualizar datos del estudiante asociados a cada entrega

Estructura de la base de dato
Tablas principales

USUARIO

id

nombre

correo

…

CERTIFICADO

id

tipo

fecha_entrega

archivo (BLOB)

autorizacion

estado

id_estudiante

MATERIA_ESTUDIANTE

id

id_estudiante

id_materia

estado

(Puedes añadir los scripts SQL en este repositorio si lo deseas)

Cómo importar la aplicación:

Inicia sesión en Oracle APEX.

Ve a App Builder → Import.

Selecciona f149984.zip.

Sigue el asistente de instalación.

Roles soportados:
Rol	Descripción:
Estudiante:	Realiza entregas y revisa su avance.
Administrador:	Revisa, aprueba y rechaza entregas.
Requisitos

Oracle APEX 22.x o superior

Oracle Database 19c o superior

Tablespace con soporte para BLOBs

📄 Licencia

Este proyecto puede usarse con fines educativos y de desarrollo interno.
