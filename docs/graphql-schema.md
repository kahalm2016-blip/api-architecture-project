# Definición de Esquema GraphQL

## Descripción
El esquema GraphQL define los tipos, consultas y mutaciones disponibles en el sistema.

## Tipos principales

type Item {
  id: ID!
  name: String!
  description: String
}

## Queries

type Query {
  getItems: [Item]
  getItem(id: ID!): Item
}

## Mutations

type Mutation {
  createItem(name: String!, description: String): Item
  updateItem(id: ID!, name: String, description: String): Item
  deleteItem(id: ID!): Boolean
}

## Decisiones técnicas
- Uso de tipado fuerte mediante GraphQL
- Separación clara entre Queries y Mutations
- Flexibilidad en consultas del cliente
