release: python manage.py migrate
web: daphne Djat.asgi:application --port $8000 --bind 0.0.0.0 -v2