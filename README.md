# **Automazition-plan**
## **1. Перечень автоматизируемых сценариев**

#### Предусловие
*  Перед выполнением всех сценариев следует перейти на сайт https://netology.ru


## 2. Перечень используемых инструментов с обоснованием выбора.

* Idea intellij - программа в которой мы будем писать наш код и тесты

* Selenide -так как основная задача тест интерфейса,мы можем использовать данную библиотеку для обращения к элементам страниц

* Facker - данная библотека поможет нам с генерацией валидных и невалидных данных для наших тестов.

* Loombok - Нам важно,чтобы наш код выглядел как можно более структуризированным и менее громоздким

* Allure - нам важно понимать производительность наших тестов и их покрытие.Для этого нам нужна библиотека Allure для построения отчетов или любая другая.

* Github или любая облачная система для хранения кода.Чтобы можно оперативно править код и  хранить различные версии нашего проекта.

* CI-данная надстройка поможет нам вовремя выявить ,что с нашими тестами что-то случилось.Например изменились какие-то метрики.Можем использовать CI на Github или Appveyor.

* Junit5 - платформа для написания тестов

* Gradle - система автоматизиции сборки. 

* Docker - поможет создать образ базы данных.

* Jmeter -данный инструмент поможет  проверить нам ,что будет с нашим сайтом при посещении большим количеством пользователей.

* DB Navigator или Dbeaver -для отправки запросов в нашу базу данных

* Java - язык программирования на котором мы будем писать автотесты.


## 3. Перечень необходимых разрешений, данных и доступов.

* Нам необходим jar.файл

* Копия базы данных данных(включая все необходимые атрибуты,пароль,логин,имя),чтобы не засорять и не перегружать текущую .

* Получить все необходимые метрики от аналитиков и возможные сценарии пользовательского поведения
  
*  Получить разрешение на выполнение работ по тестированию у владельцев сайта


## 4. Перечень и описание возможных рисков при автоматизации.

* Интерфейс сайта и метрики сайта могут поменяться,поэтому наши тесты будут падать и их придется переделывать
  

## 5. Перечень необходимых специалистов для автоматизации.

* QA инженер


## 6. Интервальная оценка с учётом рисков в часах.

* 8 - 15 часов
