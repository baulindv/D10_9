###D10.9 Домашнее задание

Требования для запуска описаны в файле requirements.txt 

Для запуска использовать команду "python manage.py runserver".

После запуска приложение будет доступно по адресу http://127.0.0.1:8000/

Админка: http://127.0.0.1:8000/admin/

Логин:пароль для входа в админку - 1:1

В базу данных занесено некоторое количество автомобилей разных марок и производителей со случайно сгенерированными годами выпуска, цветом и типом КПП.

Приложение позволяет фильтровать каталог по годам выпуска, цвету, типу КПП, а также выполнять регистронезависимый поиск по названию и производителю автомобиля (строка поискового запроса ищется сразу в 2х полях).

Фильтрация реализована с помощью Q-объектов, которые добавляются в зависимости от установленных фильтров в форме поиска.