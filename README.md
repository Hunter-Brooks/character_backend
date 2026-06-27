# character_backend

Minimal Spring Boot backend for a React frontend.

## Requirements

- Java 17
- Maven 3.9+

## Run locally

```bash
mvn spring-boot:run
```

The app starts on `http://localhost:8080`.

## API endpoints

- `GET /api/health` → `{"status":"UP"}`
- `GET /api/message` → starter response for the React frontend

## React development setup

By default, CORS is enabled for:

- `http://localhost:3000`
- `http://localhost:5173`

You can override that list with the `app.cors.allowed-origins` property.