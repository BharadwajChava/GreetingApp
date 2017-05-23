# GreetingApp

Instructions to run the Project:
1. pip install -r requirements.txt
2. python manage.py makemigrations drchrono
3. python manage.py sqlmigrate drchrono 0001
4. python manage.py migrate
5. python manage.py runserver
Parallelly we should also run the rabbitmq-server and also run the
“celery -A drchrono worker --loglevel=info --beat”
