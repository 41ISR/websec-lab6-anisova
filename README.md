![image](https://github.com/user-attachments/assets/a7581718-ea88-41a9-852d-1c58585a0ab6)


![image](https://github.com/user-attachments/assets/a7581718-ea88-41a9-852d-1c58585a0ab6)


# SQL инъекция

Данный документ описывает лабораторную работу по изучению SQL-инъекций. В рамках работы будут анализировать уязвимости веб-приложения, развернутого в Docker-контейнере, и применение методов эксплуатации уязвимостей.

## Цели работы:

- Определение уязвимых SQL-запросов.
- Проведение атак с использованием SQL-инъекций.
- Получение скрытых данных из базы данных.
- Анализ методов защиты от атак.

## Ресурс

[Сайт](http://92.63.179.34:8080/)

## Задания

1. Достать всех пользователей и их зарплаты

2. Узнать версию MySQL

3. Узнать пароли всех пользователей

4. Определить текущего пользователя базы данных

5. Извлечь имена таблиц из схемы базы данных

6. Получить список столбцов users таблицы

## Сдача

Создайте форк репозитория `websec-lab6-{ваша_фамилия}` в организацию `41ISR`, работайте в ветке `dev`. Удалите содержимое файла `README.md` и работайте в нем же. По завершению работы сделайте пулл реквест `dev` => `main` и отметьте  [меня](https://github.com/ktkv419) ревьювером

## Credentials

Логин и пароль для получения зарплаты кирка

- <code>username</code>: <code>james_kirk</code>
- <code>password</code>: <code>kobayashi_maru</code>

## Подсказки

- [PayloadAllTheThigs](https://swisskyrepo.github.io/PayloadsAllTheThings/)
- [SQL Injection List](https://github.com/payloadbox/sql-injection-payload-list)
