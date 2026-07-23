# Estructura del proyecto

Este proyecto es un monorepositorio que contiene un backend, un frontend,
la configuración de Docker y un pipeline de integración continua.

## Backend

El backend está desarrollado con FastAPI. Contiene los endpoints,
autenticación, lógica de la calculadora y pruebas automatizadas con pytest.

## Frontend

El frontend está desarrollado con React y TypeScript. Proporciona la interfaz
de la calculadora y se comunica con el backend mediante nginx.

## Docker

Docker Compose construye y ejecuta los contenedores del backend y frontend.

## Integración continua

GitHub Actions ejecuta automáticamente la construcción de los contenedores
y las pruebas del backend cuando se abre un Pull Request hacia main.
