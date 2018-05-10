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
