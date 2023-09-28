# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 

```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:

![270861020-d4078461-29d3-4714-aa2b-d859b4552fa6](https://github.com/Thilagavathi7/G2_DBMS/assets/119407159/08fe00da-36f2-45df-8ee5-1163cbb374d2)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:

![270861141-2c22e52a-f697-4647-8c27-19b5dbb87d15](https://github.com/Thilagavathi7/G2_DBMS/assets/119407159/05b6a6a0-ec9f-4d1f-8270-000d7322a91d)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:

![270861215-d0c90400-b82a-4d48-898f-1d18b60f2f8a](https://github.com/Thilagavathi7/G2_DBMS/assets/119407159/59009b4a-b66a-4ecc-82ff-9f1dd18b209a)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:

![270861260-a7cf6059-f7e7-4b7f-9db9-8e45b0246324](https://github.com/Thilagavathi7/G2_DBMS/assets/119407159/77735bba-2e32-4e3e-95a6-c345e917c3eb)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:

![270861345-9d838847-3a92-4ec4-a2e6-a98d06085ad0](https://github.com/Thilagavathi7/G2_DBMS/assets/119407159/20291795-8a9a-4ef0-885c-bb74d3591129)

### RESULT:

To create a student database and execute DDL queries using SQL is executed successfully...
