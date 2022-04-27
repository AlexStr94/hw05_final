# Блог платформа YaTube

Учебный проект по созданию блог-платформы с открытой регистрацией на фреймворке Django (Python). На проекте может зарегистрироваться любой желающий, после регистрации доступна публикация постов и комментариев к своим и чужим постам. 

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/AlexStr94/hw05_final.git
```

```
cd hw05_final
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
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


