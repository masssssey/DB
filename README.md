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
