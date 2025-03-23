# smh-fastapi-backend-templates

## Overview
`smh-fastapi-backend-templates` is a CLI tool that enables seamless project scaffolding for FastAPI backend applications. It provides ready-to-use templates built with Poetry, ensuring an optimized development workflow with best practices and essential dependencies.

## Features
- **Python 3.12+ Support**: Ensures compatibility with the latest Python version.
- **Poetry-based Project Templates**: Each template is structured with Poetry for dependency and package management.
- **Automatic Environment Setup**: Installs dependencies via `poetry install` after template creation.
- **Dependency Management**: Comes pre-configured with FastAPI, SQLAlchemy, Pydantic, and more.
- **Automatic Poetry Installation**: If Poetry is not found, the CLI prompts for installation.
- **Interactive Template Selection**: Users can select from multiple available templates.
- **FastAPI Ready**: Optimized for building scalable FastAPI-based backend services.
- **Linting & Formatting**: Pre-configured with Ruff, Mypy, and Pre-commit hooks.

## Prerequisites
Ensure your system meets the following requirements:
- **Python 3.12+**
- **pip 25+**
- **Poetry** (Automatically installed if not found)

## Installation
You can install `smh-fastapi-backend-templates` via pip:
```sh
pip install smh-fastapi-backend-templates
```

## Usage
Once installed, you can access the CLI tool using the `smh-fastapi-backend-templates` command.

### List Available Templates
```sh
smh-fastapi-backend-templates list-templates
```

### Create a New Project
```sh
smh-fastapi-backend-templates create-project <project_name>
```
> **Note:** If no template is provided, an interactive prompt allows you to select one.

### Example Workflow
1. Install the package: `pip install smh-fastapi-backend-templates`
2. Run `smh-fastapi-backend-templates create-project my-fastapi-app`.
3. Choose a template from the list.
4. The project structure is created.
5. Dependencies are installed using `poetry install`.
6. Your FastAPI project is ready to use!

## Template Dependencies
Each template comes pre-installed with:
- **FastAPI** (with `standard` extras)
- **SQLAlchemy** for database management
- **Pydantic** for data validation
- **Alembic** for database migrations
- **Asyncpg & Psycopg2** for PostgreSQL integration
- **Httpx & Multipart Support** for async requests
- **Pre-commit, Mypy, Ruff** for code quality and linting
- **Nuitka** for optimized builds

## Contributing
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## License
Apache License 2.0. See [LICENSE](LICENSE) for details.

