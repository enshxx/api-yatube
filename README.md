### Описание проекта:
Проект представляет собой API для обработки постов. API взаимодействует с постами, их комментариями, группами и подписками пользователей. К проекту подключена авторизация по JWT токену. Для того, чтобы узнать про все запросы к каждому эндпоинту -  можно перейти по эндпоинту /redoc/.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/enshxx/api-yatube
```

```
cd api_yatube
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
----
Полный список запросов к эндпоинтам можно найти в /redoc/
