### Описание проекта api_final_yatube:

api_final_yatube - финальный учебный проект 8 спринта курса backend-разработки
Яндекс.Практикума

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/showcrack/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Документация:

Примеры обращений к эндпоинтам находятся по адресу:

```
http://127.0.0.1:8000/redoc/
```
