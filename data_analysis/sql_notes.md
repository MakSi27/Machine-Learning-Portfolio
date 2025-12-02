# Introduction to SQL
SQL (Structured Query Language) is used to manage and interact with relational databases. It allows you to create, update, delete, and retrieve data efficiently.

# what is DML?
A data manipulation language statment used to read and modify data.

# Basic CRUD commands

## Create (insert data):
Adds new rows into a table.
ex - INSERT , VALUES

## READ (retrieve data)
Fetches data from a table
ex - SELECT , FROM

## UPDATE (modify existing data)
Changes values in existing rows.
ex - UPDATE , SET

## Delete (remove data)
Delete data from rows
ex - DELETE 


# CODE SNIPPET
```sql
CREAT TABLE BOOK(
    BookID INT PRIMARY KEY,
    TITLE VARCHAR(100),
    AUTHOR VARCHAR(100),
    Price DECIMAL (6,2)
);

INSERT INTO BOOK (BookID , TITLE , AUTHOR , Price)
VALUE (1, "Databases" , "James" , 599.00);

Select * FROM BOOK;

UPDATE BOOK 
set Price = 450.00
where BookID = 1;

DELETE FROM BOOK
WHERE BookID = 1;

```