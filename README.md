# ACTIVIDAD EN CLASE: CREACIÓN DE UN CRUD CON ENTITY FRAMEWORK

## SUSTENTADO POR
**Jerlyn Rodriguez**  
Matrícula: A00113235

## ASIGNATURA
**Desarrollo de Software con Tecnología Open Source**  
202610 ISO815-3173

## FACILITADOR
**Omar Reyes**

## OBJETIVO
Implementar un CRUD utilizando ASP.NET Core MVC, Entity Framework Core y SQL Server, aplicando operaciones básicas de persistencia de datos.

## DESCRIPCIÓN DEL PROYECTO
Este proyecto consiste en el desarrollo de un sistema CRUD para la gestión de estudiantes universitarios.  
El sistema permite realizar las siguientes operaciones:

- Crear estudiantes
- Listar estudiantes
- Editar información de estudiantes
- Eliminar estudiantes

Cada estudiante contiene los siguientes campos:
- Matrícula
- Nombre
- Apellido
- Carrera
- Correo electrónico

## TECNOLOGÍAS UTILIZADAS
- ASP.NET Core (.NET 9)
- Entity Framework Core
- SQL Server
- Patrón MVC
- Git y GitHub

## ESTRUCTURA DEL PROYECTO
- Models: Contiene el modelo Estudiante
- Data: Configuración del DbContext
- Controllers: Controlador EstudiantesController
- Views: Vistas Razor para el CRUD

## EJECUCIÓN DEL PROYECTO
1. Restaurar los paquetes NuGet
2. Ejecutar las migraciones:
