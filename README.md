# SQL and DataBase

## Topics to be cover

1. History of Data.
2. DB + SQL Fundamentals.
3. Environment Setup.
4. SQL Deep Dive.
5. Advanced SQL.
6. Database Management.
7. Database Design.
8. Solving The Mystery.
9. Database Landscape.
10. Data Engineering.
11. Redis.
12. Extra Bits(how database connects to nodejs).

Question:-if someone from your company stole youre company data from database then how do you find that person.(try to solve this mystery)


## History and Story of Data.


#### What is Data?
Before storing the data in database you must have a knowledge about data. what is this?
Database:-"its a collection of data,a method for accessing and manipulating that data".....data is everywhere company is big like amazone alibaba because of their data.Every thing work with a data from a simple drawn to a robot.We produce 2.5 quantrilians of data every year.
From where all these data come from data is the thing that as human us created but without capturing and using that data it is useless for us.Like only listening and gathering information from teacher and from online courses is usesless after some time for you to make it useful you have to make a proper notes.Databases work same as our notes they capture the data so that we can use it there are 44zetabytes of data are there we have now.All these data is captured in database.
You can not tore that much of huge data without database.Without database all the companies like instagram and facebook does not make money.Databases are not special things they are just hardware and software they are just computers.Here hardware is the mechanical part and software is the actual code that collects the useful data its here software is like a inteligent person in a store and we are the person who give him data to put somewhere by own self in the drawer and here the store or a godown is a database.
It is like a disk drive to store once and zeroes.We can create database in our phone and in our computer because the real database is same as our computer with different software and a large memory size.


1. We are now clear with that database is a hardware with a database software at top of it.
2. Excell is also a database to store our data and excel is a database software that allows us to manipulate our data a pen and a paper is also a database because its also a way to store our data.
3. The images of our database is like a circular disks putting one into another is because of this drummemory heck its image in stackoverflow.
4. Before disk drive we store our data in drum memory which is cylendrical in shape.
5. Because of its historical reason we have a cylendrical shape for database.
6. As we know that database is a software and harware there are many types of databases.
7. Excel is also a database so why we not use it for big company why we have other database.
8. Because in database we store a huge amount of data that we can not hande with Excel and spreadsheet.
9. Like integrity in database so that not every body can delete our database.
10. You can store terabytes of data.
11. You can combine different databases.
12. You can write programs to do so many interesting things with your data.
13. These things you can not do in spreadsheet.


#### These are some most popular databases.
1. MariaDB.
2. MS-SQL Server.
3. MOngoDB.
4. ElasticSearch.
5. Redis.
6. SQLite.
7. PostgreSQL.
8. IBM DB2.
9. Oracle Database.
10. Cassandra.


#### How companies use the data.
1. Product manager knowser about their product at which they are working on.They learn from the data that their product is working properly or not.Know about the drawbacks of their products and improve it to make sales.Used to target the perfect users for their products.
2. Like a web and a app developer who developed a app you put a sign in and a login page to stre the information about the user so that you can get the same user on your website by their data by shareing the link of your new product to them by their contact information that increses the chances of your sales.
3. They can play the game with their last saved location.
4. There are a data engineer and a data scientist in your company that makes decision on the behalf of the company data that creates a better macine learnign algorithms that give a better information to the users.
5. We have database administrators and databse engineers who install the database software and maintain the database they install database and update software of database.They use hadoop amazone redchip etc.

#### We can learn that.
1. How to put data in DB.
2. How to use/update/learn from data.
3. How to remove data.

#### What is thissssssssssss....
1. Datbase Management system.
2. Relational database management system.
3. Structured Query language.

##### DBMS is a software and a program to manage database it recieves information somebody like us that wants something with data and instruct the system the data base to grab that data and make chages to that data.

##### Relational Database management system is a subset of dbms it is a most used most popular type of database.It is used to setup relation among different data records.

##### SQL is language to communicate with databases or dbms and rdbms.

Example:like thik that we have a data so we have to use RDBMS(postgreSQL) that gives some functions to create databse and manage database.Both DATA + DBMS is combines to make a database.And at last finally we have sql (structured query language) outside our database its not a programming language its a query language.It gives powser like developer to communicate with that databse.Its like a simple english language.

Listen by using sql it doesnt mean that we are here to manage only a single type of database like posrgreSQL.By learnig SQL we can interact eith lots of databases like MAriaDB,SQL server,MySQL,oracleDB,SQLite,PostgreSQL.

(LINK for Practice SQL https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all)

## Types of Databases
There are hundreds of databases are there but you have to know about only few of them.
Databases are mainly divided into five categories.

1. Relational model.(Postgrace).
2. Document model.(mongoDB,caugh,Firebase they use document model)
3. Key value databases(Radis,dynamodb,all have key value storage system).
4. Graph model databases.(comples and rarely use)
5. Wide columinar(new and allpy googles big table,apachi,casendra)

#### A database is a system of hardware and software that allow a user to store and organize and use data.


# Database + SQL fundamentals

## What is SQL?
SQL is a language that we use to tawlk to our database. It is a programming language it means it has a set of rules to do communication with database. Database data is nothing but a structured setup data. You can not store tech companies data in a flat file or on excel sheet. To communicate with database we write statements in sql or sql queries. that are instructions to perform certain operation in database.


## What is a Query?
A Query is nothing but instruction. In english query is question so in our statement we use question and to which we want our answer from database. SQL query is also called as SQL statement.Eg

```sql

SELECT * FROM USERS

```

Sql statement is the synoniom of query.

In abouve statement we use select to select all because we use * which is a wild card from is used to where we have to get the data. USERS say that we have to get the data from user section in our database.

```sql

select student from users;

```
### Explain structure

```sql

 Clause { SELECT NAME
 Clause { FROM USERS
  Clause { WHERE ROLE = "MANAGER";


```
1. SELECT FROM WHERE are Keywords
2. NAME USERS ROLE are Identifiers
3. "MANAGER" is Expression.
4. ROLE = "MANAGER" is a condition
5. The whole thing is called as sql statement.

In this sql statement we are filtering the data for getting managet.
Identifier is just a word to define a part of data.
Sql is a declarative language.

## Imperitive vs Declarative

### Declarative language :- 
it is a language where we say WHAT WILL HAPPEN but we not specify clearly How it will happen

### Imperative Programming :-
Declarative means we have to define that HOW IT WILL HAPPEN In it we give line by line instruction do that and that and that.And in decalrative we say GIVE ME THIS.


Like for making sandwitch in decalaritive approach we say give me sandwitch and in inperative we take substance to make sandwitch and prepare it by own with proper instructions. 

SQL is declarative and java is imperative language but python is both imperative and declarative you can do both with it.
Declarative is simple and imperative is complex but very powerful.


## History of SQL?


The original name of sql is sequel we can use both of this name sequal stands for structured english query language. Its name was chnged because of the copyright clam.
In 1970 a programmer in IBM named   ....... wrote a paper that set  the standard for databases and sql his papaer are called a relational model of data for large shared data banks.
Two people from IBM implement his vesion They created the very first version of sql. They create language and software to amnage databases. These two people from IBM based on his ideas  wrote the original version of sql and make sql a standard language for database.

## SQL Standards

SQL is a language that used to tawlk to databases and lot of different companies make databases they sypply databases. Mysql,postgress,oracle all these companies supply databases but they all uses SQL. SQL is a widely addopted language. Companies take the sql language and add some new features to it and make a standard to make it efficient according to their data base. These companies do this because of increasing the use of their database so they add more and new features to their databases.



## What is a Databse?

Before databases we have FIle processing systems In it you save your data in individual files and there is no relationship between the data you simply created a system to save a particular type of data You have to use different copy of same data in different file that make it difficult to update data because all files are individual programmers make this software to manage their data thats why we call it a file processing system. IN this model server directly tawlk to machine or storage device it is difficult because you have to do all these management in python or java. We have to create different system or architecture to sote different type of data there is no common model. These problems are handled by database oriented approach.

## Database Oriented Approach.

People use database approach to make it simple. Database Approach :- a software utilize to manage database and it is called as database management software its purpose it to put all given constrans at a place in database and used to manage our data. It do this by following a model. Different databases software follows different models. 
This is a single piece of software that promise to you that if you follow this way to save your data i do all the management for you that is what a database management software did.
You can create different sections to store different type of data in data base and stablish the relationship between these databases by usign database management software.

Before a user uses a computer system that directly tawlk to the storage or database by having a custom software between them. Now a new thing called DBMS is introduced between computer and storage device this software take care of all the things and give you a simple and common  interface and a way to handle your database. It is handled by a specific language called structured query language.
Each DBMS has their own database model.


## Database Model

There are many database models are there we have

1. Herarchical
2. Networking
3. Entity-relationshi[
4. Relational
5. Object oriented
6. Flat
7. Semi-structured

We cover herirchical and networking model because they are old and we master relational model.


## Hierarchical model

It is a old model primarily used by IBM in 1960-1970 it is unefficient way to store data thats why people donot use it now a days. It has a tree like structure having a single root parent for a single child.It is like a XML data which is a document like and its data can be stored in tree like structure because of having nested files. But in it if you delete a root or a parent element its child automatically been deleted. It uses one to many relationship one parent have many children.

## Networking model
 It is a expended version of herarchical model that allows many to many relationship. In it child entity could have multiple parents. It is difficult to manage relationship in it.


## Relational model

It follow a table structure ,organize your data in table and make relationship between tables and in it all tables have a specific name for column. We took a unique id that uniquely identify the table data. We have lots of concep in it to draw relationship between table or data.

The logic of how the relationship are linked are handled by the database management software.


## What is DBMS (software)?

It is like a superwiser to manage our data in database i know all the rules that you want to store your data i know your model you only need to give me a sql query i know how to give your data and give back to you. It is like a referee who tells you that heyy you can not store your data like this 
.See what a DBMS can do (CRUD).It is used to perform crud operation.

1. Create
2. Read
3. Update
4. Delete

Because it is present between sql and your database, so it says that you want to create your database lets create it.

1. It is used to save your data at right place.
2. It secure your data
3. Used to do transection management


## Who is making the database software?

1. Microsoft has SQL server
2. My sql
3. Postgress
4. oracle

These are the big companies that makes the database software

All software are different but they all are operated with sql and used to perform same operation like CRUDE operation.


## How they are related to each other?

Suppose the DBMS is a chef and SQL is a customer and DATABASE is a type of cooking.

1. Chef can create any dish you want but every shef has different method to do same thing in their mind.
2. SQL , at the end if you want pizza then you only have to tell the Chef to give me a pizza some cheff are good and some are not it depends on prize.
3. Every DBMS(chef) have their different Recipy book and in interect with database differently. How to put the data in database and how to manage all these.
4. DBMS is connected with both database and on other hand it is controlled by SQL.
5. A signgle DBMS can handle multiple databases.


## DBMS?RDBMS?
DBMS is a seneral term to a software that is going to manage our database.
Database which is specially a relational database model is called RDBMS.

## 13 Rules of CoDD.
A databse management system is called as relational database management system if it follow these 13 rules.


Each and every database follow a specific way to store data is called as model each model has their rules to store data.

we use Relational Model and the key concept are like:
1. Relational Schema
2. Attribute
3. Degree
4. Cardinality
5. Tuple
6. Column
7. Relationa Key
8. Domain
9. Tables
10. Relation
11. Instance


# 1. Tables

What is a  table and why it is present in relational model. We will know hoe to break down data into entities or objects it could be student teacher and school and table is the representaion of that record. Each table has a name which is related to the data that we store in it. It is like an excellsheet and give it a name.

1. At top we have column and each column represents a specific data like id,name,lastname sex dob.
2. And We also have row in our table and each row represent a single peace of data for that table.eg 333 abhi kumar male.
3. If we compare it with excell sheet like excell we can use different name for different category of data and like excel having A B C we have specific things at top of table like ID Name sex. And like 1 2 3 4 present in excel we have single data in table.


## Column

Top to bottom line is called as column. Each column has a specific data to store and rach column has a name. 1 single column is called as column but what we call a collection of column We call it DEGREE of relation. The degree of user is id name sex.

### What a column can store 

The name of the column is called as domain/constraint like in DOB we can only store Date of birth . Here you are constraining the data that only put this data on this field.
In another way we can say about column that my table has these attributes with this constrains.
We can use any one of that.
Every table has columns and columns are also called as attributes and the collection of column is called as degree and every column may or may not specifically has to say that store this type of data.

## Rows/tuples
A line go from left to right is called as row.
A table is a collection of columns and rows. Columns are special because they have a specific type of data and each and every column has a constrain or a attribute domain. Row is used to inser a new data or entitity. A touple is nothing but a single record of data. 1 Touple means one single row of data. Each and every touple follow the column constrains. A collection of rows/topules are called as CARDNALITY.





















