# FSDLab4


Execute the following SQL query to create a db named "employee" a table named "employees" inside your MySQL database. We will use this table for all of our future operations.



CREATE TABLE employees (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    address VARCHAR(255) NOT NULL,
    salary INT(10) NOT NULL
);
