# Todo API

REST API для управления задачами.

## Стек
- Python 3
- Django 3.2+
- Django REST Framework
- django-filter
- SQLite

## Возможности
- CRUD задач с приоритетами и сроками
- Пагинация (10 записей на страницу)
- Фильтрация по статусу и приоритету
- Поиск по заголовку и описанию
- Сортировка по дате, приоритету, дедлайну

## Установка
```bash
git clone https://github.com/fivsky/todo-api.git
cd todo-api
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver