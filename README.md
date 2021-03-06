# Web-Lab-4

Четвертая лабораторная по вебу. Вариант 13214.

### Переписать приложение из предыдущей лабораторной работы с использованием следующих технологий:

* Уровень back-end должен быть основан на Spring Framework.

* Уровень front-end должен быть построен на React + Redux с использованием набора компонентов [@yandex-ui](https://github.com/bem/yandex-ui)

* Взаимодействие между уровнями back-end и front-end должно быть организовано посредством REST API.

### Приложение по-прежнему должно включать в себя 2 страницы - стартовую и основную страницу приложения. Обе страницы приложения должны быть адаптированы для отображения в 3 режимах:

* "Десктопный" - для устройств, ширина экрана которых равна или превышает 1114 пикселей.

* "Планшетный" - для устройств, ширина экрана которых равна или превышает 795, но меньше 1114 пикселей.

* "Мобильный"- для устройств, ширина экрана которых меньше 795 пикселей.

### Стартовая страница должна содержать следующие элементы:

* "Шапку", содержащую ФИО студента, номер группы и номер варианта.

* Форму для ввода логина и пароля. Информация о зарегистрированных в системе пользователях должна храниться в отдельной таблице БД (пароль должен храниться в виде хэш-суммы). Доступ неавторизованных пользователей к основной странице приложения должен быть запрещён.