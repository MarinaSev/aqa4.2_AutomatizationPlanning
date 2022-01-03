# План # 
### Автоматизация тестирования сценария перехода к форме записи на обучение профессии "Тестировщик ПО" и заполнения этой формы. ###
***
**Цель** составления данного тест-пана: описание процесса тестирования возможности записи на обучение профессии "Тестировщик ПО".

## Перечень автоматизируемых сценариев ##

### Позитивные сценарии: ###
1.  Заполнение формы на странице профессии "Тестировщик ПО" валидными данными.
1.	Заполнение формы на странице профессии "Тестировщик ПО" валидными данными с промо-кодом.
1.	Переход к форме по кнопке «Записаться» с первого экрана страницы профессии "Тестировщик ПО" и заполнение формы валидными данными.
1.	Переход к форме по кнопке «Записаться» из блока «Гарантия возврата» страницы профессии "Тестировщик ПО" и заполнение формы валидными данными.
1.	Переход к странице профессии "Тестировщик ПО" со страницы Программирование -> выбор блока с профессией.
1.	Переход к странице профессии "Тестировщик ПО" со страницы Программирование с использованием фильтра.
1.	Переход к странице Программирование из блока «Изучайте актуальные темы» с главной страницы сайта «Нетология».
1.	Переход к странице Программирование из футера главной страницы сайта «Нетология».
1.	Переход к странице профессии "Тестировщик ПО" с главной страницы сайта «Нетология» через Каталог курсов -> Программирование -> Тестировщик ПО.
1.	Переход к странице профессии "Тестировщик ПО" с главной страницы сайта «Нетология» через Каталог курсов ->Полый каталог ->поиск по названию профессии.
1.  Переход к странице профессии "Тестировщик ПО" с главной страницы сайта «Нетология» через Каталог курсов ->Полый каталог с использованием фильтра.
1.	Переход к странице профессии "Тестировщик ПО" с главной страницы сайта «Нетология» из блока «Нео» -> выбор блока с профессией.
1.	Переход к странице профессии "Тестировщик ПО" с главной страницы сайта «Нетология» из блока «Нео» с использованием фильтра.

### Негативные сценарии: ###
1.	Отправка формы записи с пустыми полями.
1.	Отправка формы записи с пустым одним из полей.
1.	Отправка формы записи с именем, написанным иероглифами, арабской вязью, состоящим из одной буквы, из цифр или символов.
1.	Отправка формы записи с номером телефона без ‘+’, из 8 или 15 цифр.
1.	Отправка формы записи с email без ‘@’, ‘.’ или без ‘.ru’.
1.	Отправка формы записи с валидными данными и неверным промокодом.

## Перечень используемых инструментов ##
-	**Java 11** – один из самых популярных языков для веб-приложений. Востребован в сфере автоматизации тестирования. Им владеют тестировщики Компании. 11 версия – самая распространённая и стабильная для автоматизированного тестирования.
-	**IntelliJ IDEA** – самая популярная среда разработки в мире Java, предлагает эффективные встроенные инструменты, поддержку JavaScript и связанных с ним технологий, а также расширенную поддержку популярных фреймворков.
-	**JUnit Jupiter** – фреймворк, широко используемый для написания и запуска авто-тестов. Зарекомендовал себя в этой сфере. Им владеют большинство тестировщиков.
-	**Gradle** –система автоматической сборки. Необходима для управления JUnit, настройки приложения и тестирования.
-	**Selenide** – фреймворк для автоматизированного тестирования веб-приложений. Изящный API, поддержка Ajax для стабильных тестов, мощные селекторы, простая конфигурация.
-	**Git и Github** – проверенная система контроля версий. Для хранения кодов автотестов и настроек окружения, предоставления доступа к ним  с локальных маши сотрудников.
-	**Allure** – фреймворк, предназначенный для создания визуально наглядной картины выполнения тестов. Удобный механизм генерации отчётов.

## Перечень необходимых разрешений/данных/доступов ##
-	Разрешение на автоматизацию.
-	Доступ в тестовое приложение.
-	Данные для доступа в приложение.

## Перечень и описание возможных рисков при автоматизации ##
-	Проблемы с подключением окружения.
-	Ошибки в коде.
-	Проблемы на сервере.

## Перечень необходимых специалистов для автоматизации ##
Инженер по автоматизированному тестированию.  
Веб-разработчик.  
Аналитик или сотрудник, выполняющий функции аналитика.  

## Интервальная оценка с учётом рисков (в часах) ##
Подготовка и настройка технической части, окружения – 8 часов.   
Написание автотестов – 20 часов.   
Отладка автотестов - 5 часов.  
Составление баг-репортов – 6 часов.   
Аналитика и отчетность - 4 часа.  
**Итого: 43 часа**

