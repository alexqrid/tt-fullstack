# Программа Frontend - 1 семестр

## 1. Вводное занятие 

- состав курса
- обзор современного фронтенда
- Подготовка структуры проекта
	- npm
	- базовая сборка (webpack)
- Создание Hello World приложения

## 2. Интенсив по js и api браузеров

- devtools
- html (форма и список сообщений)
- css (берем css-modules)
- es6, es2018
- dom, web components
- local/session storage
- обработка отправки формы, сохранение в storage

## 3. Интерфейсы “ввода”

Теория:
- event loop
- обработчики событий
- file, geolocation, payment, battery status, bluetooth
Практика:
- получение и кеширование геолокации
- загрузка файла и отрисовка preview

## 4. Взаимодействие с сервером

Теория:
- flow загрузки страницы, cors
- синхронные и асинхронные запросы
- отладка сетевых запросов
Практика:
- requirejs vs webpack loader (?)
- получение данных: XHR, fetch, Promises, jsonp

## 5. react

Теория:
- обзор фреймворков
- введение в react
- react devtools, create-react-app (публичный ui-kit)
Практика:
- перенос кода в jsx, разделение на компоненты
- дополнение конфигурации сборки
- отправка (получение) данных на сервер

## 6. SPA

Теория:
- spa, history api
- solid state
Практика:
- экран профиля
- настройка роутинга
- long-polling
- Интеграция с Server API

## 7. Построение сложного интерфейса пользователя

Теория:
- Best Practice использования React
- Паттерн Flux и Redux как реализация
Практика:
- Определение моделей и хранилищ проекта
- Реализация основных сценариев использования
- Обработка ошибок сервера

## 8. Авторизация в Web-приложениях

Теория:
- csrf, http-only cookies
- cors, csp
- js-api oauth-провайдеров
Практика:
- прикрутка OAuth от основных соцсетей
- прикрутка ombed

## 9. Доставка real-time сообщений

Теория:
- websocket
Практика:
- Простой сокет к dev-серверу
- Подключение к centrifugo со стороны клиента