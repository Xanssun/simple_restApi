# Movie API

Это простой RESTful API для управления коллекцией фильмов. API написан на Go с использованием роутера Gorilla Mux.
Он позволяет выполнять основные CRUD (Create, Read, Update, Delete) операции с фильмами.

## Возможности

- **Получение всех фильмов**: Возвращает список всех фильмов.
- **Получение одного фильма**: Возвращает детали конкретного фильма по его ID.
- **Создание фильма**: Добавляет новый фильм в коллекцию.
- **Обновление фильма**: Изменяет данные существующего фильма.
- **Удаление фильма**: Удаляет фильм из коллекции.

## Запуск сервера

Для запуска сервера выполните следующую команду:

```bash
go run main.go
