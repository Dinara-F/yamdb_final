# api_yamdb

## Description

YaMDb is an online service where everyone can leave their own review of a book, movie, music. Users can share their impressions and discuss the review in the comments.
The YaMDb project is evolving as a result of the creation of YaMDb_api. Through this interface, a mobile application or a chat bot will be able to work; through it it will be possible to transfer data to any application or to the frontend.

## Developers

- [Софья Серпинская](https://github.com/sofyaserpinskaya)

- [Сергей Поляков](https://github.com/SergeyPolyakov87)

- [Динара Фатехова](https://github.com/Dinara-F)

## Technologies
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Nginx](https://nginx.org/)
- [Gunicorn](https://gunicorn.org/)
- [Docker](https://www.docker.com/)
- [Yandex.Cloud](https://cloud.yandex.ru/)


### Installation

Run containers and deploy project:

```bash
docker-compose up -d
```

### Loading data into the database through Django ORM

category.csv
comments.csv
genre_title.csv
genre.csv
review.csv
titles.csv
users.csv

Loading data:

```bash
python3 manage.py fill_db
```

### API docs

<http://51.250.21.86/redoc/>

### Аdmin

<http://51.250.21.86/admin/>

### API

<http://51.250.21.86/api/v1/>


[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Django-app workflow](https://github.com/Dinara-F/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)](https://github.com/Dinara-F/yamdb_final/actions/workflows/yamdb_workflow.yml)
