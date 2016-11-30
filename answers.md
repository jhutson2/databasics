#Question 1
SQL:select count(*) from users;
Answer: 50

#Question 2
SQL:select price from items order by price desc limit 5;
Answer:9984, 9859, 9790, 9390, 9341

#Question 3
SQL:select min(price) from items where category = 'Books'
Answer: 1496

#Question 4
SQL:select id from addresses where street = '6439 Zetta Hills' and city = 'Willmouth' and state = 'WY', select first_name from users where id = 43
Answer:Kyra

#Question 5
SQL:select id from users where first_name = 'Virginie' and last_name = 'Mitchell'
update addresses set city = 'New York', state = 'NY', zip = '10108' where id = 39;
Answer: 39 |        37 | 7503 Cale Grove         | New York            | NY      | 10108

#Question 6
SQL: select sum(price) from items where category = 'Tools'
Answer:7383

#Question 7
SQL:select sum(quantity) from orders
Answer: 2125

#Question 8
SQL: select sum(price * quantity) from items, orders where category = 'Books'
Answer:48241750

#Question 9
SQL: INSERT INTO users VALUES(51, 'Jonathan', 'Hutson', 'J@gmail.com')
INSERT INTO orders VALUES(388, 51, 90, 7, '2015-02-09 00:40:31.268450')
