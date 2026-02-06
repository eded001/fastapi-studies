# FastAPI Studies

## First steps

Before start a project, it's recommended create a virtual environment:

```bash
python -m venv .venv
```

And activate:

On Windows (PowerShell / CMD):

```bash
.venv\Scripts\Activate
```

On Linux/macOS:

```bash
source .venv/bin/activate
```

Installing:

```bash
pip install "fastapi[standard]"
```

## Running

After writing the code, run the server with:

```bash
fastapi dev main.py
```

And see the response on [localhost:8000](http://localhost:8000).

### Documentation

The API provides two automatic documentation interfaces based on the OpenAPI specification, generated natively by FastAPI.

#### `/doc` - Swagger UI

An interactive interface designed for exploring and testing the API.

**Key features:**

- Execute requests directly from the browserpip install 'uvicorn[standard]'


- Support for sending request bodies, headers, query parameters, and authentication

- Clear visualization of request and response schemas

- Ideal for developers during integration and debugging

**When to use:**

- Quickly test endpoints

- Validate payload structures

- Simulate authentication (JWT, OAuth2, etc.)

- Inspect real-time API responses

> [!NOTE]
> This is the hands-on tool for the technical team.

#### `/redoc` - ReDoc

An interface focused on reading and referencing the API documentation.

**Key features:**

- Clean and well-organized layout

- Sidebar navigation grouped by endpoint categories

- Schemas displayed in a structured and hierarchical format

- Better experience for in-depth reading

**When to use:**

- Sharing API documentation with other teams

- Presenting the API to partners or clients

- Reviewing data contracts (schemas) with clarity

> [!NOTE]
> This is the formal, presentation-ready version of the API documentation.
