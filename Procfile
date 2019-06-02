web:python manage.py runserver
web: gunicorn -w 4 server.wsgi 
heroku ps:scale web=1