# Приложение поиска по репозиториям github.com (используя публичный API https://docs.github.com/en/rest/reference/search#search-repositories).

Требования:
● В приложении должно быть поле для поиска по имени репозитория и список с результатом поиска, расположенный под полем поиска.
● В списке отображаются только первые 20 результатов в виде названия репозитория и количество его звезд.
● Результаты должны отображаться по мере набора текста в поле поиска.
● Поиск осуществляется только в том случае, если введено более 2-х символов в поле поиска.
● Если нет результатов удовлетворяющих поисковому запросу, выводится соответствующее сообщение.
● Если в поле поиска введено менее 2-х символов, то список с результатами поиска должен быть пустым.
● Необходимо обрабатывать ошибки запросов к API и выводить сообщения пользователю.
● Если запрос к API длится более 1000 мс, то выводится лоадер или соответствующий текст.
● Значение поля поиска должно сохраняться в query-параметре текущего роутера.
● Приложение должно быть написано с использованием Angular версии не ниже 10.
● В коде необходимо использовать rxjs, компоненты и сервисы.
● Разрешено использовать при необходимости любые ui-библиотеки (Angular Material, Ng-Zorro, Kendo UI и т. п.)
