# Django

https://docs.djangoproject.com/en/2.1/intro/tutorial07/

## Links

http://192.168.99.100:8000/

## DB

- docker exec -it djangotutorial_db_1 bash
- psql -p 5432 postgres postgres
- python manage.py migrate
- python manage.py makemigrations polls
- python manage.py sqlmigrate polls 0001

## Commands

- docker-compose up --build
- docker exec -it djangotutorial_web_1 bash
- python manage.py shell
- python manage.py test polls

## Admin

- python manage.py createsuperuser