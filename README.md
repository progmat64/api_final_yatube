# Проект «API для Yatube»

### Описание

Реализована программная часть API для приложения «Yatube»

### Технологии

Python 3.9.10
Django==3.2.16

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Alexandr6400/api_final_yatube.git
```

```
cd yatube_api
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Автор

 [Александр](https://github.com/Alexandr6400)
