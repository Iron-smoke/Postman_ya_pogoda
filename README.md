Postman Collection: Yandex Weather API Testing (Тестирование Yandex Погоды)
English Version
Overview
This repository contains a Postman Collection of 12 requests designed to thoroughly test the functionality of the Yandex Weather API. These requests cover a wide range of API features, ensuring a complete and detailed examination of the service's capabilities.

The tests in this collection include requests for checking:

Current weather conditions
Weather forecasts for different time intervals (hours, days)
Multi-city weather queries
Historical weather data
Climate data for specific locations
Geolocation suggestions based on user input
Meteorological station data over a range of time
Forecasts for specific weather parameters at different altitudes (e.g., wind, temperature, cloudiness)
Precipitation type and probability
Collection Details
Number of Requests: 12
API: Yandex Weather API
Request Format: GraphQL and REST (where applicable)
Tests: Each request contains Postman tests to validate the correctness of responses, checking parameters like temperature, humidity, pressure, wind speed, and more.
Test Coverage: The collection ensures full coverage of the most critical functionalities of the API.
Tests Description
Get Current Weather by Coordinates

Purpose: Fetch current weather conditions based on latitude and longitude.
Tests: Validate temperature, cloudiness, wind speed, and direction.
Get Weather Forecast for Next 48 Hours

Purpose: Retrieve hourly forecast data for the next 48 hours.
Tests: Check temperature, humidity, and timestamp accuracy.
Multi-City Weather Forecast

Purpose: Fetch weather data for multiple cities in one request.
Tests: Validate weather conditions for London, Warsaw, and Berlin.
Historical Weather Data

Purpose: Retrieve historical weather information for a specific date range.
Tests: Verify temperature and precipitation records for accuracy.
Check Precipitation Forecast

Purpose: Test the type and strength of precipitation forecasts.
Tests: Validate rain/snow predictions.
Retrieve and Validate Meteorological Station Data

Purpose: Fetch real-time data from meteorological stations.
Tests: Validate station IDs, temperature, wind speed, and pressure readings.
... (Complete list of 12 requests)
API Key Setup
To use the Yandex Weather API, you must have a valid API key. Include your key in the Authorization header of each request:
'X-Yandex-Weather-Key': <your-api-key>
Russian Version (Русская Версия)
Обзор
Этот репозиторий содержит Postman Collection с 12 запросами, которые разработаны для всестороннего тестирования функционала API Яндекс Погоды. Эти запросы охватывают широкий спектр возможностей API, гарантируя полное и детализированное тестирование.

Тесты в коллекции включают запросы для проверки:

Текущих погодных условий
Прогнозов погоды на разные временные интервалы (часы, дни)
Погоды в нескольких городах
Исторических данных о погоде
Климатических данных для определенных мест
Предложения геолокации на основе ввода пользователя
Данных метеорологических станций за период времени
Прогнозов для конкретных погодных параметров на разных высотах (например, ветер, температура, облачность)
Вероятности осадков и типа осадков
Детали Коллекции
Количество Запросов: 12
API: Yandex Weather API
Формат Запросов: GraphQL и REST (где применимо)
Тесты: Каждый запрос содержит тесты в Postman для проверки правильности ответов, включая параметры температуры, влажности, давления, скорости ветра и другие.
Покрытие Тестов: Коллекция обеспечивает полное покрытие самых важных функций API.
Описание Тестов
Получение Текущей Погоды по Координатам

Цель: Получение текущих погодных условий на основе широты и долготы.
Тесты: Проверка температуры, облачности, скорости и направления ветра.
Получение Прогноза Погоды на Следующие 48 Часов

Цель: Получение почасового прогноза погоды на следующие 48 часов.
Тесты: Проверка температуры, влажности и точности временных меток.
Погода в Нескольких Городах

Цель: Получение погодных данных для нескольких городов в одном запросе.
Тесты: Проверка погодных условий для Лондона, Варшавы и Берлина.
Исторические Данные о Погоде

Цель: Получение исторической информации о погоде за указанный период.
Тесты: Проверка точности температуры и записей о осадках.
Проверка Прогноза Осадков

Цель: Проверка типа и силы осадков в прогнозе.
Тесты: Проверка предсказаний дождя/снега.
Получение и Проверка Данных Метеорологических Станций

Цель: Получение данных в реальном времени с метеорологических станций.
Тесты: Проверка ID станций, температуры, скорости ветра и данных о давлении.
... (Полный список из 12 запросов)
Настройка API Ключа
Чтобы использовать API Яндекс Погоды, необходимо иметь действительный API ключ. Добавьте ваш ключ в заголовок Authorization каждого запроса:
'X-Yandex-Weather-Key': <ваш-api-ключ>
