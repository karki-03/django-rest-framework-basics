# django-rest-framework-basics

Django is based on <b>MVT (Model-View-Template)</b> architecture.

MVT Structure has the following three parts – 

<b>Model:</b> The model is going to act as the interface of your data. It is responsible for maintaining data. It is the logical data structure behind the entire application and is represented by a database (generally relational databases such as MySql, Postgres). 

<b>View:</b> The View is the user interface — what you see in your browser when you render a website. It is represented by HTML/CSS/Javascript and Jinja files. 

<b>Template:</b> A template consists of static parts of the desired HTML output as well as some special syntax describing how dynamic content will be inserted. 




# Setting up Virtual environment
1. pip install virtualenvwrapper-win
2. mk virtualenv custom_virtual_env_name

# To work inside a already created v. env.
3. workon custom_virtual_env_name

# Setting up django inside v. env.
4. pip install djangorestframework
5. pip install markdown       # Markdown support for the browsable API.
6. pip install django-filter  # Filtering support

# Creating new project
7. django-admin startproject mysite

# To make new apps inside the project
8. python manage.py startapp polls

# To run the server
9. python manage.py runserver


# Migrations
10. python manage.py makemigrations 

# Your models will be scanned and compared to the versions currently contained in your migration files, and then a new set of migrations will be written out. 
# Once you have your new migration files, you should apply them to your database to make sure they work as expected:

11. python manage.py migrate


# Resources

A. Resources for uploading a file:
https://blog.vivekshukla.xyz/uploading-file-using-api-django-rest-framework/

B. Resource for CRUD operation:
https://medium.com/swlh/django-rest-framework-crud-with-drf-9a8756095c73

C. Making OAuth2 setup using Django Oauth Toolkit (DOT)
https://django-oauth-toolkit.readthedocs.io/en/latest/getting_started.html                      

