# <a name="up" />Привет, меня зовут Мария!

---

### 👨‍💻 Обо мне:

Я начинающий тестировщик. Прошла обучение в школе тестировщиков Be-tester по направлениям "Тестирование ПО", "Основы автоматизации тестирования", "Продвинутый SQL". Также прошла [курс](https://stepik.org/course/245575/syllabus) от Артема Русова по направлению "Тестирование ПО с нуля. Практические тренажеры для тестировщика", в данном портфолио представлены работы этого курса.

- 📫 Как связаться со мной: Email - maria_budilova@mail.ru

--- 

[Проектирование тестов](#test-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Анализ требований и макета<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Тест-дизайн | Классы эквивалентности | Граничные значения<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Тестовая документация | Чек-листы | Тест-кейсы

[Тестирование веб-приложений](#web-testing)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Пользовательский интерфейс | DevTools <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Таблица принятия решений | Попарное тестирование | Баг-репорты

[Тестирование API](#api-testing)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;REST API | JSON | Postman

[Тестирование баз данных](#data-bases)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SQL 

## <a name="test-design" />Проектирование тестов

### Задание 1

<details>
	<summary>Анализ требований</summary>

***

**Задание**

Вам необходимо провести анализ требований модуля "Регистрация и Авторизация" для приложения "Интернет-магазин".

Для этого у вас есть готовые пользовательские истории и мокап приложения в [Figma](https://www.figma.com/file/2T99Jt5OHPqkhe4yyoe2IC/demoshopping.ru?type=design&mode=design&t=GvtQJUmNuwPVgjWr-1).

Список историй:

[ID1 Регистрация пользователя / User Registration](https://rusau.kaiten.ru/p/d/731b641b-545d-4311-a691-c397a21eb1bd)

[ID2 Вход в систему / User Login](https://rusau.kaiten.ru/p/d/1c04eafd-86f6-4a21-85cd-1fbf8d3be706)

[ID3 Выход из системы / User Logout](https://rusau.kaiten.ru/p/d/1f464f17-8de7-4f54-992c-11e9fa5fd646)

[ID4 Проверка авторизации перед доступом к функциональности / Authorization Check before Accessing Functionality](https://rusau.kaiten.ru/p/d/d440e1db-3645-48f3-8510-686704dcf09c)

**Решение** 

[Анализ требований](https://docs.google.com/spreadsheets/d/1j_OBBcDcKQQgYLwm1UZgPqp8EzMMx1IS-Uutwc0eEq0/edit?usp=sharing)

***

</details>

### Задание 2

<details>
	<summary>Классы эквивалентности и граничные значения</summary>

***

**Задание**

У вас есть [требование](https://rusau.kaiten.ru/p/d/731b641b-545d-4311-a691-c397a21eb1bd) с валидациями для полей "Логин" и "Пароль" на странице регистрации. Учитывайте, что оба поля принимают не просто буквы, а латиницу.

Заполните таблицу тестовыми данными для проверки этих полей с учетом создания классов эквивалентности и граничных значений.

**Решение**

[Эквивалентное разбиение](https://docs.google.com/spreadsheets/d/1B0Hdkaz2FKWbs435PKR2yiq5PGhbtG0X27Pb114hx2k/edit?usp=sharing)

***

</details>

### Задание 3

<details>
	<summary>Попарное тестирование</summary>

***

**Задание**

Создайте таблицу с исходными данными для попарного тестирования, включающую параметры и значения.
Сгенерировать тестовые данные для тестирования на основе алгоритма Pairwise.
Создайте таблицу с двумя вкладками: исходные данные и тестируемые значения после применения алгоритма.
Требования к [фильтрации](https://rusau.kaiten.ru/p/d/5b275ec1-e6df-47a4-9648-d422f4a387f3) и [сортировке](https://rusau.kaiten.ru/p/d/705e06d8-971f-4e0a-b8de-7e13befcc7a3).

**Решение**

[Попарное тестирование](https://docs.google.com/spreadsheets/d/1Ytciu3eC9pBRp_6dmtuvu61yl8VV0yGj9s-gil92JM8/edit?usp=sharing)

***

</details>

### Задание 4

<details>
	<summary>Таблица принятия решений</summary>

***

**Задание**

В нашем приложении есть модуль, включающий оплату через Paypal.

У аккаунта Paypal есть три статуса: valid, invalid и blocked, а также такая характеристика, как доступный баланс, который может быть нулевым и положительным (= достаточным для оплаты).

В случае, если статус карты valid, а баланс на аккаунте достаточный для покупки, пользователь может совершить покупку. Во всех остальных случаях транзакция будет отклонена.

Создайте таблицу, которая будет учитывать эти условия и выводить действие, согласно им.

**Решение**

[Таблица принятия решений](https://docs.google.com/spreadsheets/d/1RqhVCQK5SCDM03Y9MZDYoNsat9HAvfCPeksyRqidy7I/edit?usp=sharing)

***

</details>

### Задание 5

<details>
	<summary>Создание чек-листа</summary>

***

**Задание**

Напишите чек-лист, который будет включать тестирование для регистрации, авторизации и каталога.

[Макет](https://www.figma.com/file/2T99Jt5OHPqkhe4yyoe2IC/demoshopping.ru?type=design&mode=design&t=GvtQJUmNuwPVgjWr-1) 

[Само приложение](https://intern.demoshopping.ru/)

Список историй:

[ID1 Регистрация пользователя / User Registration](https://rusau.kaiten.ru/p/d/731b641b-545d-4311-a691-c397a21eb1bd)

[ID2 Вход в систему / User Login](https://rusau.kaiten.ru/p/d/1c04eafd-86f6-4a21-85cd-1fbf8d3be706)

[ID3 Выход из системы / User Logout](https://rusau.kaiten.ru/p/d/1f464f17-8de7-4f54-992c-11e9fa5fd646)

[ID4 Проверка авторизации перед доступом к функциональности / Authorization Check before Accessing Functionality](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID5 Просмотр списка товаров и деталей продукта / Viewing the product list and product details](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID6 Добавление товара в корзину / Adding a product to the cart](https://rusau.kaiten.ru/p/d/11290aff-1218-44c5-a195-f724931d6615)

[ID7 Фильтрация списка товаров / Filtering the product list](https://rusau.kaiten.ru/p/d/5b275ec1-e6df-47a4-9648-d422f4a387f3)

[ID8 Сортировка списка товаров / Sorting the product list](https://rusau.kaiten.ru/p/d/705e06d8-971f-4e0a-b8de-7e13befcc7a3)

**Решение**

[Чек-лист](https://docs.google.com/spreadsheets/d/1oip28Fwg4E2ejfH5dK5G-k_6oO22HPggfXAy5MzQ8yQ/edit?usp=sharing)

***

</details>

### Задание 6

<details>
	<summary>Создание тест-кейсов</summary>

***

**Задание**

Создайте не менее 10 тест-кейсов для регистрации, авторизации и каталога. Вам не нужно покрывать абсолютно все проверки из чек-листа, выберите самые основные и опишите их.
Заголовок тест-кейса должен быть понятным.
У каждого шага должен быть ожидаемый результат.

[Макет](https://www.figma.com/file/2T99Jt5OHPqkhe4yyoe2IC/demoshopping.ru?type=design&mode=design&t=GvtQJUmNuwPVgjWr-1) 

[Само приложение](https://intern.demoshopping.ru/)

Список историй:

[ID1 Регистрация пользователя / User Registration](https://rusau.kaiten.ru/p/d/731b641b-545d-4311-a691-c397a21eb1bd)

[ID2 Вход в систему / User Login](https://rusau.kaiten.ru/p/d/1c04eafd-86f6-4a21-85cd-1fbf8d3be706)

[ID3 Выход из системы / User Logout](https://rusau.kaiten.ru/p/d/1f464f17-8de7-4f54-992c-11e9fa5fd646)

[ID4 Проверка авторизации перед доступом к функциональности / Authorization Check before Accessing Functionality](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID5 Просмотр списка товаров и деталей продукта / Viewing the product list and product details](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID6 Добавление товара в корзину / Adding a product to the cart](https://rusau.kaiten.ru/p/d/11290aff-1218-44c5-a195-f724931d6615)

[ID7 Фильтрация списка товаров / Filtering the product list](https://rusau.kaiten.ru/p/d/5b275ec1-e6df-47a4-9648-d422f4a387f3)

[ID8 Сортировка списка товаров / Sorting the product list](https://rusau.kaiten.ru/p/d/705e06d8-971f-4e0a-b8de-7e13befcc7a3)

**Решение**

[Тест-кейс](https://drive.google.com/file/d/1moa8aYMykNHr2foZ330iOLWVvh5_Rhxp/view?usp=sharing)

***

</details>

### Задание 7

<details>
	<summary>Поиск багов</summary>

***

**Задание**

Создайте не менее 5 отчетов о дефекте по ходу выполнения тест-кейса. 

[Само приложение](https://intern.demoshopping.ru/)

Список историй:

[ID1 Регистрация пользователя / User Registration](https://rusau.kaiten.ru/p/d/731b641b-545d-4311-a691-c397a21eb1bd)

[ID2 Вход в систему / User Login](https://rusau.kaiten.ru/p/d/1c04eafd-86f6-4a21-85cd-1fbf8d3be706)

[ID3 Выход из системы / User Logout](https://rusau.kaiten.ru/p/d/1f464f17-8de7-4f54-992c-11e9fa5fd646)

[ID4 Проверка авторизации перед доступом к функциональности / Authorization Check before Accessing Functionality](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID5 Просмотр списка товаров и деталей продукта / Viewing the product list and product details](https://rusau.kaiten.ru/p/d/d49f0805-50b2-4b3e-b41c-524c0630b709)

[ID6 Добавление товара в корзину / Adding a product to the cart](https://rusau.kaiten.ru/p/d/11290aff-1218-44c5-a195-f724931d6615)

[ID7 Фильтрация списка товаров / Filtering the product list](https://rusau.kaiten.ru/p/d/5b275ec1-e6df-47a4-9648-d422f4a387f3)

[ID8 Сортировка списка товаров / Sorting the product list](https://rusau.kaiten.ru/p/d/705e06d8-971f-4e0a-b8de-7e13befcc7a3)

**Решение**

[Баг-репорты](https://drive.google.com/file/d/1Ax8Tf2JTrVIMGRX26TXbUJEhCMBbBrLY/view?usp=sharing)

***

</details>

[Наверх](#up)

## <a name="web-testing" />Тестирование веб-приложений

### Задание 1

<details>
	<summary>Создание простой веб-страницы</summary>

***

**Задание**

Создайте ваше первое портфолио со следующей структурой:

а. Ваше имя и фамилия

б. Фото

в. Название блока "Тестовые артефакты"

г. Содержимое блока: название домашнего задания и ссылка на гугл-диск c решением. У вас должен получиться список, состоящий из всех домашних заданий и решений к ним, которые вы уже выполнили на курсе

д. Контакты для связи

Создайте папку portfolio-html.
Верстка должна быть в файле index.html.
В названии вкладки в браузере должно фигурировать ваше имя и фамилия.
Дизайн, стиль, оформление вы выбираете сами и включаете его в файл styles.css.

**Решение**

[Веб-страница](https://drive.google.com/drive/folders/1fL4xYy6uJ8jo_Ei8r5S-9mhfpVknjV7M?usp=sharing)

***

</details>

### Задание 2

<details>
	<summary>Поиск багов в корзине</summary>

***

**Задание**

Вам нужно провести исследовательское тестирования корзины без требований в приложении "Интернет-магазин". Найти и задокументировать, как можно больше багов в нем.

[Само приложение](https://intern.demoshopping.ru/)

**Решение**

[Баги корзины](https://drive.google.com/file/d/1xeUgmIkq4Tf_SoWoesLqBcgQ_LOYxh5q/view?usp=sharing)

***

</details>

[Наверх](#up)

## <a name="api-testing" />Тестирование API

### Задание 1

<details>
	<summary>Создание REST-коллекции</summary>

***

**Задание**

Создайте свою первую коллекцию для "Интернет-магазин".

Для этого перейдите по ссылке и изучите [документацию](https://intern.demoshopping.ru/api-docs/) в Swagger. Вам нужны методы для Intern Server.

1. Скачайте Postman.
2. Создайте коллекцию "DemoShopping".
3. Создайте папку "Products" и "Cart"и оформите все методы, которые относятся к этим категориям в Swagger.
4. В методе PUT для обновления товара уберите из тела запроса id, иначе будет ошибка.
5. Создайте переменные окружения QA, которые будут часто переиспользоваться, например, базовый URL, token и ID. Подумайте, что еще можно добавить в них.
6. Для всех методов Products напишите автотесты, которые могут проверять: статус-код после отправки запроса (обязательный тест), проверки для тела (тип данных в значениях, изменение ключа и значения для POST и т.д.), время ответа и т.д.

**Решение**

[REST-коллекция](https://www.postman.com/maria-budilova/api/collection/pdv0czc/demoshopping?action=share&creator=43796401) 
***

</details>

[Наверх](#up)

## <a name="data-bases" />Тестирование баз данных

### Задание 1

<details>
	<summary>Запросы к базе данных SELECT</summary>

***

**Задание**

У приложения "Интернет-магазин" есть своя база данных, в которой хранится информация про пользователей, товары, корзину, заказы и платежные данные.

1. Установите MySQL Workbench или DBeaver.
2. Подключитесь к базе данных intern_shop.
3. Выполнить последовательно запросы, согласно [заданию](https://docs.google.com/spreadsheets/d/1sahNExAKv00oiTE3CHouxODt74p3uJcrBe4sp5Uml-Y/edit?usp=sharing), и разместить их в таблице

**Решение**

[Запросы к базе данных SELECT](https://docs.google.com/spreadsheets/d/1s4-vE95_Jgq5Gx1s-HOLgD_lZjoGd8e_kQVGz9hS_4Y/edit?usp=sharing)

***

</details>

### Задание 2

<details>
	<summary>Запросы к базе данных JOIN</summary>

***

**Задание**

Продолжаем работу с базой данный intern_shop, в которой хранится информация про пользователей, товары, корзину, заказы и платежные данные.

Создайте несколько заказов для вашего пользователя и оплатите их через GUI или API.
Подключитесь к базе данных intern_shop.
Выполните последовательно запросы, согласно [заданию](https://docs.google.com/spreadsheets/d/17PuUQblt4V3PJSS6BGajtH_4x4zOKD0lV7oQnxAUg-I/edit?usp=sharing), и разместить их в таблице.

**Решение**

[Запросы к базе данных JOIN](https://docs.google.com/spreadsheets/d/1Ti0xkFh7BayoDa7Tn-qZQh9438RVcshdO4o5DJZEnNg/edit?usp=sharing)

***

[Наверх](#up)
