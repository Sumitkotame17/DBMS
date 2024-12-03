 Practical 1:
For a given set of relation schemes, create tables and perform the following Simple
Queries, Simple Queries with Aggregate functions, Queries with Aggregate functions (group
by and having clause).
---------  1.Create 2.Alter 3.Drop 4.Insert 5.Update 6.Delete
---------  Aggregate 1.Ave() 2.Count() 3.First() 4.Max() 5.Min() 6.Last()
Syntax:1. Create a table 
CREATE TABLE table_name (column_name datatype constrant, colo.....)
Example: 
Create table TY (Rl int not null primary key, sname varchar(25) not null);

Syntax:2. Alter a Table
Alter Table table_name rename column old_name TO new_name
Example:
ALTER TABLE TY rename column Rl to Roll_No;

Syntax:3.Drop
ALTER TABLE table_name DROP COLUMN column_name;
Example:
ALTER TABLE TY Drop column Roll_No;

Syntax:4.Insert data into table
INSERT INTO TY values("Ram");    ---- single values
INSERT INTO TY VALUES ("JOY", "ROY", "JOYBOY");  ------ Multiple values

Syntax: 5 Update the table
UPDATE table_name SET column1 = value1, column2 = value2, ...
WHERE condition;
Example:
UPDATE TY SET sname = "JOY2"
WHERE Roll_No = 5;

Syntax: 6 Delete a table data
DELETE FROM table_name WHERE condition;
DELETE FROM TY WHERE Roll_No = 14;

########################################################################



