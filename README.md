# Домашнее задание к занятию "6.2. SQL"
1. [Docker-compose манифест](./docker-compose/postgresql.yml).
2. Список БД:  
   ![database list](./pictures/database%20list.PNG)  
   Описание таблиц:  
   ![describe](./pictures/describe%20tables.PNG)  
   SQL-запрос и список пользователей:
   ![privileges list](./pictures/privileges%20list.PNG)
3. Запросы и результаты их выполнения:  
   ![insert orders](./pictures/insert%20orders.PNG)  
   ![insert clients](./pictures/insert%20orders.PNG)  
   ![select count](./pictures/select%20count.PNG)  
4. Запросы добавления данных:  
   ![update clients](./pictures/update%20clients.PNG)  
   Запрос для вывода данных:  
   ![inner join](./pictures/inner%20join.PNG)
5. Вывод explain:  
   ![explain](./pictures/explain.PNG)
   В данном случае explain показывает шаги формирования ответа с некоторыми параметрами, а именно:
   Параметр | описание
   -------- | --------
   cost | Абстрактное число указывающее затраченное для выполнения время. Первое число - время затраченное на выполнения запроса первой записи таблицы, второе - всех записей.
   rows | Предпологаемое количество возвращаемых строк
   width | Предпологаемый средний размер одной строки в байтах
6. Последовательность действий по созданию и восстановлению из бекапа:  
   ![pg_dump1](./pictures/pg_dump1.PNG)  
   ![pg_dump2](./pictures/pg_dump2.PNG)