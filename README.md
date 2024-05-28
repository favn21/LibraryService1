## LibraryServise

Этот проект представляет собой систему автоматизированного тестирования API для библиотечного сервиса. С помощью этой системы можно проводить тестирование различных API-методов, связанных с управлением авторами и книгами в библиотечном сервисе.

## О проекте

Проект разработан на языке Java с использованием фреймворка JUnit 5 для написания и запуска автоматических тестов. Для выполнения HTTP-запросов к API используется библиотека OkHttp. В проекте также используется библиотека Lombok для автоматической генерации геттеров, сеттеров и других стандартных методов.

## Структура проекта

- `src/main/java/com/example/api`: Исходный код приложения
    - `models`: Модели данных, используемые для представления запросов и ответов
    - `requests`: Клиенты для выполнения запросов к API
    - `responses`: Классы для валидации ответов от API
    - `exceptions`: Исключения, используемые для обработки ошибок при валидации ответов
- `src/test/java/com/example/api`: Тесты
    - `tests`: Набор автоматических тестов для API-методов

## Использование

1. Убедитесь, что у вас установлены Java Development Kit (JDK) и Maven.
2. Клонируйте репозиторий на свой локальный компьютер.
3. Откройте проект в IntelliJ IDEA или другой среде разработки.
4. Запустите тесты из директории. 
