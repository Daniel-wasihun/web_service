# Elite Web Service

A high-performance, professional Java backend service built with Spring Boot 3.4 and Java 21.

## Features

- **Spring Boot 3.4.0**: Latest stable framework for robust application development.
- **Java 21**: Modern language features and performance.
- **H2 Database**: Lightweight, in-memory database for quick development (no Docker required).
- **Lombok**: Reduced boilerplate code.
- **RESTful API**: Clean and scalable API structure.

## Getting Started

### Prerequisites

- JDK 21
- Maven 3.9+

### Running Locally

```bash
mvn spring-boot:run
```

The application is configured to run on **port 8081**.
H2 Console is available at `http://localhost:8081/h2-console` (JDBC URL: `jdbc:h2:mem:web_service`).

## API Endpoints

### Students (CRUD)
- **Get All:** `GET http://localhost:8081/api/v1/students`
- **Get By ID:** `GET http://localhost:8081/api/v1/students/{id}`
- **Create:** `POST http://localhost:8081/api/v1/students`
- **Update:** `PUT http://localhost:8081/api/v1/students/{id}`
- **Delete:** `DELETE http://localhost:8081/api/v1/students/{id}`

## License

MIT
