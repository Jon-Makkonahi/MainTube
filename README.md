# Учебный проект "MainTube"

MainTube - это социальную сеть для публикации личных дневников.

Это сайт, на котором можно создать свою страницу. 
Если на нее зайти, то можно посмотреть все записи автора.

Пользователи смогут заходить на чужие страницы, 
подписываться на авторов и комментировать их записи, также есть возможность подписыватся на автора.

+ Реализованы UNIT-тесты.

### Авторы:
- Daniil Bibikov (Jon-Makkonahi) https://github.com/Jon-Makkonahi

### Технологии:
- Python 
- Django
- PostreSQL
- SQLite(на текущий момент в GitHub)

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Jon-Makkonahi/maintube.git
```

```
cd maintube
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
