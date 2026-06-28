# Practical_assignment4_CS301

функції та процедури написані на sql
--функція calculate_order_total(p_order_id int) - рахує загальну суму замовлення
--процедура create_order(p_customer_id int) - для створення замовлення для користувача з заданим id
--процедура procedure add_product_to_order(p_order_id int, p_product_id int, p_quantity int) - для додавання продукту до існуючого замовлення

тригери і функції до них написані на plpgsql
--trigger udate_order_total, що оновлює суму замовлення, коли додають, видаляюьб або змінюють дані і відповідна функція
--trigger log_order_created, що записує логи при створенні нового order

потім тестування
детальніше описано в самому скрипті
