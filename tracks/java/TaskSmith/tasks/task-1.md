# Task 1 — Basic Todo (In-Memory)

## Intent

Introduce the first real feature of Tasksmith: a simple todo system.

This task focuses on:
- clean REST API design
- basic domain modeling
- separation of concerns

Persistence is **in-memory only**.

---

## Requirements

Implement CRUD operations for a todo item:

- Create a todo
- Retrieve a todo by ID
- List all todos
- Update a todo
- Delete a todo

A todo must have:
- unique identifier
- title
- optional description
- status (e.g. TODO, DONE)

---

## Constraints

- Use **in-memory storage** only  
  (e.g. a map or list held in memory)
- No database
- No files
- No users or authentication

Follow a basic layered structure:
- controller
- service
- storage (in-memory)

Do not expose internal models directly through the API.

---

## API Expectations

Design REST endpoints using standard HTTP semantics:
- appropriate methods (GET, POST, PUT, DELETE)
- meaningful status codes
- clear request and response bodies

Validation errors must return readable error responses.

---

## Explicit Non-Goals

Do **not** add:
- persistence
- notes
- attachments
- history
- dependencies
- sharing
- pagination
- sorting
- filtering

Keep it intentionally small.

---

## Expected Learning Outcomes

By completing this task, the developer should be able to:
- design a simple REST API
- model a small domain cleanly
- separate concerns inside a Spring Boot app
- explain how data flows through the system

---

## Completion Criteria

This task is complete when:
- all CRUD endpoints work correctly
- data is stored only in memory
- the application remains simple and readable
- the developer can explain the structure and decisions

---

> *This is the simplest version of the system. It will not stay simple.*
