web: daphne VideoStream.asgi:application --port $PORT --bind 0.0.0.0 -v2
worker: python manage.py runworker --settings=VideoStream.settings -v2