# Bookstore-Information-Management-System
Overview
Bits & Books needs a simple information management system and database to support their inventory and sales operations. 
The specification document and sample data will provide you with many of the user requirements.

In addition, to receive full credit for your project you will be required to come up with some extensions that expand onthe requirements here and provide new functionality beyond the scope of the basic requirements. 
 
Final Project Document
The final report id a professionally presented, well-organized, typed document, and a complete SQL database. This projecct include a Table of Contents file named README.txt that explains the layout of your files, including where to find each of the following files in the file structure.

Part I   –   The Final ReportYour final document will include a   relational database schema, entity relationship diagram, SQL queries, and reports, as indicated below.

Section 1   -  Database Description 
A database description document that contains the following information about your database (compiled from yourcompleted and revised checkpoints):

a)A professionally presented, well-formatted ER-model that reflects the updates you have made during the semester.  Do not submit a   hand-drawn diagram.

b)A professionally presented, well-formatted relational schema for the database.  This schema must be annotated with the primary key for each table, all foreign keys on all tables, and all functional dependencies on all tables.  Make sure that connections between FKs and PKs are clear.  

c)For each table, give a brief description of the level of normalization achieved for that table.  If the table is not in BCNF, explain why. 

d)A description of each of the indexes that you have chosen to implement on your database, along with rationale for each.

e)For each view that you have implemented, provide the following:
  i. A brief description in English of what this view produces, and why it   would be useful.
  ii. Relational algebra expression to produce this view.
  iii. SQL statements to produce the view.
  iv. Sample output from the view, with 5-10 lines of data records shown. 
  
f)A professionally presented description of three sample transactions useful for your database. This should include the sample SQL code for each transaction as well as an English language description of what “unit of work” the transaction represents. Remember –   a   transaction is    a   sequence of SQL statements taken as a   unit – this can be reads and writes together or just a   sequence of writes. One example of a   sample transaction you might want to consider is    the user making changes to an order –   what might need to be considered a   transaction in that case?


Section 2   -  User Manual
A user manual describing the usage of your database, for use by developers who are going to be writing code to use your database. Your manual should include:

a)For each table, explain what real world entity it   represents.  Provide a   description of each attribute, including its data type and any constraints you have built-in.

b)The sample SQL queries that you provided in Checkpoints 03 and 02. These queries should be organized andpresented neatly and professionally. Each query should include:
  i.An English language description of what the query should be returning
  ii.The correct relational algebra syntax of the query
  iii.The equivalent SQL query

c)INSERT syntax for adding new books, publishers, authors and customers to your system.  If there are dependencies in your system that require multiple  records to be added to tables in a specific order to add one of these items, make sure you clearly indicate what those restrictions are. 

d)DELETE syntax for removing books, publishers, authors and customers  from your system. Again, indicate anydependencies that exist on the order that the steps in your DELETE must take. In addition, provide an example set of DELETE statements for each entity in your database.


Section 3   -  Graded Checkpoint Documents
An appendix to the final report that MUST contain all of your original, graded checkpoint documents organized in a   neat and professional manner. For each checkpoint that required a   revision you MUST include a   revision for that checkpoint.  This revision may be a pointer to where in the final database document the “fixed”  version of the checkpoint resides (“See Section X Page Y   for the new relational model  diagram” for example).


Part II –   The SQL Database
1.A binary version of your database, suitable for opening using either the sqlite3 command line tool or the Firefox SQLite Admin tool.

2.SQL CREATE.  A text file containing all of the scripts needed to create your database schema on an empty database. This file should be properly commented and should execute properly if pasted into an sqlite command prompt (or loaded from the command line tool). These scripts should include all indexes and views created on your database.

3.DATA FILES. A set of text files containing the data to be loaded into your database. These files, when used with the table creation scripts above, should be able to recreate your database from scratch if your binary file is corrupted or lost. Make sure you provide instructions on how to use these scripts and files in a   separate text file.

4.SQL QUERIES. A text file containing all of the SQL queries used in your final report from Part I.   All of these queries must be in a form where they can be run over your database through a simple cut and paste into the admin tool or the sqlite3 command line tool. In addition, make sure that these queries are completely commented so that it   is clear where the query comes from in your final report writeup.

5.SQL INSERT/ DELETE.  A text file containing all of the sample INSERT and DELETE statements provided in your  user manual, suitable for pasting into a command prompt and testing the result on your database.


SQLite.
