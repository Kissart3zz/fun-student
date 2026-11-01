# Student

Учёт студентов: Spring Boot, PostgreSQL, HTML, CSS и JavaScript.
Бэкенд основан на [fun-student](https://github.com/dorzhogun/fun-student).

## Запуск

С запущенным Docker Desktop:

```sh
docker compose up --build
```

Открыть http://localhost:8080.

Без Docker: Java 21, PostgreSQL, база `students_db`, логин и пароль `postgres`. Настройки в `src/main/resources/application.yml`. Запуск: `sh mvnw spring-boot:run`, на Windows — `mvnw.cmd spring-boot:run`.

## Учётные записи

| Логин | Пароль | Доступ |
| --- | --- | --- |
| admin@example.com | admin | Добавление, изменение контактов и удаление студентов |
| teacher@example.com | teacher | Просмотр студентов |
| superadmin@example.com | superAdmin | Управление пользователями и ролями |

Проверка тестов: `sh mvnw test`.
