<div align="center">

# Task Management API

**Learn FastAPI by building something useful.**

From an in-memory prototype to a database-backed REST API.<br>
One small, well-understood step at a time.

[Getting started](#getting-started) · [Project layout](#project-layout)

</div>

---

## About the project

A hands-on learning project for building a task management service with Python and FastAPI. The focus is on understanding REST API development while keeping the design clean and easy to test.

> **Current stage: Project setup**
>
> The Python package and dependencies are in place. The FastAPI application and API endpoints are not implemented yet.

## The toolkit

| Tool | Purpose |
| --- | --- |
| **Python 3.12+** | Application language |
| **FastAPI** | REST API framework |
| **uv** | Python environment and dependency management |

## Getting started

### 1. Install the prerequisites

- Install **Python 3.12 or newer**. The project currently selects Python 3.12 through [`.python-version`](.python-version).
- Install **uv** using the [official installation guide](https://docs.astral.sh/uv/getting-started/installation/).
- Install **Git** to clone the repository.

### 2. Clone the project

```bash
git clone https://github.com/dev-rajeshsinha/task-management-api.git
cd task-management-api
```

### 3. Set up the environment

```bash
uv sync
```

This creates the local `.venv` environment and installs the project dependencies using the versions recorded in [`uv.lock`](uv.lock).

**Ready for development.** There is no API server to start yet; the FastAPI application will be added in a later step.

## Project layout

```text
task-management-api/
├── src/
│   └── task_management_api/
│       └── __init__.py      # Python package with a starter CLI function
├── .gitignore              # Files excluded from version control
├── .python-version         # Selected Python version
├── LICENSE                 # Project license
├── pyproject.toml          # Project metadata and dependencies
├── README.md               # Project overview and setup
└── uv.lock                 # Locked dependency versions
```

## License

See [LICENSE](LICENSE) for the project license.
