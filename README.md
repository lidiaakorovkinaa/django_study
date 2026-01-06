Введение в Django. Страница приветствия

### Установка
1. Скопировать репозиторий:
```bash
git clone https://github.com/username/lidiaakorovkinaa/django_study.git
```

2. Установить зависимости:
```bash
pip install -r requirements.txt
```

3. Применить миграции:
```bash
python manage.py migrate
```

4. Создать виртуальное окружение
```bash
python -m venv venv
```

5. Запустить виртуальное окружение
```bash
source venv/bin/activate
```

6. Запустить сервер:
```bash
python manage.py runserver
```

7. Открыть http://127.0.0.1:8000/ в браузере

## Структура проекта
```
myproject/
├── manage.py
├── requirements.txt
└── myproject/
    ├── settings.py
    ├── urls.py
    ├── views.py
    └── wsgi.py
```
## Версия Python
Python 3.15.0a3

## Автор
Коровкина Лидия 2-МГЗ-2

