WeatherForecastApiBlazorAppTestTask

Тестовое задание. Написать погодное веб-приложение на .Net Core (.net10, MediatR, Clean Architecture), Blazor Web App:

• Отобразить один экран с погодной информацией: текущая, почасовая (показывать оставшиеся часы из текущего дня и все часы следующего), прогноз погоды на 3 дня.

• Обработать показ загрузки и ошибку, если что-то пошло не так, с кнопкой повторного запроса

Геолокация и запросы:

• Геолокацию зафиксировать на использование города Москва

• Данные получать из запросов API:

http://api.weatherapi.com/v1/current.json?key=fa8b3df74d4042b9aa7135114252304&q=LAT,LON

http://api.weatherapi.com/v1/forecast.json?key=fa8b3df74d4042b9aa7135114252304&q=LAT,LON&days=3


Для выполнения задания back-end архитектура (проекты WeatherForecastApi.Domain, WeatherForecastApi.Application, WeatherForecastApi.Infrastructure) взяты из рекозитория
https://github.com/programmist2005/WeatherForecastApiTestTask
где реализуется абсолютно идентичная задача. Разница в решениях заключается в реализации front-end.
