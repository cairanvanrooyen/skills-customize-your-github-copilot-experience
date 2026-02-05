# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a simple REST API using FastAPI that serves data with multiple endpoints, validates input, and returns clear responses.

## 📝 Tasks

### 🛠️ Create a Basic FastAPI Service

#### Description
Set up a FastAPI application and add a starter endpoint so you can run and test the server locally.

#### Requirements
Completed program should:

- Create a FastAPI app in a Python file (for example, `main.py`)
- Include one GET endpoint that returns a JSON welcome message
- Run locally with `uvicorn` and respond to requests in the browser or with `curl`


### 🛠️ Build CRUD Endpoints for a Resource

#### Description
Add endpoints for a single resource (for example, `books` or `tasks`) and support creating, reading, updating, and deleting items.

#### Requirements
Completed program should:

- Define a Pydantic model for request and response data
- Store data in memory using a list or dictionary
- Implement GET (list and single item), POST, PUT, and DELETE endpoints
- Return clear error messages for missing items or invalid input
