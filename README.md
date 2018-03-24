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

## Run server

start server on localhost and port 8000

```bash
$ cd myFirstWebSite
$ python3 manage.py runserver
```
