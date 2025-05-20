# Sistema de Registro Universitario - Backend

Proyecto Backend desarrollado en Java con Spring Boot para la gestión universitaria, que incluye módulos clave para el control de usuarios, estudiantes, materias e inscripciones.

---

## Descripción

Este proyecto implementa un sistema backend funcional para el Sistema de Registro Universitario con las siguientes características:

- Gestión de usuarios con login, registro, roles y seguridad mediante JWT.
- CRUD completo de estudiantes con validaciones.
- CRUD completo de materias, con asignación a docentes y validaciones.
- CRUD completo de inscripciones por estudiante, con validaciones.
- Manejo personalizado de excepciones.
- Documentación de API con Swagger.
- Conexión a base de datos PostgreSQL.
- Cacheo con Redis para mejorar el rendimiento.

---

## Módulos desarrollados

| Módulo                        | Estado         | Detalles                           |
|------------------------------|----------------|----------------------------------|
| Login, registro, JWT y roles | ✔️ Completado  | Seguridad con JWT y gestión de roles |
| CRUD de estudiantes          | ✔️ Completado  | Operaciones completas con validaciones |
| CRUD de materias             | ✔️ Completado  | Asignación de docentes y validaciones |
| CRUD de inscripciones        | ✔️ Completado  | Registro y validación de inscripciones |

---

## Tecnologías usadas

- Java 17
- Spring Boot 3.x
- Spring Security (JWT)
- JPA/Hibernate
- PostgreSQL
- Redis (Cache)
- Swagger (OpenAPI)
- Maven

---

## Características técnicas

- CRUD completo: Create, Read, Update, Delete (baja lógica o física según implementación).
- Validaciones mediante anotaciones estándar (`@NotNull`, `@Email`, `@Size`, etc.).
- Manejo global de excepciones con `@RestControllerAdvice`.
- Seguridad en endpoints mediante JWT.
- Cacheo con Redis para consultas frecuentes.
- Documentación automática con Swagger UI accesible en `/swagger-ui.html`.

---

