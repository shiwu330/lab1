Задание 1
Вывести имена пользователей и даты приёма на работу женщин-продавцов.


```sql
SELECT username, hire_date
FROM salespeople
WHERE gender = 'Female'
ORDER BY hire_date
LIMIT 10;
```

Результат выполнения
<img width="248" height="450" alt="1 jpg" src="https://github.com/user-attachments/assets/e5d26658-99f1-419d-b564-158510b33787" />

Задание 2
Найти все продажи после 1 января 2023 года.
SQL-запрос

```sql
SELECT *
FROM sales
WHERE sales_transaction_date > '2018-01-01';
```

Результат выполнения
<img width="1390" height="754" alt="2 jpg" src="https://github.com/user-attachments/assets/a68f823c-a038-4c57-bc5b-de81c1f24b72" />

Задание 3
Получить список email клиентов из штата Флорида.
SQL-запрос

SELECT email
FROM customers
WHERE state = 'FL'
ORDER BY email;

Результат выполнения
<img width="1514" height="1368" alt="3 jpg" src="https://github.com/user-attachments/assets/03c37430-ec2d-4f79-b82d-309979e0f10c" />

Задание 4
Получить список клиентов из Нью-Йорка.
SQL-запрос

SELECT last_name, first_name, email
FROM customers
WHERE state = 'NY' AND city = 'New York City'
ORDER BY last_name, first_name;

Результат выполнения
<img width="898" height="526" alt="4 jpg" src="https://github.com/user-attachments/assets/31cfb726-afde-4730-b1ee-12e5c0f61604" />

Задание 5
Вывести всех клиентов, у которых указан номер телефона.
SQL-запрос

SELECT *
FROM customers
WHERE phone IS NOT NULL
ORDER BY date_added;

Результат выполнения
<img width="2112" height="352" alt="5 jpg" src="https://github.com/user-attachments/assets/8bdf8fa8-7953-4b53-8381-ec60b5a88823" />
