# SQL-BASICS.md



## Standardbefehle
```sql


-- Aggregatfunktionen --

/*

SELECT AVG (age) from Customers -- Durchschnitt
SELECT COUNT (*) FROM Customers WHERE age > 25;
SELECT MAX (amount) AS 'Größte Bestellung', AVG (amount) AS DURCHSCHNITT from Orders;

*/
-- GROUP BY --

/*

-- SELECT country, AVG (age) FROM Customers GROUP BY country;
-- SELECT * FROM Orders GROUP BY item

*/

-- JOINS --

SELECT * 
FROM Customers C -- Variable C zuordnenn
JOIN Orders O ON C.customer_id = O.customer_id;


```
