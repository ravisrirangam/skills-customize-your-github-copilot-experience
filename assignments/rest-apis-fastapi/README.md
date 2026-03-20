# 🚀 Building REST APIs with FastAPI framework

## 🎯 Objective
Build a RESTful API using FastAPI in Python, including endpoint routing, request validation, and response serialization.

## 📝 Tasks

### 🛠️ Setup FastAPI
#### Description
Create the FastAPI project environment and establish a simple app instance to confirm everything works.

#### Requirements
Completed program should:

- use `fastapi.FastAPI()` to create an app
- run with `uvicorn` (e.g., `uvicorn main:app --reload`)
- return a working response from a simple root endpoint (e.g., `/`)

### 🛠️ Implement CRUD endpoints
#### Description
Build a core set of API endpoints for a resource (such as `items`) with create, read, update, and delete operations.

#### Requirements
Completed program should:

- have an endpoint for creating a resource (`POST /items`)
- have an endpoint for reading resources (`GET /items`, `GET /items/{item_id}`)
- have an endpoint for updating a resource (`PUT /items/{item_id}`)
- have an endpoint for deleting a resource (`DELETE /items/{item_id}`)
- use path and JSON body parameters correctly

### 🛠️ Add validation and error handling
#### Description
Use Pydantic models to validate incoming data and return HTTP status codes for success and errors.

#### Requirements
Completed program should:

- define request/response models with `pydantic.BaseModel`
- validate input fields (e.g., required fields, field types)
- return `HTTPException` for invalid IDs or missing resources
- include JSON responses with status codes like 200, 201, 404

## 🧠 Skills practiced
- REST API design
- FastAPI framework and routing
- Pydantic data validation
- HTTP status handling and JSON responses
- basic API testing with curl or HTTP client tools
