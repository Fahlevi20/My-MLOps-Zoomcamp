# My-MLOps-Zoomcamp


- Learning about MLOps using Python and MLFlow

## Prepare installations:

windows
```bash
python -m venv .venv
.venv\Scripts\activate
pip install poetry
poetry install
```
ubuntu/wsl/linux
```bash
python -m venv .venv
source .venv/bin/activate
pip install poetry
poetry install
```

create database for mlflow and run in the terminal:

```bash
mlflow ui --backend-store-uri sqlite:///mlflow.db
```
click this link to access the MLFlow through your browser:
http://127.0.0.1:5000