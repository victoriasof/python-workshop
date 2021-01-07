# python-workshop

Welcome to my workshop where I present the resources which I used to study Python and create a simple Django web app.

The Watch Presentation:
https://www.canva.com/design/DAEFuo6P3A8/1DEbcr6It_MohTO1JZ-4SA/view?utm_content=DAEFuo6P3A8&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton


# Learn the Basics

Python is a very simple language, and has a very straightforward syntax. Run through this introductory tutorial:

    Hello, World!
    Variables and Types
    Lists
    Basic Operators
    String Formatting
    Basic String Operations
    Conditions
    Loops
    Functions
    Classes and Objects
    Dictionaries
    Modules and Packages

https://www.learnpython.org/


##Python Data Types

https://www.w3schools.com/python/python_datatypes.asp

## Python Language Reference

This reference manual describes the syntax and “core semantics” of the language:

https://docs.python.org/3/reference/


# Jupyter Notebook

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

Install Jupyter: https://jupyter.org/install

Run Jupyter: https://jupyter.readthedocs.io/en/latest/running.html#running


# Edabit 

Practice Python coding with fun, bite-sized challenges:

Easy exercises: https://edabit.com/challenges/python3

Examples: https://github.com/victoriasof/python-jupyter-edabit


# Codility 

Codility is a software platform that helps technical recruiters run remote interviews. Develop your coding skills with hands-on programming lessons:

Difficult exercises: https://app.codility.com/programmers/lessons/1-iterations/

Examples: https://github.com/victoriasof/python-codility-lessons


# Install Python: 

https://realpython.com/installing-python/

Many Linux distributions come packaged with Python. To find out which version of Python you have, open a terminal window and try the following commands:

$ python --version

$ python2 --version

$ python3 --version


Python 3.8 doesn’t come by default on Ubuntu 18.04 and above. To install version 3.8, open a terminal application and type the following commands:

$ sudo apt-get update

$ sudo apt-get install python3.8 python3-pip

Once the installation is complete, you can run Python 3.8 with the python3.8 command and pip with the pip3 command.



# Install Visual Studio Code 

Install Visual Studio Code via Ubuntu Software


Getting Started with Python in VS Code: 

By using the Python extension, you make VS Code into a great lightweight Python IDE (which you may find a productive alternative to PyCharm).


Create a Python Hello World source code file

https://code.visualstudio.com/docs/python/python-tutorial?fbclid=IwAR0BcDnl7fFKbkbme8E5NEeN-03jWnogQcyVVbCYvdhWm6aOaZqO0bJWuDA


Using Python environments in VS Code:

To select a specific environment, use the Python: Select Interpreter command from the Command Palette (Ctrl+Shift+P).

https://code.visualstudio.com/docs/python/environments?fbclid=IwAR3ozSWpq0FxV0w1baD-8WY1Yo2Z0KIEVT2g2HfsmZ3KUXyHx9EAMZJnr2w


Django Tutorial in Visual Studio Code:

Django is a high-level Python framework designed for rapid, secure, and scalable web development. 

https://code.visualstudio.com/docs/python/tutorial-django


# Django Web framework 


How to install Django:

https://docs.djangoproject.com/en/3.1/topics/install/


Django poll app tutorial:

https://docs.djangoproject.com/en/3.1/intro/tutorial01/


# Basic steps to create a simple Django blog with Python:

    1. use django-admin to create project -> django-admin startproject myproject
    2. create app -> python3 manage.py startapp blog
    3. register app in settings.pys // settings.py line 40
    4. in main urls.py import path and include -> from django.urls import include, path
    5. convert admin route to this -> path('admin/', admin.site.urls),
    6. create urls.py inside my new app (blog) // copy the code from the docs
    7. import the newly created blog/urls.py inside the main urls.py using the include() function
    8. create the views that you declared inside the urls.py in your app folder
    9. run the command python3 manage.py migrate (creates some default Django settings inside your database)
    10. python3 manage.py runserver to run a development server and check our code


In blog folder, create folders:

- templates: add html files (layout.html can be the base from which the other html files will be extended)

- static: add images, bootstrap.min.css, bootstrap.min.js, style.css


Example: https://github.com/victoriasof/django-blog

Useful links:

Understanding MVC pattern in Django: https://medium.com/shecodeafrica/understanding-the-mvc-pattern-in-django-edda05b9f43f

Template inheritance: https://docs.djangoproject.com/en/3.1/ref/templates/language/

HTTP Response: https://docs.djangoproject.com/en/3.1/ref/request-response/

{% csrf_token %} : https://docs.djangoproject.com/en/3.1/ref/csrf/

Download bootstrap CSS and JS: https://getbootstrap.com/docs/4.5/getting-started/download/

django-secrets helps you to not commit your secrets to a repo: https://pypi.org/project/django-secrets/


