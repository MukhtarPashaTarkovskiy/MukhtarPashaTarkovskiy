# 👋 Mukhtar-Pasha Tarkovskiy — QA Engineer

<img src="avatar.jpg" width="200" alt="Mukhtar-Pasha Tarkovskiy">

**Junior QA Engineer | Manual Testing · API Testing · UI Test Automation**

Занимаюсь функциональным тестированием веб- и мобильных приложений, проверкой REST API и разработкой автоматизированных тестов на Java.

Работаю с **REST Assured, Selenium WebDriver, Selenide, TestNG, JUnit 5, PostgreSQL, JDBC, Postman и Maven**.

В портфолио представлены проекты ручного и автоматизированного тестирования, тестовая документация, баг-репорты, API-коллекции и Java-приложения.

Разрабатываю собственное веб-приложение Task Manager и отдельный многомодульный проект его автоматизированного тестирования. Это позволяет работать с системой на уровнях **UI → REST API → бизнес-логика → база данных**.

---

## 🧰 Tech Stack

**Testing:** `Manual Testing` · `Functional Testing` · `Regression Testing` · `Web Testing` · `Mobile Testing` · `API Testing`

**Automation:** `Java 17` · `REST Assured` · `Selenium WebDriver` · `Selenide` · `TestNG` · `JUnit 5` · `Maven` · `Page Object Model` · `DataProvider`

**API & Security:** `REST API` · `HTTP` · `JSON` · `Postman` · `JSON Schema` · `Sessions` · `CSRF`

**Databases:** `PostgreSQL` · `MySQL` · `SQL` · `JDBC` · `Spring Data JPA` · `Hibernate`

**Test Documentation:** `Test Plans` · `Test Cases` · `Checklists` · `Test Data` · `Bug Reports` · `Test Matrix`

**Tools:** `Git` · `GitHub` · `GitHub Actions` · `Allure` · `Jira` · `TestRail` · `YouGile` · `DevTools` · `Charles Proxy` · `IntelliJ IDEA` · `DBeaver`

**Backend:** `Spring Boot` · `Spring Security` · `Thymeleaf` · `Docker` · `Render` · `Neon`

---

# 🚀 Featured Automation Projects

## 🧪 Task Manager — API & UI Test Automation

**Статус: завершённый проект портфолио**

Многомодульный Maven-проект автоматизированного тестирования собственного веб-приложения Task Manager.

Проект разделён на независимые модули `api-tests` и `ui-tests`, что позволяет развивать API- и UI-проверки в рамках единой тестовой архитектуры.

### ✅ Реализовано

- Автоматизация REST API с использованием REST Assured и TestNG.
- Проверки регистрации, авторизации и операций с задачами.
- Позитивные и негативные сценарии.
- Проверки HTTP-статусов, JSON-ответов и JSON Schema.
- Работа с HTTP-сессиями и CSRF-токенами.
- Проверка данных PostgreSQL через JDBC.
- Генерация уникальных тестовых данных и их автоматическая очистка.
- Тестовая документация: тест-план, тест-кейсы, тестовые данные и матрица.
- UI-проверки регистрации, входа и управления задачами с использованием Selenium и Page Object.

**CI:** GitHub Actions на Ubuntu 24.04, последовательные наборы API/UI Smoke и Regression, общий режим All и отчётность Allure. Автоматический All в `main` завершился с результатом **127 Passed, 0 Failed, 0 Skipped (100%)**. Это 127 выполнений и 117 уникальных вариантов. [Запуск №42644411463](https://github.com/MukhtarPashaTarkovskiy/task-manager-autotests/actions/runs/42644411463).

![Allure Combined-All — 127 Passed, 0 Failed, 0 Skipped, 100%](https://raw.githubusercontent.com/MukhtarPashaTarkovskiy/task-manager-autotests/main/docs/images/allure-overview-main-127-pass.png)

**Стек:** `Java 17` · `REST Assured` · `TestNG` · `Selenium WebDriver` · `PostgreSQL` · `JDBC` · `Maven` · `JSON Schema` · `Allure`

### 🔗 Проект

[🧪 Task Manager — репозиторий автотестов](https://github.com/MukhtarPashaTarkovskiy/task-manager-autotests)

[🌐 Открыть тестовое приложение](https://task-manager-test-588r.onrender.com)

---

## 🛒 SauceDemo — UI Test Automation

Проект автоматизации UI-тестирования учебного интернет-магазина SauceDemo.

Автотесты разработаны на Java с использованием Selenium WebDriver и TestNG. Применяется паттерн Page Object Model, параметризация через DataProvider и организация тестов по пользовательским сценариям.

### ✅ Реализовано

- Позитивные и негативные проверки авторизации.
- Параметризованные тесты с различными тестовыми пользователями.
- Проверки каталога товаров.
- Добавление товаров в корзину и проверка её содержимого.
- TestNG Listener и скриншоты при ошибках UI-тестов.
- Интеграция с Allure.
- Автоматический запуск тестов через GitHub Actions.
- Отдельный пример подключения к PostgreSQL через JDBC.

**CI:** последний проверенный запуск GitHub Actions завершился успешно.

**Стек:** `Java 17` · `Selenium WebDriver` · `TestNG` · `Maven` · `Page Object Model` · `Allure` · `GitHub Actions`

### 🔗 Проект

[🚀 SauceDemo — исходный код и README](https://github.com/MukhtarPashaTarkovskiy/saucedemo-ui-autotests)

[🌐 Тестируемый сайт SauceDemo](https://www.saucedemo.com/)

---

## 📋 Task Manager — Java / Spring Boot

Собственное веб-приложение для управления задачами, разработанное на Java и Spring Boot.

Проект используется как **Application Under Test (AUT)** для автоматизации API- и UI-тестирования.

### 🏗 Реализовано

- REST API для работы с пользователями и задачами.
- Регистрация и авторизация пользователей.
- Spring Security, HTTP-сессии и CSRF-защита.
- Хранение данных в PostgreSQL через Spring Data JPA.
- Раздельные тестовая и продуктивная среды.
- Развёртывание приложения на Render.
- Отдельные базы данных Neon для TEST и PROD.
- Docker-конфигурация приложения.

**Стек:** `Java 17` · `Spring Boot` · `Spring Security` · `Spring Data JPA` · `PostgreSQL` · `Maven` · `Docker` · `Render` · `Neon`

### 🔗 Проект

[💻 Task Manager — исходный код](https://github.com/MukhtarPashaTarkovskiy/task-manager)

[🌐 Task Manager — PROD](https://task-manager-kqoi.onrender.com)

[🧪 Task Manager — TEST](https://task-manager-test-588r.onrender.com)

---

# 📂 Manual QA & API Testing Projects

## 📱 SkillCinema — Mobile QA

Проект по ручному тестированию мобильного приложения.

Проверял пользовательские сценарии и интерфейс приложения, составлял тестовую документацию, регистрировал обнаруженные дефекты и подготавливал screenshot evidence.

**Навыки:** `Mobile Testing` · `Functional Testing` · `UI Testing` · `Test Cases` · `Bug Reporting` · `Jira`

### 🔗 Материалы

[📁 Открыть проект SkillCinema](https://drive.google.com/drive/folders/1-X1QR9JyVFGZ3ljaElOygK95dOO6qGx_?usp=sharing)

[📊 QA Portfolio — документация и навигация](https://docs.google.com/spreadsheets/d/1J-vHH_nV1emMXVcjufveTKT9GBUTaFEkkK3Aq9zW-DQ/edit?usp=sharing)

[🖼️ Screenshot Evidence](https://drive.google.com/drive/folders/1s2TQomFZ1ObBKX8WsQl0HJAl1G8tiHhP?usp=sharing)

---

## 🛒 Internet Shop — Web QA

Проект по ручному функциональному тестированию интернет-магазина.

Анализировал требования, проектировал приёмочные сценарии, проверял главную страницу, каталог, карточку товара, корзину, оформление заказа, регистрацию и личный кабинет. Обнаруженные проблемы и замечания оформлял в YouGile.

### 📊 Результаты

- **45** приёмочных тестовых сценариев.
- **161** зарегистрированный баг / замечание.
- **12** screenshot evidence.
- Публичная доска баг-репортов YouGile.

**Навыки:** `Web Testing` · `Requirements Analysis` · `Test Design` · `Acceptance Testing` · `Bug Reporting`

### 🔗 Материалы

[📊 Internet Shop QA Portfolio](https://docs.google.com/spreadsheets/d/168BPWq-8iRLeM06_ueMaA3saK8YOpPik96bbK3uXdcM/edit?usp=sharing)

[🐞 Публичная доска YouGile](https://ru.yougile.com/board/3satrxejn5tk)

[🖼️ Screenshot Evidence](https://drive.google.com/drive/folders/1Q7uHqoh6VVFotPXSNHMk1JhEnYP3zyCb?usp=sharing)

[📁 Все материалы проекта](https://drive.google.com/drive/folders/1fQcUGZ15YGUWrD0HacVdj_CrUvJ2TBxv?usp=sharing)

---

## 🔌 API Testing — Postman

Набор практических проектов по тестированию REST API.

Создавал коллекции `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, настраивал environments и переменные, работал с токенами авторизации и динамическими данными между запросами.

Писал JavaScript-проверки с `pm.test()` и `pm.expect()` и запускал связанные сценарии через Collection Runner.

В портфолио представлены **PFLB Test API**, **PR-CY API** и API Homework.

**Навыки:** `REST API` · `HTTP` · `Postman` · `JSON` · `JavaScript` · `Authorization`

### 🔗 Collections & Environments

[🧪 PFLB Test API Collection](https://drive.google.com/file/d/1d-yX58vZmbiDPghBC9FuVCSN5fs1cOhR/view?usp=sharing)

[🌐 PFLB Test Environment](https://drive.google.com/file/d/1EGU4U2q5oTGt5KpuQkMIXqpCUyFUWY-Z/view?usp=sharing)

[🔐 PFLB Token Environment](https://drive.google.com/file/d/11yuTQ8PkO7dyd3C_XkofPNfRwA8N5Nbh/view?usp=sharing)

[🔎 PR-CY API Collection](https://drive.google.com/file/d/1OEg2hpiDMR-u4sddvupBzhTDFP9yQHBI/view?usp=sharing)

[🌐 PR-CY Environment](https://drive.google.com/file/d/1Isjo_yBucUz1ObBGluNmYwSoqOoP7tgF/view?usp=sharing)

[🧪 API Homework Collection](https://drive.google.com/file/d/1yTzVVKuXK9ZYQWNJwUD9avXF8WnhNhX9/view?usp=sharing)

[📁 Все материалы API Testing](https://drive.google.com/drive/folders/17gaP-UZHmDuvZtWhrwC3cScYoW4dagzw?usp=sharing)

> Environment-файлы для публичного портфолио сохранены без рабочих секретов и токенов.

---

## 🔍 PR-CY — Web QA

Командный проект по ручному тестированию веб-сервиса PR-CY.

Моя основная зона ответственности — раздел **«Тариф и цены»**. Анализировал функциональность и требования, декомпозировал их на проверки, составлял чек-лист, работал с тест-кейсами и баг-репортами.

### 📊 Результаты

- **375** уникальных тест-кейсов в портфельной версии командного проекта.
- За мной закреплено **226 проверок** командного чек-листа.
- **225 проверок** относятся к разделу **«Тариф и цены»**.
- Подготовлены примеры баг-репортов и screenshot evidence из Jira.

В зоне ответственности проверялись карточки и сравнение тарифов, оформление подписки, промокоды, калькулятор лимитов, дополнительные опции, формы и связанные пользовательские сценарии.

**Навыки:** `Web Testing` · `Test Design` · `Checklists` · `Test Cases` · `TestRail` · `Jira` · `Teamwork`

### 🔗 Материалы

[📊 PR-CY — тест-кейсы](https://docs.google.com/spreadsheets/d/1hd2Ja4FyrcNSwSY1PIItUsdUAUBZzYY2YEd1R4JlFKE/edit?usp=sharing)

[📋 PR-CY — командный чек-лист](https://docs.google.com/spreadsheets/d/1iU4oAHN2yWhRHvGxpqcsC8vBa-tghBKHpVirv7yruGI/edit?usp=sharing)

[📁 Все материалы PR-CY](https://drive.google.com/drive/folders/1Clod1EhlEKHuiW15p71PtdG0ejvvnffB?usp=sharing)

---

# 💻 Additional Projects

## 🤖 UI Test Automation — Java / Selenium / JUnit 5

Проект автоматизации UI-тестирования веб-приложения.

Разрабатывал и рефакторил автотесты на Java с Selenium WebDriver и JUnit 5. Структура организована по Page Object Model: Page Objects, `BasePage`, `BaseTest` и конфигурация тестового окружения.

### 📊 Результат контрольного запуска

- **22 теста**
- **20 Passed**
- **2 Skipped**
- **0 Failed**

**Стек:** `Java` · `Selenium WebDriver` · `JUnit 5` · `Maven` · `Page Object Model` · `Git`

[🚀 Открыть UI Automation Project](https://github.com/MukhtarPashaTarkovskiy/autotesting-java-basics-diploma)

---

## 🔎 SearchEngine — Java / Spring Boot

Backend-приложение поискового движка для индексации сайтов и полнотекстового поиска.

Работал с Java и Spring Boot, REST API, MySQL, Spring Data JPA / Hibernate, JSoup и обработкой текстовых данных.

Приложение обходит страницы сайтов, сохраняет данные, выполняет лемматизацию, строит поисковый индекс и предоставляет API для управления индексацией, статистики и поиска.

**Стек:** `Java 17` · `Spring Boot` · `REST API` · `MySQL` · `JPA` · `Hibernate` · `JSoup` · `Maven`

[🔎 Открыть SearchEngine](https://github.com/MukhtarPashaTarkovskiy/SearchEngine)

---

# 🎓 Certificates

Сертификаты по тестированию, Java-разработке и смежным направлениям собраны отдельно.

[🎓 Открыть сертификаты](https://drive.google.com/drive/folders/1sRIq6qTKZVVPcyJ30mrIDCq-cBBomu8c?usp=sharing)

---

# 🎯 Что показывает портфолио

**Анализ требований → тест-дизайн → тестовая документация → выполнение проверок → баг-репорты → API-автоматизация → UI-автоматизация → проверка БД → отчётность и CI**

Проекты демонстрируют практические навыки ручного и автоматизированного тестирования, понимание клиент-серверной архитектуры, REST API, SQL, Java и Git.

---

## 📬 Контакты

**Mukhtar-Pasha Tarkovskiy**

✉️ [mukhtarpashatarkovskiy@mail.ru](mailto:mukhtarpashatarkovskiy@mail.ru)

✈️ [Telegram](https://t.me/TARKOVSKIYM)
