# SQL - Introduction

This was my first project in which I began to work with SQL and relational
databases. I began practicing introductory data definition and data
manipulation language, making subqueries, and using functions.

## Usage :dolphin:

* Scripts [3-list_tables.sql](./3-list_tables.sql) forward take the database to query
from as a MySQL command line argument.

```
$ cat 3-list_tables.sql | mysql -h localhost -u root -p mysql
```

## Tasks :page_with_curl:

* **0. List databases**
  * [0-list_databases.sql](./0-list_databases.sql): MySQL script that lists all databases.

* **1. Create a database**
  * [1-create_database.sql](./1-create_database.sql): MySQL script that creates the database
  `hbtn_0c_0`.

* **2. Delete a database**
  * [2-remove_databases.sql](./2-remove_databases.sql): MySQL script that deletes the database
  `hbtn_0c_0`.

* **3. List tables**
  * [3-list_tables.sql](./3-list_tables.sql): MySQL script that lists all tables.

* **4. First table**
  * [4-first_table.sql](./4-first_table.sql): MySQL script that creates a table `first_table`.
  * Description:
    * `id`: INT
    * `name`: VARCHAR(256)

* **5. Full description**
  * [5-full_table.sql](./5-full_table.sql): MySQL script that prints the full description of the
  table `first_table`.

* **6. List all in table**
  * [6-list_values.sql](./6-list_values.sql): MySQL script that lists all rows of the table
  `first_table`.

