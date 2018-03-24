# Django_Setup

## Setting up Django

- clone Django repo
```bash
$ git clone https://github.com/django/django.git
```

This will create a folder called django

- install django package
```bash
$ pip3 install -e django/
```

To test django was installed:

```bash
$ ipython
```

```python
In [1]: import django
```

If you see this then it was a success:

```python
In [1]: import django

In [2]:
```

To exit ipython type quit and press the enter key:

```python
In [1]: import django

In [2]: quit
```

## Create a Django Project

call project myFirstWebSite

```bash
$ django-admin startproject myFirstWebSite
```

This will create the following file directory structure

```bash
myFirstWebSite/
    manage.py
    myFirstWebSite/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```

## Run server

start server on localhost and default port 8000

```bash
$ cd myFirstWebSite
$ python3 manage.py runserver
```
to check the server is working load localhost:8000

for custom port 8080

```bash
$ python3 manage.py runserver 8080
```

## Set up Hello World Text on app home page

create HelloWorld app

```bash
$ python3 manage.py startapp HelloWorld
```
This will create the following file directory structure

```bash
HelloWorld/
    migrations/
        __init__.py
        admin.py
        apps.py
        models.py
        tests.py
        views.py
```
