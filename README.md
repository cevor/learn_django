# Django Framework

## Start Project

Run

    django-admin startproject learn_site

Project Files:

manage.py

- A command-line utility for executing Django commands from within your project.

asgi.py

- enables ASGI compatible web servers to serve your project.

settings.py

- contains the setting for your project.

urls.py

- contains project-level URL declarations. By default, this file contains a single URL pattern for the admin.

wsgi.py

- enables WSGI compatible web servers to serve your project.

## Create App in project

Run

    cd learn_site
    python manage.py startapp pages

## Add installed pages app in settings

To register our app with Django, we need to add it to the INSTALLED_APPS list in settings.py file.

add pages app

    'pages.apps.PagesConfig',

App files:

The migrations folder

- is where Django stores migrations, or changes to your database.

admin.py

- is where you register your models with the Django admin application.

apps.py

- is a configuration file common to all Django apps.

models.py

- is where the models for your app are located.

tests.py

- contains test procedures run when testing your app.

views.py

- is the location of the views for your app.

## Run Dev Server

    python manage.py runserver
