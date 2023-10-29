# Empty Flask Project


This guide outlines the essential steps for setting up the project:

1. Creating a virtual environment using `venv`.
2. Activating the virtual environment.
3. Installing project dependencies from `requirements.txt`.
4. Starting the Flask application.

You can adapt this guide to your specific project needs and provide additional information as required.

## Getting Started

To get started with this project, follow these steps:

## 1. Install Python Virtual Environment (venv)

Before you begin, make sure you have Python installed. If not, you can download and install Python from [python.org](https://www.python.org/downloads/).

To create a virtual environment, open a terminal and navigate to your project's directory. Run the following commands:

### Create a virtual environment
```bash
python -m venv venv
```
```bash
# On macOS/Linux
source venv/bin/activate
```
```bash
# On Windows
venv\Scripts\activate
```

## 2. Install Project Dependencies
```bash
pip install -r requirements.txt
```

## 3. Start the Flask Application
```bash
python run.py runserver
```

# Info
Save Project Dependencies to requirements.txt

If you install any new libraries or update existing ones during development, remember to update your requirements.txt file to keep a record of your project's dependencies. To do this, you can use the following command:

```bash
pip freeze > requirements.txt
```

# Pip Upgrade
```bash
pip install --upgrade pip
```