# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build a REST API using the FastAPI framework. Students will practice defining routes, handling requests, and returning JSON responses.

## 📝 Tasks

### 🛠️	Create a Basic FastAPI App

#### Description
Set up a FastAPI application with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Define a GET route at `/` that returns a JSON welcome message
- Run successfully with `uvicorn`

### 🛠️	Add CRUD Endpoints

#### Description
Add endpoints to create, read, update, and delete items from an in-memory list.

#### Requirements
Completed program should:

- Define a Pydantic model for the item
- Implement `GET /items`, `POST /items`, `PUT /items/{id}`, and `DELETE /items/{id}`
- Return appropriate HTTP status codes for each operation
