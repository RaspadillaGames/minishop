# MiniShop — Laboratorios

API REST para gestión de productos. Proyecto base para Labs 12, 13 y 14 del curso Construcción y Pruebas de Software.

## Requisitos
- Java 17+
- Maven 3.8+

## Ejecutar pruebas
```bash
mvn clean verify
```
Resultado esperado: `Tests run: 13, Failures: 0, Errors: 0`

## Estructura
```
src/main/java/com/tecsup/minishop/
├── controller/ProductController.java
├── service/ProductService.java
├── repository/ProductRepository.java
└── model/Product.java
```

## Endpoints
- `POST /api/products` — Crear producto
- `GET /api/products` — Listar todos
- `GET /api/products/{id}` — Buscar por ID
