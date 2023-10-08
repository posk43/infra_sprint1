Kittygram

Описание проекта:

Проект Kittygram - социальная сеть, где вы можете обмениваться фотографиями котиков.

Стек технологий:

Python 3.9.16

node.js v18.17.1

backend: Django

frontend: React

nginx

gunicorn

Автор проекта:

Лиджиев Петр (github: posk43)

Как запустить проект:

Настройка бэкенд-приложения:


1. Клонировать репозиторий
git clone "адрес клонируемого репозитория"

3. Перейти в директорию бэкенда-приложения:

cd название_проекта/backend

3. Cоздать и активировать виртуальное окружение:

python3 -m venv env
Если у вас Linux/macOS

source env/bin/activate
Если у вас windows

source env/scripts/activate
 python3 -m pip install --upgrade pip

4. Установить зависимости из файла requirements.txt:

pip install -r requirements.txt



5. Выполнить миграции:

python3 manage.py migrate
Запустить проект:

python3 manage.py runserver

Настройка фронтенд-приложения:


1. Находясь в директории с фронтенд-приложением, установите ависимости для него:

npm i

2. Далее из этой же директории выполните команду:

npm run build
