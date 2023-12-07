Проект

В результате выполнения задачи будет разработан API backend на языке Python с использованием одной СУБД - PostgreSQL.

Регистрация и авторизация пользователей
CRUD механизм для создания, чтения, обновления и удаления привычек


Документация

К проекту подключен Redoc и Swagger 

Проект состоит из модели User, Role, Product, Category. Запуск проекта

Для запуска проекта необходимо выполнить следующие шаги:

1. Активировать виртуальное окружение для проекта.
2. Запустить файл main.py командой uvicorn src.main:app --reload
3. Проверить работоспособность API backend, отправив запросы на соответствующие эндпоинты.

Желаем приятного пользования и успехов в достижении целей!

Требования

FastApi

Шаги по запуску

Клонирование репозитория

git clone https://github.com/Vitaly-Dudkin/pythonProject
cd pythonProject

Настройка окружения Создайте файл .env_sample в корне проекта и укажите необходимые значения для переменных окружения. 

Запуск проекта

src.main:app --reload
