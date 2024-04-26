## Описание приложения

Приложение представляет из себя веб-сайт интернет-магазина "Skillbox".

![Screenshot website](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website/assets/79922872/c793001f-0b3e-4a93-a847-c56e91b95f8d)

**В этом интернет-магазине реализованы:**
1. Формы авторизации, регистрации и восстановления пароля
2. Личный кабинет
3. Главная страница
4. Каталог товаров
5. Карточки товаров
6. Корзина
7. Оформление заказа
8. Оплата

## Версии тестовых стендов сайта интернет-магазина:

1. Первая версия сайта для первичного тестирования: для разработки сценариев тестирования и оценки трудозатрат [ссылка](https://intershop.skillbox.ru/)
2. [Вторая версия](https://intershop2.skillbox.ru/) - для тестирования форм регистрации и авторизации.
3. [Третья версия](https://intershop3.skillbox.ru/) - для тестирования через API, тестирования безопасности.
4. [Четвертая версия](https://intershop4.skillbox.ru/) - для тестирования UI, регрессионное тестирования после редизайна.
5. [Пятая версия](https://intershop5.skillbox.ru/) - итоговый тестовый стенд интернет-магазина.


## Документы:
1. Черновик аналитики (спецификации) для интернет-магазина. [ссылка на Notion](https://clear-bag-041.notion.site/59c95b381bff42c48bb8b9d2844d94b7)
2. [Исправленная версия аналитики (спецификации) для интернет-магазина](https://clear-bag-041.notion.site/Skillbox-a055fa1f369a4a1f8c2aa5e172025a6b)<br>
3. [Диаграмма состояний и переходов товара](https://app.diagrams.net/#G14acD3uKsXWy_RWQKkgi9TYB-ANPiYXxd#%7B%22pageId%22%3A%222YBvvXClWsGukQMizWep%22%7D)<br>
4. [Список сценариев для регрессионного тестирования с оценкой трудозатрат.](https://docs.google.com/spreadsheets/d/1d6gN8mm1BpPjtwRLP7G3FegSfSBXF46qepG-KPAJffg/edit?pli=1#gid=0)
5. [Методы API](https://clear-bag-041.notion.site/API-27127580e3e0418183d41540e68760a2)<br>
6. [Макет в Figma для тестирования UI](https://www.figma.com/file/dbKqwkD7bJhQyhTnjRSjJs/%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F?type=design&node-id=0-1&mode=design&t=zZV4lNX4kHMHn9dE-0)<br>
7. [Сценарии для приемочного тестирования](https://docs.google.com/spreadsheets/d/1OO51l74hWLtmj8rve0M9WUfzGDzVwcbrzggRNxl_1Z0/edit?pli=1#gid=0)
8. [Коллекция запросов Postman](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website/blob/main/Online_store_Skillbox-.postman_collection.json)

## Предустановленное ПО:

- [Postman](https://www.postman.com/)

## Задача:

**Комплексно протестировать сайт по следующим пунктам:**
1. Проверка требований спецификации. [задачи](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#1-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B0-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9-%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8)
2. [Тестирование формы регистрации и авторизации.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#2-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%84%D0%BE%D1%80%D0%BC%D1%8B-%D1%80%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-%D0%B0%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8)
3. [Исследование сайта, разработка диаграммы состояний и переходов товара.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#3-%D0%B8%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D1%81%D0%B0%D0%B9%D1%82%D0%B0-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%B4%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B-%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B9-%D0%B8-%D0%BF%D0%B5%D1%80%D0%B5%D1%85%D0%BE%D0%B4%D0%BE%D0%B2-%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%B0)
4. [Разработка сценариев тестирования и оценка трудозатрат.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#4-%D1%80%D0%B5%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B5%D0%B2-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B8-%D0%BE%D1%86%D0%B5%D0%BD%D0%BA%D0%B0-%D1%82%D1%80%D1%83%D0%B4%D0%BE%D0%B7%D0%B0%D1%82%D1%80%D0%B0%D1%82)
5. [Тестирование методом серого ящика черех API.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#5-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%BE%D0%BC-%D1%81%D0%B5%D1%80%D0%BE%D0%B3%D0%BE-%D1%8F%D1%89%D0%B8%D0%BA%D0%B0-%D1%87%D0%B5%D1%80%D0%B5%D1%85-api)
6. [Тестирование безопасности.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#6-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
7. [Тестирование UI.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#7-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-ui)
8. [Регрессионное тестирование.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#8-%D1%80%D0%B5%D0%B3%D1%80%D0%B5%D1%81%D1%81%D0%B8%D0%BE%D0%BD%D0%BD%D0%BE%D0%B5-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
9. [Составление приемочных сценариев.](https://github.com/Ekaterina-Isabel/Testing-an-online-store-website?tab=readme-ov-file#9-%D1%81%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%D0%BE%D1%87%D0%BD%D1%8B%D1%85-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B5%D0%B2)

## Результат тестирования: 

По результатам тестирования были созданы баг-репорты в YouTrack ([ссылка на YouTrack](https://ekaterinakuz.youtrack.cloud/agiles/159-2/current))

#### 1. Проверка требований спецификации

**Задача:**
1. Создать баг-трекер в [YouTrack](https://ekaterinakuz.youtrack.cloud/agiles/159-2/current).
2. Завести в нём карточку «Тестирование аналитики».
3. Проанализировать [черновик аналитики (спецификации) для интернет-магазина](https://clear-bag-041.notion.site/59c95b381bff42c48bb8b9d2844d94b7), найти баги.
4. Создать баг-репорты и прикрепить их к созданной карточке.
6. Сравнить черновик аналитики с [чистовиком](https://clear-bag-041.notion.site/Skillbox-a055fa1f369a4a1f8c2aa5e172025a6b), исправленные баги отметить выполненными в баг-трекере.

#### 2. Тестирование формы регистрации и авторизации

**Задача:**
1. Протестировать формы [авторизации](https://intershop2.skillbox.ru/my-account/) и [регистрации](https://intershop2.skillbox.ru/register/). Основной упор сделать на тестирование бизнес-логики: найти функциональные баги, не зависящие от браузеров.
2. Создать карточку «Тестирование формы регистрации и авторизации» в YouTrack.
3. Прикрепить к карточке найденные баги.


#### 3. Исследование сайта, разработка диаграммы состояний и переходов товара
  
**Задача:**
1. Создать диаграмму состояний и переходов (ДСП) по всему сервису в draw.io или другом инструменте. Представьте, что основная сущность или объект в интернет-магазине — это товар: его ищут, просматривают, добавляют в корзину, оплачивают.
2. Создать карточку в YouTrack и прикрепить в неё результат.

#### 4. Разработка сценариев регрессионного тестирования и оценка трудозатрат

**Задача:**
1. Скопировать [шаблон формы с регрессионными сценариями](https://docs.google.com/spreadsheets/d/1NRaUtCzDc0o8bxKRHMU5sWrWRDL1kT1tL7dX2-ZqsjI/edit#gid=0) и заполнить его:
- тесты должны охватывать всю функциональность, кроме формы авторизации и регистрации: поиск товара, каталог товара, карточку товара, корзину, оформление заказа и оплату, 
- прописать сценарии по шагам для [тестового стенда интернет-магазина](https://intershop.skillbox.ru/) (40–60 тестовых сценариев),
- сформировать ожидаемый результат максимально конкретно, 
- оценить трудозатраты (время выполнения теста достаточно округлять до минут).
2. Завести карточку в YouTrack, прикрепить к ней список сценариев.

#### 5. Тестирование методом серого ящика через API

**Задача:**
1. Протестировать функциональность «Остатки товара на складе» на [новом тестовом стенде](https://intershop3.skillbox.ru/)
2. Протестировать хранение данных на бэкенде, применяя API. Для работы с API используйте [документацию на все доступные методы API.](https://clear-bag-041.notion.site/API-27127580e3e0418183d41540e68760a2)
3. Завести найденные баги в YouTrack.

#### 6. Тестирование безопасности

**Задача:**
1. Протестировать [тестовый стенд](https://intershop3.skillbox.ru/) на уязвимости безопасности.
2. Завести все найденные баги в YouTrack в отдельной карточке. 

#### 7. Тестирование UI

**Задача:**
1. Протестировать UI [нового тестового стенда](https://intershop4.skillbox.ru/) по [прототипу (макету) в Figma](https://www.figma.com/file/dbKqwkD7bJhQyhTnjRSjJs/%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F?type=design&node-id=0-1&mode=design&t=cC4MNG2IfGd1ffxa-0) в браузерах Google Chrome и Firefox.
2. Завести найденные баги в YouTrack. Можно создать одну карточку на тестирование UI, но в теле бага обязательно указать браузер, где найден баг.

#### 8. Регрессионное тестирование

**Задача:**
1. Провести повторное тестирование по регрессионным сценариям [тестового стенда](https://intershop4.skillbox.ru/) после редизайна. При регрессе засечь время на прохождение каждого сценария.
2. Добавить найденные баги в карточку «Регресс интернет-магазина» в YouTrack.
3. Отметить в форме с регрессионными сценариями фактическое время теста.
4. Провести повторное тестирование багов функциональности формы регистрации и авторизации, остатков на складе. Исправленные баги пометить в трекере как сделанные.

#### 9. Составление приемочных сценариев

**Задача:**
1. Скопировать и заполнить [шаблон приёмочных тестов](https://docs.google.com/spreadsheets/d/1LYdHx8tvdDIQSzJLHM0mjdRGzhiNPJS-YHLE0kg4p6w/edit#gid=0). Составить сценарии на основе [аналитики](https://clear-bag-041.notion.site/Skillbox-a055fa1f369a4a1f8c2aa5e172025a6b). (от 20 до 50 штук)
2. Прикрепить приёмочные сценарии к задаче «Создание приёмочных тестов» в YouTrack.
