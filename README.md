# Config Repository - Tasks Manager App

Este repositorio contiene los archivos de configuración centralizada para los microservicios de la aplicación Tasks Manager App.

## Estructura

- `auth-service.yml` – Configuración de base de datos, JWT, Eureka
- `user-service.yml`
- `task-service.yml`
- `notification-service.yml`
- `api-gateway.yml`
- `service-registry.yml`

## Uso

Este repositorio es consumido por el microservicio `config-server` vía Spring Cloud Config Server.
