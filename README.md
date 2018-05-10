# SQL_practice

This is the SQL practice to let me understand how this works in a very efficient way! 

1. Creating a table and insert data into it. 

CREATE TABLE polos (id INTEGER PRIMARY KEY, name TEXT, quantity INTEGER);

INSERT INTO polos VALUES(1, "blue", 78,000);
INSERT INTO polos VALUES(2, "yellow", 67,895);
INSERT INTO polos VALUES(3, "white", 1,000,000);

SELECT * 
FROM polos;

/** result **/

id   name
1     blue
2     yellow
3     white



Practive:

Now, add three of your favorite books into the table.

CREATE TABLE favbooks(id INTEGER PRIMARY KEY, name TEXT, rating INTEGER);

INSERT INTO favbooks VALUES(1, "Blue Ocean SHift", 90);
INSERT INTO favbooks VALUES(2, "1984 Geroge Orwell", 99);
INSERT INTO favbooks VALUES(3, "Comman Sence", 76);

SELECT *
FROM favbooks;

/** result **/
DATABASE SCHEMA
favbooks 3 rows
id (PK) INTEGER
name TEXT
rating INTEGER
RESULTS
id	name	rating
1	Blue Ocean SHift	90
2	1984 Geroge Orwell	99
3	Comman Sence


Day2:

![screen shot 2018-05-10 at 6 41 56 am](https://user-images.githubusercontent.com/19642027/39866110-436fb244-541d-11e8-8a86-d56fca7793aa.png)
