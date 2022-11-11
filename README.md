=======
# API для проекта YaTube
Описание:
Это API к проекту YaTube соцеальной сети с постами и групами, позволяет создавать посты(POST), редактировать их(PUT, PATCH) и остовлять коменты под ними, автор поста может его удалить(DELETE), так же можно подписываться на других участинков проекта, все это может делать залогиненный пользователь, анонимы могут только смотреть посты и коменты к ним.

# Технологии примененные в проекте:
- Код проекта написан на Python с преминением веб-фреймворка Django REST Framework.
- Используется база данных - SQLite
- Библиотеки Simple JWT(для работы с токенами) и django-filter(для филтрации запросов)

# Установка проекта:
1. Клонировать репозиторий и перейти в него
```
    git@github.com:Fiji-cosmo/api_final_yatube.git
    
    cd api_final_yatube
```
2. Развернуть виртуальное окружение и активировать его
```
  py -3.7 -m venv venv
  
  source venv/Scripts/activate
```
3. Установить зависимости
```
  pip install -r requirements.txt
```
4. Применить миграции
```
  python manage.py migrate
```
5. Запустить сервер
```
  python manage.py runserver
```
# Просмотр доступных эндпоинтов к API
<<<<<<< HEAD
Чтобы посмотреть все доступные эндпоинты перейдите в раздел документации при запущенном сервере. Она доступна по адрессу  http://127.0.0.1:8000/redoc/
=======
Чтобы посмотреть все доступные эндпоинты перейдите в раздел документации при запущенном сервере. Она доступна по адрессу  http://127.0.0.1:8000/redoc/
>>>>>>> 9338cefbd582ce2649ed4b00c270bfc28e27e820
