# **Automazition-plan**
## **1. Перечень автоматизируемых сценариев**

#### Предусловие
*  Перед выполнением всех сценариев следует перейти на сайт https://netology.ru
#### Сценарии на переход к форме записи

* Переход к форме записи через главную страницу-каталог курсов - программирование- Тестировщик ПО
  
   1.1. Нажать на кнопку каталог курсов
  
   1.2. Нажать на блок программирование
  
   1.3. Нажать на блок Тестировщик ПО
  
   1.4. Нажать на кнопку записаться

  *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон
  
  
 * Переход к форме записи  через главную страницу  -каталог курсов -поиск-Тестировщик ПО

   1.1. Нажать на кнопку каталог курсов
  
   1.2. Нажать на поиск,ввести Тестировщик ПО,нажать кнопку " Найти курс "
  
   1.3. Выбрать Тестировщик ПО
  
   1.4. Нажать на кнопку записаться

   *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон
  

 * Переход к форме записи  через главную страницу  - программирование -Тестировщик ПО
    
   1.1. Нажать на блок Программирование
  
   1.2. Нажать на блок Тестировщик ПО
  
   1.3. Нажать на кнопку записаться

   *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон
  

 * Переход к форме записи  через главную страницу  - полный каталог -Тестировщик ПО
 
   1.1. Нажать на кнопку Полный каталог
  
   1.2. Выбрать Тестировщик ПО
  
   1.3. Нажать на кнопку записаться

   *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон
  

 * Переход к форме записи  через главную страницу  - полный каталог - поиск -Тестировщик ПО
 
   1.1. Нажать на кнопку Полный каталог
  
   1.2. Кликнуть на меню поиск,ввести Тестировщик ПО,нажать на кнопку "Найти курс"
  
   1.3. Нажать на кнопку записаться

   *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон
  

 * Переход к форме записи  через главную страницу  - полный каталог - программирование - Тестировщик ПО
 
   1.1. Нажать на кнопку Полный каталог
  
   1.2. Нажать на блок Программирование
  
   1.3. Нажать на блок Тестировщик ПО

   1.4. Нажать на кнопку записаться

   *Ожидаемый результат.* Открылась форма записи,видно поле Имя,Телефон

   
#### Сценарии на заполнение формы заявки 

#### Предусловие

* Перед выполнением дальнейших тестов необходимо перейти к форме записи,любым из перечисленных способов выше.

* Тест на введение валидных значений в форму заявки

  1.1 Ввести валидное значение в поле имя "Евгения"

  1.2 Ввести валидное значение в поле номер телефона "+79046441684"

  1.3 Нажать на кнопку записаться

  *Ожидаемый результат.* Ваша заявка отправлена,скоро с вами свяжиться специалист

* Тест на введение невалидных значений в поле имя

  1.1 Ввести  значение в поле имя "888888"

  *Ожидаемый результат.* Под полем имя красным высвечивается надпись " Должно состоять из букв "

* Тест на введение невалидных значений в поле телефон 

  1.1 Ввести  значение в поле телефон "аааа"

  *Ожидаемый результат.* Под полем телефон  красным высвечивается надпись " Номер в формате +9 (999) 999-99-99 "

* Тест на введение граничных  значений в поле имя 

  1.1 Ввести  значение в поле имя "а"

  *Ожидаемый результат.* Под полем имя  красным высвечивается надпись " Должно быть не короче 2 символов "

* Тест на удаление данных в полях имя и телефон

  1.1 Ввести данные в поле имя "Евгения".Удалить данные из поля Имя

  1.2 Ввести данные в поле  телефон  "+79046441684".Удалить данные из поля Телефон

  *Ожидаемый результат.* Данные успешно удаляются ,под каждым из поле высвечивается надпись "Обязательное поле"


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
