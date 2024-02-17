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

It is a old model primarily used by IBM in 1960-1970 it is unefficient way to store data thats why people donot use it now a days. It has a tree like structure having a single child and 






