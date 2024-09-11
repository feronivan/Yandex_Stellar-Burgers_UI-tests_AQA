## UI-тесты для веб-приложения "Stellar Burgers". Проект по автоматизированному тестированию.
"Stellar Burgers" - сервис, которая позволяет заказать бургер в Stellar Burgers.

## Задачи:
Описать используемые элементы с помощью Page Object. 
Протестировать функциональность в Google Chrome и Яндекс.Браузере. 
Подключить Allure-отчёт.

<details>
<summary> Функциональность </summary> 
 
*Регистрация*
Проверить:
 - Успешную регистрацию.
 - Ошибку для некорректного пароля. Минимальный пароль — шесть символов.

*Вход*
Проверить:
 - вход по кнопке «Войти в аккаунт» на главной,
 - вход через кнопку «Личный кабинет»,
 - вход через кнопку в форме регистрации,
 - вход через кнопку в форме восстановления пароля.

*Переход в личный кабинет*
 - Проверить переход по клику на «Личный кабинет».
 - Переход из личного кабинета в конструктор.
 - Проверить переход по клику на «Конструктор» и на логотип Stellar Burgers.

*Выход из аккаунта*
 - Проверить выход по кнопке «Выйти» в личном кабинете.

*Раздел «Конструктор»*
Проверить, что работают переходы к разделам:
 - «Булки»,
 - «Соусы»,
 - «Начинки».
 - ***
</details>

## Проделанная работа:
- собран Maven-проект в IntelliJ IDEA с использованием Java 11 и подключением JUnit 4, Selenium, Allure, RestAssured;
- в автотестах проверены регистрация, авторизация, переход в личный кабинет, переход из личного кабинета на главную страницу, выход из аккаунта и конструктор на главной странице;
- тест написан для последних версий браузеров Google Chrome и Яндекс.Браузер;
- сгенерирован отчет с помощью Allure для упрощения анализа автотестов.
