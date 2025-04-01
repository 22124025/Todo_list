web: gunicorn todoapp.wsgi --log-file - 

web: python manage.py migrate && gunicorn todoapp.wsgi