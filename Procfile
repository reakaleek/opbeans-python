web: gunicorn -b 0.0.0.0:3000 opbeans.wsgi
tasks: celery -A opbeans -c 1 worker -l info
beat: celery -A opbeans beat -l info
