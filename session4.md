Tasks
1.Write an SQL query to find all restaurants in a table called Restaurants whose names end with 'Cafe' using the LIKE operator.
2.In a Flipkart-style Products table, use the BETWEEN operator to select all products with a price between 500 and 1500 rupees.
3.Write an SQL query to display all users from a Users table whose city is either 'Ahmedabad', 'Surat', or 'Vadodara' using the IN operator.
4.Given a table called Songs with columns song_name and artist_name, find all songs where the artist_name contains the letter sequence 'ar' anywhere in the name using the LIKE operator.<br><br><em><strong>Hint:</strong> Use wildcards on both sides of the pattern.</em>


**solution**
1. 
```
SELECT *
FROM Restaurants
WHERE Name LIKE '%Cafe';
```
2.
```
SELECT *
FROM Products
WHERE Price BETWEEN 500 AND 1500;
```
3.
```
SELECT *
FROM Users
WHERE City IN ('Ahmedabad', 'Surat', 'Vadodara');
```
4.
```
SELECT *
FROM Songs
WHERE artist_name LIKE '%ar%';
```