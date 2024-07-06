# SQL
1. the database language by the use of which we can perform certain operations on the existing database 
2. and also we can use this language to create a database. 
3. **[SQL](https://www.geeksforgeeks.org/structured-query-language/)** uses certain commands like Create, Drop, Insert, etc. to carry out the required tasks
- ***DDL – Data Definition Language***
    1. **[DDL](https://www.geeksforgeeks.org/features-of-structured-query-language-sql/)** or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. 
    2. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
    3. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. 
    4. These commands are normally not used by a general user, who should be accessing the database via an application.
    - List of DDL commands:
        1. **[CREATE](https://www.geeksforgeeks.org/sql-create/)**: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
        2. **[DROP](https://www.geeksforgeeks.org/sql-drop-truncate/)**: This command is used to delete objects from the database.
        3. **[ALTER](https://www.geeksforgeeks.org/sql-alter-add-drop-modify/):** This is used to alter the structure of the database.
        4. **[TRUNCATE](https://www.geeksforgeeks.org/sql-drop-truncate/):** This is used to remove all records from a table, including all spaces allocated for the records are removed.
        5. **[COMMENT](https://www.geeksforgeeks.org/sql-comments/)**: This is used to add comments to the data dictionary.
        6. **[RENAME](https://www.geeksforgeeks.org/sql-alter-rename/):** This is used to rename an object existing in the database.

- ***DQL – Data Query Language***
    1. it is a component of SQL statement that allows getting data from the database and imposing order upon it. 
    2. It includes the SELECT statement. This command allows getting the data out of the database to perform operations with it. 
    3. When a SELECT is fired against a table or tables the result is compiled into a further temporary table, which is displayed or perhaps received by the program i.e. a front-end.
    
    List of DQL:
    
    - **[SELECT](https://www.geeksforgeeks.org/sql-select-clause/):** It is used to retrieve data from the database.

- ***DCL – Data Control Language***
    
    DCL includes commands such as GRANT and REVOKE which mainly deal with the rights, permissions, and other controls of the database system.
    
    - List of  DCL commands:
        - **[GRANT:](https://www.geeksforgeeks.org/mysql-grant-revoke-privileges/)** This command gives users access privileges to the database.
        - **[REVOKE:](https://www.geeksforgeeks.org/difference-between-grant-and-revoke/)** This command withdraws the user’s access privileges given by using the GRANT command.
- ***DML – Data Manipulation Language***
    1. deals with the manipulation of data present in the database belonging to DML or Data Manipulation Language and this includes most of the SQL statements. 
    2. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
    - List of DML commands:
        - **[INSERT](https://www.geeksforgeeks.org/sql-insert-statement/)** : It is used to insert data into a table.
        - **[UPDATE](https://www.geeksforgeeks.org/sql-update-statement/):** It is used to update existing data within a table.
        - **[DELETE](https://www.geeksforgeeks.org/sql-delete-statement/)** : It is used to delete records from a database table.
        - **[LOCK:](https://www.geeksforgeeks.org/sql-lock-table/)** Table control concurrency.
        - **CALL:** Call a PL/SQL or JAVA subprogram.
        - **EXPLAIN PLAN:** It describes the access path to data.
- ***TCL - Transaction Control Language***
    - List of TCL commands:
        - **[COMMIT](https://www.geeksforgeeks.org/sql-transactions/):** Commits a Transaction.
        - **[ROLLBACK](https://www.geeksforgeeks.org/sql-transactions/):** Rollbacks a transaction in case of any error occurs.
        - **[SAVEPOINT](https://www.geeksforgeeks.org/sql-transactions/):** Sets a savepoint within a transaction.
        - **[SET TRANSACTION:](https://www.geeksforgeeks.org/sql-transactions/)** Specify characteristics for the transaction.

## SQL cheatsheet
[BASIC SQL Link](https://www.educba.com/cheat-sheet-sql/?source=leftnav)
