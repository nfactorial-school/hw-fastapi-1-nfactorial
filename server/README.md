# server

Данная папка предназначена для следующих заданий:
- server-ping-pong
- server-request-info

> 💡 Необходимо чтобы задания были выполнены в данной папке.

## Запуск проекта

Установить зависимости:

```bash
poetry install
```

Войти в окружение poetry:

```bash
poetry shell
```

Запустить WSGI-сервер.

```bash
gunicorn main:app
```

После этого сервер запуститься на порту 8000. Чтобы проверить подключение сделайте запрос на [localhost:8000](http://localhost:8000).

```bash
curl localhost:8000

# Hello, World!
```
