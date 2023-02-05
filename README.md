REST API социальной сети YaTube (Яндекс.Практикум)
=====

Описание проекта
----------
Проект создан в рамках учебного курса Яндекс.Практикум.

API сервис для проекта социальной сети Yatube.

Установка проекта из репозитория
----------

1. Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone https://github.com/KVGribko/api_final_yatube.git

cd api_final_yatube
```
2. Cоздать и активировать виртуальное окружение:
```bash
python -m venv venv

source venv/Scripts/activate
```
3. Установить зависимости из файла ```requirements.txt```:
```bash
python -m pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
cd yatube_api

python manage.py migrate
```
5. Запустить проект:
```bash
python manage.py runserver
```
Документация к проекту
----------
Документация для API доступна после запуска по адресу ```http://127.0.0.1:8000/redoc/```.
