# FastAPI CREATE APP

fastapi-create-app is a CLI tool for generating bare-bone FastAPI project.
When you run `fastapi-create-app [project_name]`, it generates the following project structure:

    .
    ├── app/
    │   ├── __init__.py
    │   ├── config/
    │   │   ├── __init__.py
    │   │   └── config.py
    │   ├── database/
    │   │   ├── __init__.py
    │   │   └── database.py
    │   ├── models/
    │   │   ├── __init__.py
    │   │   └── models.py
    │   ├── routers/
    │   │   ├── __init__.py
    │   │   └── routes.py
    │   ├── schemas/
    │   │   ├── __init__.py
    │   │   └── schemas.py
    │   └── services/
    │   │   ├── __init__.py
    │   │   └── services.py
    │   └── statics/
    │   └── templates/
    │   └── tests/
    │   │   ├── __init__.py
    │   │   └── tests.py
    │   └── utils/
    │       ├── __init__.py
    │       └── utils.py
    ├── Dockerfile
    ├── docker-compose.yaml
    ├── [project_name]_ven
    ├── .env
    ├── .gitignore
    ├── requirements.txt
    └── README.md

### INSTALLATION

`pip install fastapi-create-app`

### COMMAND

`fastapi-create-app [project_name]`

This command initialized an empty git repository, create a virtual environment using the python builtin `venv` by appending `_evv` to the project name, i.e `[project_name]_env`.

##### Activate the virtual environment before installing dependencies.

[view project on github](https://github.com/kenmoh/cli)
