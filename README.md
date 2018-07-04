//# sql-1-afternoon//

/* create table Person (
  ID integer primary key autoincrement,
  Name string,
  Age integer,
  Height integer,
  City string,
  FavoriteColor string
  ); */
  
/*  insert into Person (Name, Age, Height, City, FavoriteColor)
  values 
  	('Jeremy', 40, 175, 'Seoul', 'Black'),
	('Scala', 40, 172, 'Seoul', 'White'),
    ('Ema', 36, 180, 'Mwanza', 'Red'),
    ('Rachel', 35, 165, 'Mwanza', 'Blue'),
    ('Dan', 41, 174, 'Chiang Mai', 'Gray'); */
    
/* select * from Person order by height; */

/* select * from person order by height desc; */

/* select * from person order by age desc; */

/* select * from person where age > 20; */

/* select * from person where age = 18; */

/* SELECT * FROM person WHERE age > 20 AND age < 30; */

/* SELECT * FROM Person WHERE age != 27; */

/* SELECT * FROM Person WHERE favoritecolor = 'Red'; */

/* SELECT * FROM Person WHERE favoritecolor != 'Red' AND favoritecolor != 'Blue'; */

/* SELECT * FROM Person WHERE favoritecolor = 'Orange' OR favoritecolor = 'Green'; */

/* SELECT * FROM Person WHERE favoritecolor IN ('Orange', 'Green', 'Blue'); */

/* SELECT * FROM Person WHERE favoritecolor IN ('Yellow' , 'Purple'); */




/* create table Orders (
  PersonID integer primary key autoincrement,
  ProductName string,
  ProductPrice float,
  Quantity integer
  );
 */

/* INSERT INTO Orders (PersonID, ProductName, ProductPrice, Quantity)
values (10, 'T-Shirt', 15.99, 2),
(12, 'Jeans', 45.99, 1); */

/* INSERT INTO Orders (ProductName, ProductPrice, Quantity)
values ('Sandals', 15.99, 2); */

/* INSERT INTO Orders (PersonID, ProductName, ProductPrice, Quantity)
values (4, 'Socks', 105.99, 2); */

/* INSERT INTO Orders (ProductName, ProductPrice, Quantity)
values ('Sunglasses', 10.99, 1); */


/* SELECT * FROM orders; */

/* SELECT SUM(Quantity) FROM Orders; */

/* SELECT SUM(ProductPrice * Quantity) FROM Orders; */

/* SELECT SUM(ProductPrice * Quantity) FROM Orders WHERE PersonID = 4; */

/* SELECT * FROM ARTIST; */

/* INSERT INTO Artist(Name)
VALUES ('The Boogie Beats'), ('Wallpaper Nest-Frogs'), ('The Chick Peas'); */

/* SELECT name FROM Artist ORDER BY name DESC LIMIT 10; */

/* SELECT name FROM Artist ORDER BY name LIMIT 5; */

/* SELECT * FROM Artist WHERE Name like 'Black%'; */

/* SELECT * FROM Artist WHERE Name LIKE '%black%'; */

/* SELECT FirstName, LastName FROM Employee WHERE City = 'Calgary'; */

/* SELECT FirstName, LastName, MAX(BirthDate) FROM Employee; */

/* SELECT FirstName, LastName, MIN(BirthDate) FROM Employee; */

/* SELECT * FROM Employee WHERE reportsto = 2; */

/* SELECT COUNT(*) FROM Employee WHERE city = 'Lethbridge'; */

/* SELECT * FROM Invoice; */

/* SELECT COUNT(*) FROM Invoice WHERE BillingCountry = 'USA'; */

/* SELECT MAX(Total) FROM Invoice; */

/* SELECT MIN(Total) FROM Invoice; */

/* SELECT * FROM Invoice WHERE Total > 5; */

/* SELECT * FROM Invoice WHERE Total < 5; */

/* SELECT * FROM Invoice WHERE BillingState IN ( "CA", "TX", "IN" ); */

/* SELECT AVG(Total) FROM Invoice; */

/* SELECT SUM(Total) FROM Invoice; */

