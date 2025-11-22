# Python Project Skeleton Template

## TL;DR

```sh
cookiecutter gh:deti/py-template && \
  cd $(ls -t | head -1) && \
  git init -b master && \
  git add . && \
  git commit -m "Initial commit from cookiecutter" && \
  make init
```

## ✨ Features

- ⚡ **uv** as environment + package manager
- 🔨**make** for automation
- 🧩 **src/**-based project structure
- ⚙️**pydantic_settings** for configuration management
- ✅ **pytest** for testing  
- 🧹 **ruff** for linting, formatting, and import sorting 
- 📁 Ready-to-use `pyproject.toml`  
- 🧪 Example test included  
- 📦 Clean, minimal, extensible


---

## 📦 Requirements

Before using the template, install:

- **Python 3.13**
- **uv** → https://github.com/astral-sh/uv
- **make**
