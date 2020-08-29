# django-pgsql-starter
Starter template for django application with postgresql server

* Uses Python 3.8 and Django 3.1
* Uses latest Postgresql in docker with latest pgadmin4
* Environment variables setup
* Dependency management with pipenv

## Using the template

* clone the repository
* install dependencies with ```pipenv shell``` and ```pipenv install```
* copy .env.example to .env and edit variables
* edit docker-compose.yml file to adjust database details. Use same database name as in your .env file
* start your database with ```sudo docker-compose up -d``` and your app with ```python manage.py migrate``` and ```python manage.py runserver```
