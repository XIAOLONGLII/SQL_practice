# SQL_practice

This is the SQL practice to let me understand how this works in a very efficient way! 

1. Creating a table and insert data into it. 

<img width="1150" alt="screen shot 2018-05-10 at 11 31 55 am" src="https://user-images.githubusercontent.com/19642027/39878315-0ab4dc12-5446-11e8-9377-f3db9ad95c45.png">
<img width="936" alt="screen shot 2018-05-10 at 11 33 07 am" src="https://user-images.githubusercontent.com/19642027/39878317-0ac4b2ea-5446-11e8-863f-1e82c1c9fc75.png">
<img width="1147" alt="screen shot 2018-05-10 at 11 33 18 am" src="https://user-images.githubusercontent.com/19642027/39878318-0acde0b8-5446-11e8-9585-3b94641f51b7.png">


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
