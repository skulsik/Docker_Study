# Docker_Study

Запуск Python контейнера - 
docker run --network host -it python bash

Установка джанги - 
pip install django

Создание приложения - 
django-admin startproject app

Применение миграций - 
./manage.py migrate

Запуск сервера - 
./manage.py runserver

Запуск постгрес - 
docker run -e POSTGRES_PASSWORD=12345 -p 5432:5432 -v C:\Users\Skulsik\pg_data:/var/lib/postgresql/data postgres

Проверка существования контейнера - 
docker ps

Подключение к контейнеру - 
docker exec -it 46c24c2b6466 psql -U postgres
