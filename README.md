<h1>Как запустить проект:</h1>

Клонируйте репозиторий:

```python
git clone https://github.com/Lancelot-knight/api_final_yatube.git
```
Cоздайте и активируйте виртуальное окружение:

```python
python -m venv venv
```
```python
source venv/Scripts/activate
```
Установите зависимости из файла requirements.txt:

```python
python -m pip install --upgrade pip
```
```python
pip install -r requirements.txt
```
Выполните миграции:

```python
python manage.py migrate
```
Запустите проект:

```python
python manage.py runserver
```
