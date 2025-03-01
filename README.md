---

# gRPC Currency Exchange Service 🌍💱

Этот репозиторий предоставляет gRPC сервис для обмена валют. Он позволяет получить курсы валют для всех поддерживаемых валют или курс для конкретной валюты.

## 📜 Протокол gRPC

Контракт сервиса описан в файле `currencyexchange.proto`, который включает два метода:

- **GetAllRates** — Получение курсов всех валют.
- **GetSpecificRate** — Получение курса для одной валюты.

## 🚀 Установка и запуск

1. Установите зависимости.
2. Запустите сервер.
3. Используйте gRPC для подключения к серверу и вызова методов.

## 🧑‍💻 Пример использования

Пример запросов для вызова методов сервиса:

- **GetAllRates** — Получение всех курсов валют.
- **GetSpecificRate** — Получение курса для одной валюты.
