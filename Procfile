web: python manage.py collectstatic --no-input && python manage.py runserver 0.0.0.0:8080
migrate: python manage.py migrate
celery: celery -A config.celery_app worker -l INFO
celerybeat: celery -A config.celery_app beat -l INFO
