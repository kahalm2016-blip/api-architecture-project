# Diagrama de Arquitectura

## Descripción General
El sistema está diseñado siguiendo una arquitectura cliente-servidor, separando responsabilidades entre frontend, backend y base de datos.

## Componentes principales

1. Cliente (Frontend)
- Interfaz de usuario
- Realiza solicitudes HTTP o consultas GraphQL

2. Servidor (Backend)
- Maneja la lógica de negocio
- Expone endpoints REST
- Implementa esquema GraphQL

3. Base de Datos
- Almacena información persistente
- Gestiona entidades del sistema

## Flujo de datos

Cliente → API (REST/GraphQL) → Lógica de negocio → Base de datos → Respuesta al cliente

## Decisiones técnicas

- Separación de responsabilidades
- Arquitectura escalable
- Uso de estándares REST y GraphQL
