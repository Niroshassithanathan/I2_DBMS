# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## AIM :
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language) :
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## List of DDL commands :
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.

## Query :
1)Create a table student with the following fieds rollno,name,age,address,phoneno.
## SQL QUERY :
```
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));
```
## OUTPUT :
<img width="647" alt="d1" src="https://github.com/Niroshassithanathan/I2_DBMS/assets/121418437/5df59f06-3fca-41ec-a9ad-8f7df3a40c14">

## Query :
2)Change the above student table by adding another attribute department.
## SQL QUERY :
```
alter table student add department varchar(15);
```
## OUTPUT :
<img width="354" alt="d2" src="https://github.com/Niroshassithanathan/I2_DBMS/assets/121418437/b46598f9-a860-4919-8c2e-daf3b8fe18e4">

## QUERY :
3)Drop the student table
## SQL QUERY :
```
drop table student;
```
## OUTPUT :
<img width="215" alt="d3" src="https://github.com/Niroshassithanathan/I2_DBMS/assets/121418437/81e23418-9dec-4058-9351-0a47e2e046ee">

## QUERY :
4)Delete the student table using truncate keyword.
## SQL QUERY :
```
truncate table student;
```
## OUTPUT :
<img width="209" alt="d4" src="https://github.com/Niroshassithanathan/I2_DBMS/assets/121418437/9f6529f1-f512-455f-8801-519a8a29c07d">

## QUERY :
5)Rename the student table to mystudent.
## SQL QUERY :
```
rename table student to mystudent;
```
## OUTPUT :
<img width="233" alt="d5" src="https://github.com/Niroshassithanathan/I2_DBMS/assets/121418437/511aa78b-9974-4025-9e49-de28cb6033d5">
