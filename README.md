# PostgreSQL

# SQL Statement fundamentals

```
1. SELECT * FROM actor;
2. SELECT first_name, last_name FROM actor;
3. SELECT DISTINCT first_name FROM actor;
4. SELECT DISTINCT(first_name) FROM actor;
5. SELECT DISTINCT(first_name, last_name) FROM actor;
6. SELECT COUNT(city) FROM city;
7. SELECT COUNT(DISTINCT(city)) FROM city;
8. SELECT first_name, last_name FROM actor WHERE first_name = 'Ed'
9. SELECT first_name, last_name FROM actor WHERE last_name = 'Chase' AND first_name = 'Jon';
10. SELECT * FROM rental WHERE customer_id >= 590 AND inventory_id > 4200 AND staff_id != 2
```

Note: 

1. DISTINCT - Unique values
2. COUNT - returns the number
3. Comparison Operators - greater than, less than, equal to
4. Logical Operators - Allows us to combine above comparison operators, these are the logical operators AND, OR, NOT

# COMPARISON OPERATORS
![comparison operators](https://github.com/revanth-karra/PostgreSQL/assets/52368773/a4d8b7be-e053-49a0-92d7-cadda2f92afa)


