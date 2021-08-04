# djlocallibrary

Mozilla's locallibrary implementation in Django

Currently deployed with heroku at (https://shielded-basin-27912.herokuapp.com/)[https://shielded-basin-27912.herokuapp.com/]

## Get started

Download the code and move into main folder [djlocallibrary].

Create virtual env by using command

```
python3 -m venv env
cd env/bin/source/activate
```

Install the django

```
pip install django
```

Start server

```
python manage.py runserver
```

---

Other requirements (for heroku deployment):

`database-url & psycopg2` (PostgresSQL).
`whitenoise` (Static files).
`gunicorn` (WSGI web server).
