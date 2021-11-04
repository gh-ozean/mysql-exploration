# Load MySQL Sample Database
How to load the `classicmodels` sample database to the MySQL Server using the command-line interface of the `mysql` program.

## Load MySQL Sample Database
- [Download the MySQL `classicmodels` sample database.](download_mysql_sample_database.md)
- [Connect to the MySQL Server.](connect_to_mysql_server.md)
- Use the `source` command to load the `classicmodels` sample database into the MySQL Server.
```shell
mysql> source C:\mysql-exploration\assets\databases\mysqlsampledatabase.sql
```
- Use the `SHOW DATABASES` command to list all databases in the current server.
```shell
mysql> SHOW DATABASES;
+--------------------+
| Database           |
+--------------------+
| classicmodels      |
| information_schema |
| mysql              |
| performance_schema |
| sakila             |
| sys                |
| world              |
+--------------------+
7 rows in set (0.00 sec)
```
- Use the `USE` command to switch the current database to the `classicmodels` database.
```shell
mysql> USE classicmodels;
```
- Use this command to query data from the customers table.
```shell
mysql> SELECT * FROM customers;
```

## References
- [How to Load the Sample Database into MySQL Server](https://www.mysqltutorial.org/how-to-load-sample-database-into-mysql-database-server.aspx)
