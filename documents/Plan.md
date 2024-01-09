> ### **Планирование автоматизации тестирования**
> ### _Перечень планируемых сценариев_
> > 1. Отправка валидной формы на покупку тура
>
> 1. Открыть сайт
> 2. Нажать кнопку "Купить"
> 3. Заполнить форму валидными данными
> 4. Нажать "Подтвердить"
>
> **Ожидаемый результат** Форма успешно заполняется
>
> > 2. Отправка валидной формы на покупку тура в кредит
>
> 1. Открыть сайт
> 2. Нажать кнопку "Купить в кредит"
> 3. Заполнить форму валидными данными
> 4. Нажать "Подтвердить"
>
> **Ожидаемый результат** Форма успешно заполняется
>
> > 3. Отправка невалидной формы на покупку тура
>
> 1. Открыть сайт
> 2. Нажать кнопку "Купить"
> 3. Заполнить форму невалидными данными (Пример, в поле "Фамилия" ввести "Ивано$$")
> 4. Нажать "Подтвердить"
>
> **Ожидаемый результат** Ошибка! Не верно введены данные в поле "Фамилия"
>
> > 4. Отправка невалидной формы на покупку тура в кредит
>
> 1. Открыть сайт
> 2. Нажать кнопку "Купить в кредит"
> 3. Заполнить форму невалидными данными (Пример, в поле "Дата" ввести "П8")
> 4. Нажать "Подтвердить"
>
> **Ожидаемый результат** Ошибка! Не верно введены данные в поле "Дата"
>
> > 5. Навигация переключении с формы на форму
>
> 1. Открыть сайт
> 2. Нажать кнопку "Купить"
> 3. Нажать кнопку "Назад"
> 4. Нажать кнопку "Купить в кредит"
>
> **Ожидаемый результат** Успешное переключение с формы на форму
>
> ### _Перечень используемых инструментов с обоснованием выбора_
> 1. Java - для написания кода
> 2. Markdown - для написания отчетов
> 3. Git - для доступа к проекту коллегам
> 4. Selenide - для визуализации автотестов
> 5. Gradle - для написания автотестов
> 6. MySQL, PostgreSQ - для подключения к СУДБ
> 7. Docker - для запуска эмулятора
> 8. Allure - для отчета по тестированию
> 9. JUnit5 - для написания кода
>
> ### _Перечень и описание возможных рисков_
> * Отсутствие в коде разработчика приложения тестовых меток. Вследствие чего уменьшается скорость тестирования и увеличивается стоимость проекта
> * Обновление функций приложения, что приведет к новому поиску селекторов
> * Сбои в инфраструктуре сайта. Не рабочий сайт нельзя протестировать
>
> ### _Интервальная оценка с учетом рисков в часах_
> На дипломный проект выделено 48 часов, с учетом рисков (20-25%) получается 60 часов
>
> ### _План сдачи работ_
> Не позднее 27 января, при этом возможно продление дедлайна на 14 дней