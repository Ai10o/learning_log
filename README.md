# Learning Logs
## Описание проекта
Learning Logs — это проект, основанный на книге "Python Crash Course, 2nd Edition" автора Эрика Мэттиса. Это веб-приложение на Django, позволяющее пользователям вести журнал об их процессе обучения.

## Установка

1. Клонируйте репозиторий проекта:

   `https://github.com/Ai10o/learning_log.git`

2. Перейдите в каталог проекта

3. Установите необходимые зависимости:

   `pip install -r requirements.txt`

4. Выполните миграции для создания структуры базы данных:

   `python manage.py makemigrations`
   
   `python manage.py migrate`

6. Создайте суперпользователя для доступа к админ-панели:

   `python manage.py createsuperuser`

7. Запустите сервер разработки:

   `python manage.py runserver`
