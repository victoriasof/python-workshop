# python-workshop

Learn the Basics: https://www.learnpython.org/

# Jupyter Notebook
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

Install Jupyter: https://jupyter.org/install

Run Jupyter: https://jupyter.readthedocs.io/en/latest/running.html#running

# Edabit 
Practice Python coding with fun, bite-sized challenges. 

Easy exercises: https://edabit.com/challenges/python3

https://github.com/victoriasof/python-jupyter-edabit

# Codility 

Prepare for tech interviews and develop your coding skills with hands-on programming lessons. Become a strong tech candidate online using Codility!

Difficult exercises: https://app.codility.com/programmers/lessons/1-iterations/


https://github.com/victoriasof/python-codility-lessons


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


$ sudo apt install python3-django


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


# Install Django 

How to install Django:
https://docs.djangoproject.com/en/3.1/topics/install/

Django poll app:
https://docs.djangoproject.com/en/3.1/intro/tutorial01/


How to create a simple Django web app with Python:

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


https://github.com/victoriasof/django-blog

