# Task 0 — Spring Boot Setup

## Intent

Create a minimal Spring Boot project that starts successfully.

This task is only about **bootstrapping the codebase**.  
No product logic is introduced here.

---

## Instructions

1. Go to **https://start.spring.io**
2. Create a new Spring Boot project with:
   - Project: Maven
   - Language: Java
   - Packaging: Jar
   - Java: LTS version
   - Dependencies:
     - Spring Web

3. Generate the project and open it in your IDE.
4. Run the application and ensure it starts successfully.

---

## Requirements

- The application must start without errors.
- No database configuration.
- No authentication.
- No domain models.
- No business logic.

---

## Optional (but recommended)

- Add a simple endpoint:
  - `GET /health` → returns `200 OK`
- Add a brief README with instructions to run the app.

---

## Explicit Non-Goals

Do **not** add:
- persistence
- security
- caching
- background jobs
- Docker
- CI/CD

Those will be introduced later when they are justified.

---

## Completion Criteria

This task is complete when:
- the application starts locally
- the codebase is clean and understandable
- every file present is intentional

---

> *If it runs, you’re done. Move on.*
