1. Dish
id primary key
name
price
description
time_do_do

2. Employee
id primary key
name
salary

3. Ingredient
id primary key
price
name

4. Inventory
ingredient_id foreign key
quantity

5. expense
id primary key
time

6. expense_list
expense_id foreign key
ingredient_id foreign key
quantity
total_price

7. supply
id primary key
name
address
wait_time

8. supply_ingredient
id primary key
supply_id foreign key
ingredient_id foreign key
price

9.  Order
id primary key
customer_id foreign key
status

10. Customer
id primary key
name
address
phone
wait_time

11.  Work
id primary key
employee_id foreign key
dish_id foreign key
time_start
time_end

