# Django Rest Framework: api backend

A simple api backend with a single endpoint exposing all todos.
api endpoint to get all todos: <http://127.0.0.1:8000/api/>
api endpoint to get a single todo: <http://127.0.0.1:8000/api/1/>

## Commands available: you should have pipenv install locally

```console
pipenv shell
pipenv sync

python manage.py makemigrations todos
python manage.py migrate

python manage.py runserver
```
