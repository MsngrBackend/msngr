# Common commands

## Update all submodules to latest remote

`git submodule update --remote --merge`

## Update a specific submodule only

`git submodule update --remote --merge auth-service`

## Pull changes after someone else updated submodule pointers

`git submodule update --init --recursive`

## See which submodules have new commits available

`git submodule status`

## Реализованный функционал

| Функционал             | Сервис                 |
| ---------------------- | ---------------------- |
| Регистрация и вход     | AuthService            |
| Подтверждение email    | AuthService            |
| Управление сессиями    | AuthService            |
| Профиль пользователя   | ProfileService         |
| Редактирование профиля | ProfileService         |
| Аватары                | ProfileService + MinIO |
| Настройки приватности  | ProfileService         |
| Контакты               | ProfileService         |
| Избранные чаты         | ProfileService         |
| Чаты                   | MessageService         |
| Отправка сообщений     | MessageService         |

## Планируемый функционал

| Функционал                        | Заметки                                                                 |
| --------------------------------- | ----------------------------------------------------------------------- |
| Реакции на сообщения              |                                                                         |
| Удаление сообщений                | Доработать существующую реализацию — сейчас через REST, нужен WebSocket |
| Редактирование сообщений          | Доработать существующую реализацию — сейчас через REST, нужен WebSocket |
| Медиафайлы                        |                                                                         |
| Голосовые сообщения               |                                                                         |
