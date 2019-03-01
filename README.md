## Note

- docker build .
- docker-compose build
- docker-compose run app sh -c "django-admin.py startproject app ."
- docker-compose run app sh -c "python manage.py makemigrations core"
- docker-compose up
    - http://localhost:8000

- docker-compose run app sh -c "python manage.py createsuperuser"
