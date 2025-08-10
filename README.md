# REST API Project

## 📚 Overview
This Django project implements a simple REST API using **Django REST Framework** and **django-filter** (`v2.4.0` as required in the assignment).

The API provides CRUD functionality for a `Student` model with fields:
- `name`
- `email`
- `course`



## 🚀 Features
- Create, Read, Update, Delete (CRUD) students
- Filter students by `course`
- Search by `name` or `email`
- Order results by `id` or `name`
- Admin panel to manage records



## 📦 Technologies Used
- Python 3.x
- Django >= 3.0
- Django REST Framework
- django-filter == 2.4.0
- SQLite (default database)

## Folder
rest_api_project/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md
│
├── rest_api_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── api/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── serializers.py
    ├── views.py
    ├── urls.py
    ├── tests.py
    └── migrations/

## ▶️ How to Run the Project

1. **Install dependencies**  
```bash
pip install -r requirements.txt
