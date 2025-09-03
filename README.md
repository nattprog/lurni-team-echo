# Welcome to Lurni.

Contents:

- [Virtual Environment and Dependancies](#virtual-environment-and-dependancies)
- [Run the Django App](#run-the-django-app)

---

## Virtual Environment and Dependancies

### Initialising virtual environment

`py -m venv .venv`

### Activating virtual environment

Git bash/Linux:

`source .venv/Scripts/activate`

Powershell:

`.venv\Scripts\activate`

### Installing dependancies

`pip install requirements.txt`

### Rewriting dependancies

`pip freeze > requirements.txt`

(warning: use with caution. When possible, add dependacies manually to requirements.txt)

## Run the Django App

`python manage.py runserver`
