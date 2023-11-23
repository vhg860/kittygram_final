# Проект Kittygram

[![Build Status](https://github.com/vhg860/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/vhg860/kittygram_final/actions)

Kittygram - это социальная сеть для обмена фотографиями любимых питомцев.

## Описание проекта

Этот проект представляет собой полностью функциональное приложение, состоящее из бэкенд-части, разработанной на Django, и фронтенд-части на React. В проекте использован стек технологий, включающий:

- **Backend**: Django, PostgreSQL (используется в качестве базы данных)
- **Frontend**: React
- **Сборка и развертывание**: Docker, GitHub Actions

## Развертывание проекта

Для развертывания проекта необходимо выполнить следующие шаги:

1. Клонировать репозиторий.
2. Заполнить файл `env` с необходимыми переменными окружения.
3. Выполнить развертывание с помощью команды `docker-compose up`.

## Заполнение файлов окружения (env)

Вам нужно создать файл `.env` и заполнить его следующими переменными окружения:

```dotenv
Настройки для подключения к базе данных PostgreSQL
POSTGRES_DB=kittygram
POSTGRES_USER=kittygram_user
POSTGRES_PASSWORD=kittygram_password
DB_NAME=kittygram
DB_PORT=5432
```
### Автор
[Дмитрий](https://github.com/vhg860)