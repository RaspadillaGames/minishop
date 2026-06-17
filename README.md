# MiniShop REST API

![CI Pipeline](https://github.com/RaspadillaGames/minishop/actions/workflows/ci.yml/badge.svg)

API REST para gestión de productos. Proyecto base para Labs 12, 13 y 14.

## Ejecutar pruebas
```bash
mvn clean verify
```

## Endpoints
- `POST /api/products` — Crear producto
- `GET /api/products` — Listar todos
- `GET /api/products/{id}` — Buscar por ID