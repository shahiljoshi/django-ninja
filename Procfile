web: gunicorn djninja.wsgi:application --log-file - --log-level debug
release: python manage.py makemigrations --noinput
release: python manage.py collectstatic --noinput
release: python manage.py migrate --noinput
