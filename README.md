# Сайт для публикации и обсуждения статей
Это интерактивный сайт для публикации и обсуждения статей! Пользователи могут создавать статьи, комментировать их, а также регистрироваться для доступа к дополнительным функциям.

## Возможности

- **Добавление статей**: Пользователи могут публиковать новые статьи, заполняя форму с названием и содержанием статьи.
- **Комментирование статей**: После публикации статьи другие пользователи могут оставлять комментарии под ней.
- **Регистрация и аутентификация**: Пользователи могут регистрироваться на сайте, а затем входить, используя свои учетные данные.
- **Управление статьями и комментариями**: Авторы статей могут редактировать и удалять свои статьи, а также удалять комментарии к ним.
Начало работы:
- **Добавление статьи**: Перейдите в раздел “Новая статья” и заполните форму, указав название и содержание статьи. Нажмите “Опубликовать”, чтобы добавить статью на сайт.
- **Комментирование**: Под опубликованной статьей перейдите в раздел “Добавить комментарий”, заполните форму и нажмите “Отправить”, чтобы оставить комментарий.
- **Регистрация/Вход**: Перейдите в раздел “Регистрация” или “Вход” и заполните необходимые поля для создания учетной записи или входа на сайт.
- **Управление контентом**: Авторы могут редактировать или удалять свои статьи и комментарии в соответствующих разделах.


## Техническая информация:
- **Запуск сервера**: Выполните команду rails s в терминале для запуска сервера.
- **Запуск клиента**: Перейдите в директорию клиента с помощью cd ./client и запустите клиентское приложение командой npm run dev.
- **Запуск тестов**: Для запуска тестов используйте скрипт run_tests.sh, предварительно сделав его исполняемым командой chmod +x run_tests.sh.
- **Запуск в Docker**: Используйте команду docker compose up для запуска приложения в контейнерах Docker.

## Эндпоинты:
- /articles - список всех статей.
- /articles/{id} - детали конкретной статьи.
- /comments - список всех комментариев.
- /users - список всех пользователей.
- /sessions/new - страница входа.
- /users/new - страница регистрации.

Это приложение предоставляет базовый функционал для веб-сайта, на котором можно делиться и обсуждать статьи, а также взаимодействовать с другими пользователями. Оно идеально подходит для сообществ, где ценится обмен знаниями и мнениями.


Dependencies:
- Ruby 3.2.4
- Ruby Rails 7.1.3
- bcrypt 3.1.7
- bundler 2.5.10
- sqlite3
- Node.js 20.12.2


Install dependencies:
```bash
bundle install
```

Run the web server from IDE or from terminal with
```bash
rails server
```
