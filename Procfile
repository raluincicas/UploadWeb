web:python manage.py runserver
web: gunicorn -w 4 server:app 
heroku ps:scale web=1