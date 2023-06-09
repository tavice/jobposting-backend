web: python manage.py runserver 0.0.0.0:$PORT
web: gunicorn <backend>.wsgi --log-file - && python manage.py collectstatic --noinput

