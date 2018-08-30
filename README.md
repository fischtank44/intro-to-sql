# intro to SQL  

## short URL to this repo [sqlrepo.sage.codes](https://github.com/sagecodes/into-to-sql)

## Do these things first!

- Open your web browser. I'll be using [chrome](https://www.google.com/chrome/), but feel free to use your whatever your favorite browser is. 
- We're going to use an [online editor and database](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) for SQL from [W3Schools](https://www.w3schools.com/). 
 
## What this workshop is

A super friendly introduction to SQL No previous experience expected! 

You can't learn EVERYTHING in ~2 hours. But you can learn enough to get excited and comfortable to keep working and learning on your own! Come to our almost weekly code hours [meetups](https://www.meetup.com/Learn-Code-Seattle/events/) to ask questions if you get stuck and show off what you've been working on!

- This course is for absolute beginners
- Ask Questions!
- Answer Questions!
- Help others when you can
- Its ok to get stuck, just ask for help!
- Feel free to move ahead
- Be patient and nice


## About me:
Hello I'm [Sage Elliott](http://sageelliott.com/). I'm a Technology Evangelist here at Galvanize! Previously I've worked as a software and hardware engineer with Startups and Agencies in Seattle, WA and Melbourne, FL. I love technology! I'm currently learning more about how to build AI and VR projects! 

- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)


## About you!

Give a quick Intro!

- Whats your name?
- Whats your background?
- Why are you interested in SQL and data?

## Why is data important

Data = infomation | Imagine a phonebook with hundeds of people and businesses

Databases = computerized storage of data | imagine an organized digital collections of people and businesses.

- Dynamic sites
	- Facebook
	- Gmail 
- Mobile apps
	- Uber
	- Snapchat 
- Data for reccomndations
	- Netflix
	- Amazon products
- Item Tracking
	- Library
	- UPS

Some Professional Roles that work with databases:

- Web Developer
- Data Analysis
- Data Science
- Database Admin


## What is SQL?

Pronounced `S.` `Q.` `L.` or Sequel. Eitherway is fine!

SQL stands for Structed Query Language

Reading Data from a database is known as Querying.


- DDL Data DefnitionLanguage
- DML DataManipulationLanguage
- DCL DataControlLanguage


Common SQL Databases:

Each of these databases can be Queried using the SQL programming Language.
- MySQL
- PostgreSQL
- Microsoft SQL
- SQLie 
- Oracle

*Note:* There are some slight differences to each database


Other databases 
These are often referred to noSQL databased

- GraphQL
- MongoDB
- Couchbase
- Redis



#### Where SQL used?

#### WHat is an ORM?

ORM stands for Object relation model

#### What is noSQL?




## What is a relational database?

Two major components in a database

Data(Information Stored) and Schema(How the data is organized)

Sections are called tables


##### Tables
You can think of tables as speadsheets:


| Column ↓  | Column ↓   |  Column ↓  |
|---|---|---|
| Row →   |   |   | 
| Row →   |   |   |
| Row →   |   |   | 

##### Table Organizaton

Usually seperate tables contain data for a specific type of thing:

If we look at [w3schools](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) again you can see all the different tables in the database

![alt text](img/tables.png "Tables")


Orders table:

| OrderID  |  	CustomerID | 	EmployeeID  | OrderDate  |  ShipperID |
|---|---|---|---|---|
| 10248  | 90  |  5 | 1996-07-04  | 	3  |
| 10249  |  81 |  6 |  1996-07-05 |  1 |
|  10250 | 34  | 4  |  1996-07-08 |  2 |


Products Tables:

| ProductID  | ProductName  | SupplierID  | CategoryID  |  Unit | Price|
|---|---|---|---|---|---|
| 1  |  Chais |  1 |  1 |  10 boxes x 20 bags | 18  |
|  2 |  Chang |  1 |  1 | 24 - 12 oz bottles  | 19 |
|  3 | Aniseed Syrup  | 1  | 2  |  12 - 550 ml bottles | 10  |


Filter data table example:

Rearrange table example:

*Note:* This isn't actually changing the database. You're just choosing what and how to look at the data.

The same database can be used in diffent ways acrros applications at the same time.

- Website could be pulling data to show your purchase history
- An analyst could be pulling the data to learn what the most popular item is

### Data types

data types for table columns are defined in the schema

The most common data types are:

- Text (Names, Desciptions)
- Numeric (cost, age, weight, quantity)
- Dates (Dates and time)

Its inportant to have the correct data type for your data. This ensures that sorting and calculations work properly.

*Note:* Data types may change depenidng on which database you're using.

## lets do some SQL!

Visit [w3schools](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) and navigate to the SQL section.


#### Filtering

Lets take a look at all the categories of prducts we have

`SELECT * FROM Categories`

Lets see how many customers do we have?

`SELECT COUNT(*) FROM Customers`

Lets take a look at our orders

`SELECT * FROM Orders`

Lets rearrange the orders by date

```
SELECT * FROM Orders
ORDER BY OrderDate DESC
```

Neat! Lets see which customer made that top order! We will take the value from the CustomerID column.

```
SELECT * FROM customers
WHERE CustomerID = '66'
```



#### Reranging

#### Math

- Sum
- AVG
- Count


#### Joins

#### Group by

Import first step is to understand your data.

- How is it structered?
- What does it represent?



## Questions
Knowing what we just learned lets try to answer some questions about our data!

- What is the most popular item?
- Which customer has spent the most money?
- What was the largest order?
- Whats the most popular category?
- Which cusomer has returned the most?


## Keep Learning!!!

challenges:


Reosurces:
- [w3schools](https://www.w3schools.com/sql/)
- [sqlzoo](https://sqlzoo.net/)
- [Datacamp](https://www.datacamp.com/courses/intro-to-sql-for-data-science)
- [mimo](https://getmimo.com/) Mobile app

## Upcoming Events

## Upcoming Courses



## Answers
Answers to the Questions Section:

- Q: What is the most popular item?
	- A:
	- Query: `bjblblnlnnlnlk`
- Which customer has spent the most money?

- What was the largest order?

- Whats the most popular category?

- Which cusomer has returned the most?
