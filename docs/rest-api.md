# Diseño de Endpoints REST

## Descripción
La API REST permitirá la gestión de recursos del sistema mediante operaciones HTTP estándar.

## Endpoints principales

### GET /api/items
Obtiene la lista de elementos.
Respuesta:
{
  "success": true,
  "data": []
}

### POST /api/items
Crea un nuevo elemento.
Body:
{
  "name": "string",
  "description": "string"
}

### PUT /api/items/{id}
Actualiza un elemento existente.

### DELETE /api/items/{id}
Elimina un elemento del sistema.

## Decisiones técnicas
- Uso de arquitectura RESTful
- Respuestas en formato JSON
- Uso de códigos HTTP estándar

