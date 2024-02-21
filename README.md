# Задание 1

**Valuator** - приложение помощник редактора.

Пользователь с помощью формы на главной странице отправляет текст на обработку, после чего перенаправляется на страницу _summary_, где видит результат обработки.

Приложение предоставляет следующие функции:

1. оценивает содержание;
2. проверяет похожесть на другие тексты.

Результат оценки содержания - число _rank_ в диапазоне [0..1], равное доле неалфавитных символов в тексте.
Алфавитными считаются символы строчных и прописных букв латинского и русского алфавитов.

Проверка на похожесть делается на основе поиска дубликата текста среди ранее обработанных.
Если найден дубликат, то _similarity_ = 1, иначе 0.

## Задание

Первое задание является ознакомительным. Прежде всего нужно ознакомиться с используемыми технологиями и инструментами:

- научиться создавать и запускать Web-приложение на фреймворке Asp.Net Core Pages,
- подключать к проекту Nuget библиотеки,
- запускать пошаговую отладку приложения в среде разработки.

В предоставленном шаблоне приложения необходимо:

1. Указать ваше имя и группу на странице About
2. Дописать недостающий код _(отмечен комментарием **//TODO**)_. В качестве хранилища использовать key-value хранилище Redis.

## Инструменты разработки и программные компоненты

1. ASP.NET Core 8.0, https://learn.microsoft.com/en-us/aspnet/core/getting-started/?view=aspnetcore-8.0
2. NoSQL база данных Redis, https://redis.io/
3. Рекомендуемые IDE: VS Code, Rider, Visual Studio
