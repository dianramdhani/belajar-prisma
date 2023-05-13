# Belajar ORM Prisma

## Motivasi

Belajar untuk implementasi ORM dengan prisma.

Source: 
- https://www.prisma.io/docs/getting-started/quickstart
- https://www.prisma.io/docs/concepts/database-connectors/mongodb

@startuml
actor Programmer
participant CLI
participant Env
participant Schema
participant Index

Programmer -> CLI: Membuat project
Programmer -> CLI: Prisma init
Programmer -> Env: Update DATABASE_URL
Programmer -> Schema: Adjust datasource
Programmer -> Schema: Buat model
Programmer -> Index: Buat simple logic
@enduml