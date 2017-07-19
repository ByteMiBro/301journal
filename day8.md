****Thoughts on SQL****
Fuck yeah! Mind blown!
-- I have often in my life been a data driven person, so it is nice to finally get to one of the more data driven sides of programming.  


****A Fictional Discussion with Nate on how to view programming****
Nate says programming is very much a manipulation of data. I do see this definition as a subset of programming. However, I think of the umbrella of programming as its traditional definition- a way to make a one machine do several things without completely rebuilding the machine.


****Description of Adapting my Thought Process****
Over the time of this class I've Had to adapt my thought processes. My traditional style of thinking is to work back from the problem to get to solution one by defining the problem, and figure out what that solution will be based on the definitions of the attributes of the solution that align with the underlining concept of the problem. This requires more thinking and deep understanding with less action. I developed this style of thinking from the early days of my childhood - not all the reasons are known to me- but, because I see thinking as a better and a more fun way of doing things, which is usually Why I take rare actions, but action means more to me. However, our culture's philosophy is centered around a more goal and time oriented way of thinking, which is fucking hilarious considering...There is a bit of a catch 22, I learn by creating problems for myself, and then creating the solutions to those problems myself, so that I have a personal index of values and definitions of the material I am learning. But In the culture we live in at the moment, in order to prove you know something under a certain time and human constraint, I have to solve problems created for me, with solutions that have an expected and pre-setup model. While the culture's way is nice to stay on base with what the community around us knows and expects us to know, this will eventually subside as it doesn't let a large amount of ground breaking work happen in a small period of time- which will be needed as the population increases, our civilization spreads, and technology changes faster.


****Notes****
CRUD.
DBSM(Data Base Management System), organized as a collection of data.
table based databases are most common, but documents are rapidly growing.
SQL(Structured Query Language)
special lang. for manipulating data.
contain clauses, expressions, and predicates:
[entire thing is one statement:
  [Update clauses
  [set clause = expression]
  [predicate:
    [where clause = 'name expression';
  ]
]


Query select statement(retrieves data from one or more tables):

SELECT isbn,
title,
price,
price*0.06 sales_tax
FROM Book
Where price > 100.00
ORDER BY title;


DDL(Data Definition Language) manages the table and index structure. lets youc hannge the definitons of the data. you change the data base not the data.
DDL statement:

CREATE (url)
ALTER (url)
DROP (url)
TRUNCATE (url)

or

CREATE TABLE example(
  col1 INTEGER PRIMARY KEY
  column2 VARCHAR(50)
  col3 DATE NOT NULL,
  );
ALTER ()
DROP ()
TRUNCATE ()


Data type are a constraint on the kind of data a column can have.
floating pt # vs decimals and big long integers vs fixed pt.
flpt# generally stored as approximations


MODEL
models are simplified description of real world object. A database table is a simple model.
Use JavaScript to add behavior to model.
create tables to model your objects.


TABLES
name table and create desired columns and datatypes. Changing the types on tables is difficult, changing the columns is easy. refer to the data modeling process.
Insert records. use INSERT statement:

INSERT INTO articles(title, author, etc.)
VALUES();

QUERYING DATA
use SELECT clause:

SELECT
FROM
Where
ORDER BY;

UPDATE RECORDS
always use a condition with update or it will end up everywhere.


DELETE RECORDS
