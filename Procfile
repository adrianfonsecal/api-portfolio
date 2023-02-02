web: gunicorn api_test:apicrud.wsgi --log-file -
release: python manage.py makemigrations --noinput
release: python manage.py migrate --noinput

