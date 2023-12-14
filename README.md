# Learning Logs
## Описание проекта
Learning Logs — это проект, основанный на книге "Python Crash Course, 2nd Edition" автора Эрика Мэттиса. Это веб-приложение на Django, позволяющее пользователям вести журнал об их процессе обучения.

## Установка

1. Клонируйте репозиторий проекта:

   `https://github.com/Ai10o/learning_log.git`

2. Перейдите в каталог проекта
3. Создайте виртуальную среду для проекта:

   python -m venv venv

4. Активируйте виртуальную среду:

   Для Windows:
   `venv\Scripts\activate`
   
   Для macOS и Linux:
   `source venv/bin/activate`
   
5. Установите необходимые зависимости:

   `pip install -r requirements.txt`

6. Выполните миграции для создания структуры базы данных:

   `python manage.py makemigrations`
   
   `python manage.py migrate`

7. Создайте суперпользователя для доступа к админ-панели:

   `python manage.py createsuperuser`

8. Запустите сервер разработки:

   `python manage.py runserver`
