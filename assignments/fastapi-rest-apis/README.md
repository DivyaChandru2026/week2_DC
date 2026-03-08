# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple RESTful API using the FastAPI framework in Python by defining endpoints, handling requests, and returning JSON responses.

## 📝 Tasks

### 🛠️ Initialize FastAPI Project

#### Description
Set up a new Python project that uses FastAPI and Uvicorn.

#### Requirements
Completed project should:

- Install `fastapi` and `uvicorn` (e.g. in a `requirements.txt`)
- Create a main application file (e.g. `main.py`)
- Instantiate a `FastAPI` app object
- Be able to start the server with `uvicorn main:app --reload`

### 🛠️ Define API Endpoints

#### Description
Create routes for basic operations on a `Item` resource.

#### Requirements
Completed program should:

- Include a GET endpoint at `/items/` returning a list of sample items
- Include a GET endpoint at `/items/{item_id}` returning a single item by ID
- Use Pydantic models for request/response schemas
- Return JSON responses with appropriate data structures

### 🛠️ Implement CRUD Operations

#### Description
Add create, update and delete functionality for items.

#### Requirements
Completed program should:

- Provide a POST endpoint `/items/` to add a new item
- Provide a PUT or PATCH endpoint `/items/{item_id}` to modify an existing item
- Provide a DELETE endpoint `/items/{item_id}` to remove an item
- Handle errors (e.g. item not found) with proper HTTP status codes