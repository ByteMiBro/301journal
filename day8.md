Nate says programming is very much manipulating data.
I think of programming as its traditional definition- a way to make a one machine do somethi




****Notes****
CRUD.
DBSM(Data Base Management System), organized as a collection of data.
table based databases are most common, but documents are rapidly growing.
SQL(Structured Query Language)
specail lang for manipulating data.
contain clauses, expressions, and predicates:
[entire thing is one statement:
  [Update clauses
  [set clause = expression]
  [predicate:
    [where clause = 'name expression';
  ]
]

Query seclect statement(retreives data from one or more tables):

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
Use javascript to add behavoir to model.
create tables to model your objects.

TABLES
name table and create desired columns and datatypes. Changing the types on tables is dificult, changing the columns is easy. refer to the data modeling process.
Insert records. use INSERT statement:

INSERT INTO articles(title, author, etc.)
vALUES();

QUERYING DATA
use SELECT clause:

SELECT
FROM
Where
ORDER BY;

UPDATE RECORDS
always use a condition with update or it will end up everywhere.


DELETE RECORDS
