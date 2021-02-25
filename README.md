
# Building a Django Back End

In this project, you will be building a back wnd with Django for your iTunes project from phase 1.

## Tasks
1. Follow the directions below for "Using This Template" to start a project from the Django Project Template.
2. 

# Django Project Template

This project was generated from the Momentum Django project template. This template sets up some minimal changes:
```
    django-extensions and django-debug-toolbar are both installed and set up.
    django-environ is set up and the DEBUG, SECRET_KEY, and DATABASES settings are set by this package.
    A starting Django app named core is provided.
    There is a custom user model defined in core.models.User.
    There is a templates/ and a static/ directory at the top level, both of which are set up to be used.
    A .gitignore file is provided.
    Pipenv is used to manage dependencies.
```

## Using this template

In an *empty directory*, run:
```py

django-admin startproject --template=https://github.com/momentumlearn/django-project-template/archive/main.zip --name=Pipfile project .
pipenv install
pipenv shell
cp project/.env.sample project/.env
./manage.py makemigrations
./manage.py migrate

```

**Replace `project` above with the name of your project.**
