Описание: 
Этот проект позволяет пользователям получать доступ через API к постам, группам, подписчикам, комментариям и прочему.
Создавать, удалять объекты, редактировать их по своему усмотрению
Установка:
Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/kiroshi1/api_final_yatube.git
cd api_final_yatube
Cоздать и активировать виртуальное окружение:

python -m venv env
venv/scripts/activate
Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:

python manage.py migrate
Запустить проект:

python manage.py runserver
