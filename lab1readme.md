1. Dish
id primary key
name
price
description
time_to_do

2 Employee
id primary key
name
salary

3. dish_ingredient
dish_id foreign key
ingredeient foreign key
quanity

4. Ingredient
id primary key
price
name

5. Inventory
ingredient_id foreign key
quantity

6. expense
id primary key
time
supply_id foreign key

7. expense_list
expense_id foreign key
ingredient_id foreign key
quantity
total_price

8. supply
id primary key
name
address
wait_time


9. supply_ingredient
id primary key
supply_id foreign key
ingredient_id foreign key
price

10.  Order
id primary key
customer_id foreign key
time_order
time_delivery
interest
status

11. Order_dish -ok
order_id
dish_id
quantity

12. Customer
id primary key
name
address
phone
wait_time


13.  Work
id primary key
employee_id foreign key
dish_id foreign key
order_id foreign key
time_start
time_end
