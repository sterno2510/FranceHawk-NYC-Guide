# New York City Guide

## Submitted by:
- Brian Stern [Github profile](https://github.com/sterno2510/)
- Shameeka France [Github profile](https://github.com/yahighness)

## How to create a virtual environment for django

1. Create a directory you'll want your environment in.
    - Type the following commands into the terminal window
        -mkdir django-projects
        -cd django-projects
2. Inside the django-projects folder run the following command
    -python -m venv django-env


## Install Django

1. Inside the django-projects folder run the following command from the terminal.  You will see django getting installed in the terminal window.
    -pip install django 

2. Create a requirements.txt file in the django-projects folder with the following command from the terminal.
    - pip freeze > requirements.txt

## Enter the virtual environment

1. Inside the django-projects folder run the following command from the terminal.
    -For Windows Users
        -django-env\Scripts\activate
    -For Mac Users
        -source django-env/bin/activate

## Run the django server

1. Inside your project foler run the following command from the terminal.
    -python manage.py runserver