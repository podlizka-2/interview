# Interview
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
##  Предварительные требования
1. Установите [Docker](https://docs.docker.com/get-docker/)
2. Установите [Docker Compose](https://docs.docker.com/compose/install/)

## 🚀 Быстрый старт
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/podlizka-2/interview.git
   ```
2. Соберите и запустите контейнеры:
   ```bash
   docker-compose up --build
   ```
3. Приложение будет доступно по адресу:  
   http://localhost:8000

## 🛠 Команды управления
| Команда | Описание |
|---------|----------|
| `docker-compose up` | Запуск контейнеров |
| `docker-compose down` | Остановка контейнеров |
| `docker-compose logs -f` | Просмотр логов в реальном времени |
| `docker-compose exec web bash` | Доступ к контейнеру |

## 🔧 Устранение неполадок
Если возникают ошибки зависимостей:
```bash
docker-compose build --no-cache
```

Для применения миграций:
```bash
docker-compose exec web python manage.py migrate
```

## 🌐 Доступ к приложению
- Основное приложение: http://localhost:8000
- Админ-панель: http://localhost:8000/admin (создайте суперпользователя командой `docker-compose exec web python manage.py createsuperuser`)

