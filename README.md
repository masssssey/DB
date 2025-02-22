Лабораторная работа №1

1. Выберите из таблицы orders все заказы
   
   SELECT * FROM orders;
   
   ![image](https://github.com/user-attachments/assets/be90847e-dc2b-46ca-88ac-b0accae188d4)
   
2.Выберите из таблицы orders все заказы кроме новых. У новых заказов status равен "new". Использовать in

SELECT * FROM orders WHERE STATUS IN ('cancelled','in_progress','delivery')

![image](https://github.com/user-attachments/assets/c82eac2c-1b97-4fbc-9e0e-068aad2640ba)

3.Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

![image](https://github.com/user-attachments/assets/33d80e22-b504-4bd0-93ee-50bf0bf0df31)

4.Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count). Вывести нужно только номер (id) и сумму (sum) заказа.

![image](https://github.com/user-attachments/assets/b39c468b-d38e-4a26-a7f6-acc4e929434e)

Лабораторная работа №2

1. Выберите из таблицы orders 3 самых дешевых заказа за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/cd59133b-f481-43f7-83ee-d58f9c25bcfe)
   
2. Выберите из таблицы orders 2 самых дорогих заказов за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/0c3b404d-cecd-442f-b76f-449e82df07ba)
