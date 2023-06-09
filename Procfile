web: python manage.py runserver 0.0.0.0:$PORT
web: gunicorn <job-posting>.wsgi --log-file - && python manage.py collectstatic --noinput
web: gunicorn job-posting.wsgi

