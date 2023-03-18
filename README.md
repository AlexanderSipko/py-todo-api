# API from simple todo app

  [deploy project](https://cloud.amvera.ru/projects/py-todo-api)

## Описание АПИ

Каждая заметка будет определяться следующим образом:

Все заметки будут храниться массивом в файле формата JSON.

`{
  "text": "Купить молоко",
  "done": true
}`

## API

GET /todo получает список всех TODO.
GET /todo/<id> получает TODO с заданным id (индексом в массиве).
POST /todo добавляет новую TODO в конец списка.
PUT /todo/<id> заменяет TODO с заданным id.
DELETE /todo?{object} удаляет запись TODO