# Bamazon

Bamazon is a CRM that focuses on sales. It provides command-line interfaces for customers, managers, and supervisors.

Technologies Used
Node, MySQL

How to Run:

1.In MySQL Workbench, connect to localhost:3306 and run bamazon_schema.sql then bamazon_seeds.sql.

![mee](images/how_to_run_step3)

2.Finally, in Bash, type node bamazonCustomer.js tolog in as a customer, node bamazonManager.js as a manager, node bamazonSupervisor.js as a supervisor.

Demos - Customer:

As a customer, you can check items (products) that are for sale and buy them.

To buy an item, enter the item ID and quantity. You will get the subtotal.

![mee](images/customer_step1)

Note, you can buy an item only up to the stock quantity.

![mee](images/customer_step2)

At the end, you can see all items that you purchased.

![mee](images/customer_step3)

Demos - Manager

As a manager, you can add new items and restock them.

Add a New Product

To add an item, enter the department name (make a selection), item name, price, and stock quantity.

![mee](images/manager_steps1)

View Products for Sale

Check items that are for sale.

![mee](images/manager_steps2)

Add to inventory

Let's stock more Until Dawn!

![mee](images/manager_steps3)

View Low Inventory

Finally, you can check which items have fewer than 5 in stock.

![mee](images/manager_steps4)

Demos - Supervisor

As a supervisior, you can add new departments and check their profits.

Add a New Department

To add a department, enter the department name and overhead costs.

![mee](images/supervisor_steps1)

View Department Sales

You can check the overhead costs, sales, and profits of each department.

![mee](images/supervisor_steps2)





