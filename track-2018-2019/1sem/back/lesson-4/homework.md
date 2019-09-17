## Домашнее задание 4

- Создать и запустить Flask проект, придерживаясь структуры проекта - 3
Собственно, нужно в папке app создать два файла: __init__.py и views.py. В __init__.py инициализируете приложение, читаете конфиг. Добавить instance/config.py в .gitignore. В конфиге config.py в корне сделать два класса для теста и продакшена.
- Реализовать "заглушки" для всех методов API, используя flask.jsonify - 4
В файле views.py сделать несколько методов --- получить списки чатов, список контактов, создать новый чат и т.д. Заглушка --- внутри метода сделать статический json, который будет возвращать метод (не забыть добавить status_code и mimetype).
- Обрабтывать только нужные методы (GET/POST) - 1
Для методов из views.py сделать обработку методов (GET/POST). Для вьюшек, которые обрабатывают оба метода сделать правильную обработку логики.
- Написать тесты (unittest) проверяющие работу views (достаточно проверить status_code, mimetype, содержимое ответа) - 3
Протестировать все созданные методы из views.py, проверить не только правильную работу методов, но и корректную обработку неправильных методов (например, посылаем GET запрос методу, принимающему только POST).