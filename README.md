Как запустить проект:
Клонируйте репозиторий:

git clone https://github.com/rodionbogoveev/api_final_yatube
Cоздайте и активируйте виртуальное окружение:

python -m venv venv
source venv/Scripts/activate
Установите зависимости из файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt
Выполните миграции:

python manage.py migrate
Запустите проект:

python manage.py runserver