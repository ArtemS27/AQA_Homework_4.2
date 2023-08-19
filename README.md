# Автоматизируемые сценарии
### 1. Автоматизация перехода на страницу заполнения формы "Тестировщик ПО"
1. Отркыть страницу netology.ru
2. В хедере нажать кнопку "Каталог курсов".
3. Из выпадающего списка выбрать "Программирование".
4. Из списка выбрать "Тестировщик ПО".
5. Пролистать страницу вниз до конца.

*Ожидаемый результат: Открыта страница курса "Тестировщик ПО"*

### 2. Автоматизация перехода на страницу заполнения формы "Тестировщик ПО"
1. Отркыть страницу netology.ru
2. В хедере нажать кнопку "Каталог курсов".
3. В поле ввода поиска ввести "Тестировщик ПО"
4. Нажать кнопку "Найти"
5. Из списка выбрать "Тестировщик ПО"
6. Пролистать страницу вниз до конца.

*Ожидаемый результат: Открыта страница курса "Тестировщик ПО"*

### 3. Автоматизация заполнения формы. Позитивный сценарий.
1. В поле имя ввести валидное имя.
2. В поле телефон ввести валидное значение.
3. Нажать кнопку "Записаться"

*Ожидаемый результат: Форма отправлена*

### 4. Автоматизация заполнения формы. Негативный сценарий.
1. В поле имя ввести невалидное имя.
2. В поле телефон ввести валидное значение.
3. Нажать кнопку "Записаться"

*Ожидаемый результат: Появилось сообщение "Поле Имя может содержать только кириллицу"*

### 5. Автоматизация заполнения формы. Негативный сценарий.
1. В поле имя ввести валидное имя.
2. В поле телефон ввести невалидное значение.
3. Нажать кнопку "Записаться"

*Ожидаемый результат: Появилось сообщение: "Поле телефон должно содержать 11 цифр"*

## Перечень используемых инструментов

### IntelliJ IDEA
Удобный для использования фрэймворк с интеграцией системы Git.

### Java
Популярный ООП язык программирования с большим количеством возможностей и библиотек.

### Gradle
Удобная система автоматической сборки с простым подключением зависимостей.

### Junit
Библиотека для проведения тестов.

### Selenide 
Библоиотека для взаимодействия с UI с простым и понятным синтаксисом.

### JavaFaker
Библиотека для генерации рандомных данных.

## Необходимые разрешения, данные и доступы.

1. Разрешение на тестирование.
2. Данные формата валидного имени пользователя и телефона.

## Возможные риски при автоматизации.

1. Отсутсвие доступа к сайту.
2. Отсутсвие данных формата валидного имени или телефона.
3. Отсутстве явных индентификаторов элементов сайта.
4. Изменение структуры сайта.

## Необходимые специалисты для автоматизации

* Тестировщик

## Интервальная оценка с учетом рисков

5 часов.
