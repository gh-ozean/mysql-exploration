# Download MySQL Sample Database
The MySQL `classicmodels` sample database is a retailer of scale models of classic cars database. It contains typical business data such as customers, products, sales orders, sales order line items, etc.

## Download MySQL Sample Database
- Download the MySQL `classicmodels` sample database.
    - [From the `mysqltutorial.org` website.](https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip)
    - [From this repository.](../../assets/databases/mysqlsampledatabase.sql)
- Load the MySQL `classicmodels` sample database into MySQL Server.

## MySQL Sample Database Schema
- The MySQL `classicmodels` sample database schema consists of the following tables:
    - **Customers**: stores customer’s data.
    - **Products**: stores a list of scale model cars.
    - **ProductLines**: stores a list of product line categories.
    - **Orders**: stores sales orders placed by customers.
    - **OrderDetails**: stores sales order line items for each sales order.
    - **Payments**: stores payments made by customers based on their accounts.
    - **Employees**: stores all employee information as well as the organization structure such as who reports to whom.
    - **Offices**: stores sales office data.
<details>
  <summary>ER-Diagram</summary>

  ![](../../assets/images/mysql_sample_database_schema.png "MySQL Sample Database Schema")
</details>

## References
- [MySQL Sample Database](https://www.mysqltutorial.org/mysql-sample-database.aspx)
