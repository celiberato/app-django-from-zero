# app-django-from-zero

mkdir app-from-zero

poetry init (install pytest / factory-boy)

poetry add django

poetry run django-admin startproject app_from_zero .

poetry run python manage.py startapp api

poetry run python manage.py migrate

poetry run python manage.py runserver
