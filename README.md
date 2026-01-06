Создание структуры приложения для блога с использованием шаблонов Django.
Ветка lab_2

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
blog/
├── manage.py
├── requirements.txt
├── blog/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── wsgi.py
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── about_page.html
│   ├── post_page.html
│   └── post_1.html, post_2.html, post_3.html
└── static/
    ├── css/style.css
    └── img/
```
## Версия Python
Python 3.15.0a3

## Автор
Коровкина Лидия 2-МГЗ-2

