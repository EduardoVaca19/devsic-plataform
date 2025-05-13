# DevSync Platform

Plataforma distribuida para gestión ágil de proyectos.

## Servicios

- Auth Service: Autenticación de usuarios (Puerto 4000)
- Project Service: Gestión de proyectos (Puerto 4001)
- Task Service: Gestión de tareas (Puerto 4002)
- Notification Service: Envío de notificaciones (Puerto 4003)

## Base de datos

- PostgreSQL (Puerto 5432)

## Cómo levantar el proyecto

```bash
docker-compose up --build
