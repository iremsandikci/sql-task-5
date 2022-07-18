# sql-task-5
SELECT * FROM film
WHERE title LIKE '%N'
ORDER BY lenght DESC
LIMIT 5;
SELECT * FROM film
WHERE title LIKE '%N'
ORDER BY lenght 
OFFSET 5
LIMIT 5;
SELECT * FROM customer
WHERE store_id=1
ORDER BY last_name DESC
LIMIT 4;
