# py-django-firstapp

Simple app builded on python 3.6 with django.


### Build

- create venvfile 

```bash

 > mkdir first-app

 > cd first-app 

 > python -m venv venv

```

- venvfile - Win option

```bash

>  venv\Scripts\activate

```


- venvfile - Mac option

```bash

> source  venv/bin/activate

```

- install Django project

```bash

 > pip install Django

 > django-admin startproject public_python

 > cd public_python

 > python manage.py startapp main

```


### Commands

- start dev server

```bash

> python manage.py runserve

```

- test

```bash

> python manage.py test

```

- migrations

```bash

> python manage.py makemigrations

> python manage.py migrate

```

- superuser

```bash

> python manage.py createsuperuser

```

### Deploy project

- create virtualvenv

```bash

 > mkdir /usr/home/login/.virtualenvs

 > cd /usr/home/login/.virtualenvs

 > virtualenv django-app -p /usr/local/bin/python3.6

 > source /usr/home/login/.virtualenvs/django-app/bin/activate

```

- static files

```bash

 > python manage.py collectstatic

```


