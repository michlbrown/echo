# Python App Template

A lightweight Python application template with opinionated defaults for development, testing, linting, and automation. Designed for fast setup and clean workflows using modern tooling.

## 🚀 Features

- 🐍 Python project with minimal boilerplate  
- ✨ [uv](https://github.com/astral-sh/uv) for fast dependency management  
- 🧪 [Pytest](https://docs.pytest.org/en/stable/) for testing  
- 🧹 [Ruff](https://docs.astral.sh/ruff/) for linting and formatting  
- 🪝 [Pre-commit](https://pre-commit.com/) hooks to enforce code quality


## 📦 Requirements

- Python 3.13+
- [uv](https://github.com/astral-sh/uv)  

## 🛠️ Setup 

1. Clone the repo 
```bash
git clone https://github.com/michlbrown/python-app-template.git
```
2. Install dependencies
```bash
cd python-app-template
uv sync
```
3. Setup pre-commit hooks
```bash
pre-commit install
```