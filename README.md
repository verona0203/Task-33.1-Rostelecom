# Task-33.1-Rostelecom
Дипломный проект: реальный кейс компании «Ростелеком Информационные Технологии».Задание протестировать страницы с пользовательскими данными на сайте Ростелеком. 
Так как много однотипных страниц, удобно сделать несколько макетов Page-Object, и на их основе написать автотесты.
Удобно,что почти у всех тестируемых элементов в DOM-дереве есть ID, что облегчает написание локаторов.
Ручными тест-кейсами можно протестировать классы эквивалентности и граничные значения, поскольку там нет больших массивов данных.
Удалось описать несколько багов.
Код для запуска тестов в Pycharm: python -m pytest -v --driver Chrome --driver-path tests/chromedriver tests/файл с тестами.
