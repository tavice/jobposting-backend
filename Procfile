web: python manage.py runserver 0.0.0.0:$PORT
web: gunicorn <your_project_name>.wsgi --log-file - && python manage.py collectstatic --noinput

