# 📦 mypythonlibrary
This README will act as a modular, pip-installable Python utility library for resuable data functions, configuration handling, and project automation. Built with clean packaging and versioning practices to support scalable development and deployment.

## 🚀 Installation
Installing the latest version directly from GitHub:

- **pip install git+https://github.com/KyleBoardwine/fibonacci**

Or install a specific version tag:

- **pip install git+https://github.com/KyleBoardwine/fibonacci@v1.0.0**

If you want to uninstall:

- **pip uninstall mypythonlibrary**

## 🧠 Features
- Reusable data processing and I/O utilities

- Config management with YAML/JSON

- Business logic functions

- Versioning with GitHub Releases

- Pip-compatible library structure

## 📁 Package Structure

mypythonlibrary/

├── __init__.py

├── config.py

├── data_utils.py

├── file_utils.py

├── logger.py

├── myfunctions.py

├── constants.py

setup.py

pyproject.toml

README.md


## 🏗️ Python Packaging Best Practices
- Use **pyporject.toml** to define build system and dependencies

- Add **__init__.py** to make directories importable

- Keep test cases in a separate **/tests ** folder

- Use semantic versioning via GitHub tags

- Use **.gitignore** to exclude files like **__pycache__/**, **.env**, and secrets

## 🔖 Versioning & Releases

**Create a New Release**

1. Commit your changes and push:

   git add .
   
   git commit -m "Add comment about commit"
   
   git push origin main
   
2. Tag a version:

    git tag v1.1.0
   
   git push origin v1.1.0
   
3. Create a release on GitHub
   
   Go to repo -> Releases -> "Draft a new release"

## 🔄 Working with Versions

**Install a Specific Version**

- pip install git+https://github.com/KyleBoardwine/fibonacci@v1.1.0

**Switch Local Code to a Version Branch**

- git checkout v1.1.0

- git checkout main

## 🧪 Development & Contributing
**Clone the repo:**

- git clone https://github.com/KyleBoardwine/fibonacci

- cd mypythonlibrary

**Create a virtual environment:**

- python -m venv venv

- source venv/Scripts/activate

**Install locally in editable mode:**

- pip install -e
