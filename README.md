# api_yamdb

## Описание

Проект YaMDb собирает отзывы пользователей на различные произведения.

### Команда разработчиков

Софья Серпинская <https://github.com/sofyaserpinskaya>

Сергей Поляков <https://github.com/SergeyPolyakov87>

Динара Фатехова <https://github.com/Dinara-F>

### Технологии

Django 2.2.16

django-filter==21.1

djangorestframework 3.12.4

djangorestframework-simplejwt 5.0.0

### Установка

Запустить контейнеры и развернуть проект:

```bash
docker-compose up -d
```

### Загрузка данных в БД через Django ORM

Данные для загрузки в БД содержатся в файлах:
category.csv
comments.csv
genre_title.csv
genre.csv
review.csv
titles.csv
users.csv

Загрузка данных:

```bash
python3 manage.py fill_db
```

### Документация API-сервера

<http://51.250.21.86/redoc/>

### Админ

<http://51.250.21.86/admin/>

### API

<http://51.250.21.86/api/v1/>


[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Django-app workflow](https://github.com/Dinara-F/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)](https://github.com/Dinara-F/yamdb_final/actions/workflows/yamdb_workflow.yml)