# 🧪 Casos Prácticos y Soluciones - Base de Datos

¡Bienvenido a la sección de talleres prácticos! Esta carpeta contiene los enunciados de las prácticas asignadas y la documentación de sus respectivas soluciones. El objetivo de este módulo es aplicar los conceptos de modelado de datos, comandos DDL/DML, restricciones de integridad y administración de servidores en entornos de bases de datos relacionales (PostgreSQL / SQL Server).

---

## 🚀 Objetivos del Aprendizaje

*   **Diseño Físico:** Implementar diagramas entidad-relación directamente en código SQL estructurado.
*   **Refactorización Estructural:** Modificar esquemas de bases de datos en producción utilizando comandos `ALTER TABLE`.
*   **Gestión de Errores (Debugging):** Identificar, analizar y solucionar errores comunes de sintaxis, violaciones de claves ajenas (`FK`) y restricciones de verificación (`CHECK`).
*   **Seguridad y Vistas:** Crear capas de abstracción mediante vistas y gestionar privilegios de acceso para usuarios.

---

## 📋 Desglose de Prácticas

### [📄 Práctica 1: Gestión de Profesores y Alumnos](./practica1-profesores-alumnos.pdf)
*   **Foco:** Creación inicial de tablas, definición de tipos de datos, claves primarias (`PK`) y relaciones básicas.
*   **Evidencias de Solución:**
    *   [Practica 1- Table Editor.png](./Practicas%20soluciones/Practica%201-%20Table%20Editor.png): Estructura visual de las tablas creadas.
    *   [Practica 1-SQL Editor.png](./Practicas%20soluciones/Practica%201-SQL%20Editor.png): Script de inicialización ejecutado correctamente.

### [📄 Práctica 2: Sistema de Cursos](./practica2-cursos.pdf)
*   **Foco:** Inserción de datos e integridad referencial en relaciones N:M.
*   **Evidencias de Solución:**
    *   [Practica 2- SQL Editor.png](./Practicas%20soluciones/Practica%202-%20SQL%20Editor.png): Comandos de inserción y consultas de validación.
    *   [Practica 2- Error de la prueba 4.png](./Practicas%20soluciones/Practica%202-%20Error%20de%20la%20prueba%204.png): Análisis y corrección de un fallo de inserción por violación de restricciones.

### [📄 Práctica 3: Control de Matrículas](./practica3-matriculas.pdf)
*   **Foco:** Reglas de negocio complejas aplicadas a la matriculación de alumnos en diferentes períodos académicos.
*   **Evidencias de Solución:**
    *   [Practica 3 - SQL Editor.png](./Practicas%20soluciones/Practica%203%20-%20SQL%20Editor.png): Estructura de las tablas puente y queries de cruce.
    *   [Practica 3 - Error de la prueba 1.png](./Practicas%20soluciones/Practica%203%20-%20Error%20de%20la%20prueba%201.png): Captura del proceso de depuración de un error de clave duplicada o nula.

### [📄 Práctica 4: Aulas y Alteración de Tablas](./practica4-aulas-alter-table.pdf)
*   **Foco:** Modificación avanzada de esquemas en caliente empleando `ALTER TABLE`, agregando nuevas columnas, modificando restricciones y enlazando claves foráneas.
*   **Evidencias de Solución:**
    *   [Practica 4 - Tabla aula.png](./Practicas%20soluciones/Practica%204%20-%20Tabla%20aula.png): Creación de la nueva entidad.
    *   [Practica 4 - Clave ajena aula.png](./Practicas%20soluciones/Practica%204%20-%20Clave%20ajena%20aula.png): Vinculación exitosa de la relación entre tablas.
    *   [Practica 4 - Columna telefono_tutor.png](./Practicas%20soluciones/Practica%204%20-%20Columna%20telefono_tutor.png) y [Practica 4- Columna codigo_aula.png](./Practicas%20soluciones/Practica%204-%20Columna%20codigo_aula.png): Modificaciones de propiedades de columna.
    *   [Practica 4 - SQL Editor.png](./Practicas%20soluciones/Practica%204%20-%20SQL%20Editor.png): Historial de comandos DDL ejecutados.

### [📄 Práctica 5: Horarios y Control de Pagos](./practica5-horarios-pagos.pdf)
*   **Foco:** Control de flujos financieros e integridad temporal (evitar solapamiento de horarios y estados de pago).

### [📄 Práctica 6: Vistas y Permisos de Acceso](./practica6-vistas-permisos.pdf)
*   **Foco:** Seguridad y abstracción. Creación de vistas para enmascarar datos sensibles y comandos `GRANT` / `REVOKE` para la gestión de roles de usuario.

---

## 📂 Estructura de Soluciones Visuales

Las capturas con los resultados de los editores de código y el análisis de errores se encuentran centralizadas en la subcarpeta:
👉 **[Practicas soluciones/](./Practicas%20soluciones/)**

> 💡 **Nota de aprendizaje:** Los archivos marcados como `Error de la prueba...` son fundamentales en este portafolio, ya que documentan la capacidad de interpretar los mensajes del motor de la base de datos (DBMS) y corregir la lógica del script en tiempo real.
