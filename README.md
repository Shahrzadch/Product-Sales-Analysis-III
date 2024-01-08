**Product Sales Analysis III**

The Sales table has information about sale_id, product_id, year, quantity, and price.
(sale_id, year) is the primary key (combination of columns with unique values) of this table.
product_id is a foreign key (reference column) to Product table.
Each row of this table shows a sale on the product product_id in a certain year.
Note that the price is per unit.

The Product table has product_id and product_name.
product_id is the primary key (column with unique values) of this table.
Each row of this table indicates the product name of each product.

Write a solution to select the product id, year, quantity, and price for the first year of every product sold.
Return the resulting table in any order.
