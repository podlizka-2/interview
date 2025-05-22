# interview
## Описание: данный проект представляет собой статический сайт-визитку, созданный с использованием HTML, CSS
### Структура проекта 
```plaintext
/interview-1 
│├── myportfolio
│   ├── db.sqlite3
│   ├── main
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   ├── models.py
│   │   ├── __pycache__
│   │   ├── static
│   │   ├── templates
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── manage.py
│   └── myportfolio
│       ├── asgi.py
│       ├── __init__.py
│       ├── __pycache__
│       ├── settings.py
│       ├── urls.py
│       └── wsgi.py
└── README.md
```
### Запуск проекта.
### 1. Клонируйте репозиторий или скачайте архив с файлами.
```bash
git clone https://github.com/podlizka-2/interview.git 
```

### 2. Выполнить миграции.
```bash
python3 myportfolio/manage.py migrate 
```

### 3. Запустите локальный сервер (например, через VSCode или команду):
```bash
python3 myportfolio/manage.py runserver 
```

### 4. И перейдите по адресу: 
http://localhost:8000.

