# lab1
SELECT username
FROM salespeople
WHERE gender = 'Female'
ORDER BY hire_date
LIMIT 10;

<img width="1110" height="798" alt="image" src="https://github.com/shiwu330/lab1/blob/main/img/1.jpg.png" />

SELECT username, hire_date
FROM salespeople
WHERE gender = 'Female'
ORDER BY hire_date
LIMIT 10;

SELECT *
FROM sales
WHERE sales_transaction_date > '2023-01-01';

SELECT email
FROM customers
WHERE state = 'FL'
ORDER BY email;

SELECT last_name, first_name, email
FROM customers
WHERE state = 'NY' AND city = 'New York City'
ORDER BY last_name, first_name;

SELECT *
FROM customers
WHERE phone IS NOT NULL
ORDER BY date_added;
