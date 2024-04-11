## Blogicum

# Описание

Социальная сеть для публикации личных дневников. Сайт, на котором пользователь может создать свою страницу и публиковать на ней сообщения («посты»).

# Функционал сайта

- Для каждого поста существует категория — например «путешествия», «кулинария» или «python-разработка», а также опционально можно указать локацию, с которой связан пост.

- Пользователь может перейти на страницу любой категории и увидеть все посты, которые к ней относятся.

- Пользователи могут заходить на чужие страницы, читать и комментировать чужие посты.

- Для своей страницы автор может задать имя и уникальный адрес.

- Есть возможность модерировать записи и блокировать пользователей, рассылающих спам.

## Установка и запуск

Клонировать репозиторий:
```python
git clone <https or SSH URL>
```
Перейти в папку проекта:
```python
cd django_sprint1
```
Создать виртуальное окружение:
```python
python3 -m venv .venv
```
Активировать виртуальное окружение:
```python
source .venv/bin/activate
```
Установить библиотеки:
```python
pip install -r requirements.txt
```
Запустить сервер django:
```python
python3 manage.py runserver
```
Автор
[Timofey - Razborshchikov](https://github.com/Timofey3085)
