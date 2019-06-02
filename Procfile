web:python manage.py runserver
web: gunicorn -w 4 server:__init__
heroku ps:scale web=1