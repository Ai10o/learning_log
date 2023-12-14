# Learning Logs
## Описание проекта
Learning Logs — это проект, основанный на книге "Python Crash Course, 2nd Edition" автора Эрика Мэттиса. Это веб-приложение на Django, позволяющее пользователям вести журнал об их процессе обучения.

## Начальная настройка перед запуском
Перед запуском проекта необходимо выполнить следующие шаги:

1. Запустите виртуальное окружение:
source ll_env/bin/activate
2. Запустите сервер Django:
python manage.py runserver

## Основные компоненты
- **Модели (Models)** — это специальные классы Django, которые используются для представления данных.
- **Представления (Views)** — это специальные функции, обрабатывающие данные запроса пользователя и предоставляющие пользовательский интерфейс в браузере. Часто используется базовый шаблон для подготовки интерфейса для различных представлений.
- **Интерактивная оболочка (Interactive shell)** полезна для отладки в виртуальной среде: `python manage.py shell`.

## Создание виртуального окружения
1. Создайте виртуальное окружение `ll_env`, введя в терминале:
python3 -m venv ll_env

2. Активируйте виртуальное окружение (для Mac OS):
   На Windows: `ll_env/Scripts/activate`
   На MacOS и Linux: `source ll_env/bin/activate`
   
3. Для выхода из виртуального окружения введите `deactivate` в терминале или просто закройте терминал.

## Установка и настройка Django
1. Установка зависимостей
   
   Установим зависимости: `pip install -r requirements.txt`

2. Запуск сервера

   Запустим сервер: `python manage.py runserver`

