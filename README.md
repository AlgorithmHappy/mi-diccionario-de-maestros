# Plataforma de Calificación de Profesores

Monorepo con backend (Kotlin + Spring Boot), frontend (HTML/CSS/JS), diseño (DBML/Penpot) y scraping (Python).

## Estructura
- `back_end_src/` — API REST con Spring Boot (Kotlin).
- `front_end_src/` — Frontend estático (HTML/CSS/JS).
- `back_end_design/` — Modelo DBML y documentación de API.
- `front_end_design/` — Diseño (Penpot): fuentes/exports.
- `scrap_src/` — Scraper en Python para poblar catálogos base.
- `docker/` — Ambiente que se levanta con Docker para desarrollar.

## Requisitos
- Java 17+ / Kotlin
- Gradle o Maven
- Python 3.10+ (recomendado)

## Config
- Variables de entorno: crea un archivo `.env` (no se versiona).
- Spring perfila `application-local.yml` (no se versiona).