## Create virtual environment
python -m  venv "<virtual environment name>"

## Setting execution policy to the current user
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

## Activate the virtual environment
<virtual environment name>\Scripts\Activate.ps1

## Upgrade pip
python -m pip install --upgrade pip

## Install Django in the virtual environment
pip install Django

## Creating Blank Django Project. 
django-admin startproject <project name> . 

## __init__.py in the project folder
__init__.py shows that the folder's files which are part of a Python package. We can't install files from another folder without this file.

## asgi.py in the project folder
asgi.py offers the option of running an Asynchronous Server Gateway Interface.

## settings.py in the project folder
settings.py manages the settings of the django project

## urls.py in the project folder
urls.py tells Django what pages to make when a browser or URL asks for them.

## wsgi.py in the project folder
wsgi.py stands for Web Server Gateway Interface. WSGI helps Django server our web pages.

## manage.py - 
The manage.py file is not a core component of the Django project, but it is used to run Django commands like starting the local web server or making a new app.
- Let's test our project using the light weight web server with Django for local devvelopment. The runserver command will be used. It can be found in the file manage.py
- Below command is used to run the server 
python manage.py runserver
- Once that runs we can test the server with 127.0.0.1/8000  or localhost/8000

# Creating a Blank App
Django uses apps and projects to keep code clean and easy and read. Multiple apps can be part of same Django project.
Each app will have a set of functions to control. For example, an e-commerce site, you may use on app to login users, another to handle payments, and another to list item details. That's three different apps that are all part of the same main project.

command - python manage.py startapp <app name>


