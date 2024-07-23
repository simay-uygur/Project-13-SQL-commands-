# Project-13-SQL-commands-
These are assignments given in Patika Java Intermediate course.


The given query tasks are

List the distinct values in the replacement_cost column in the film table.
How many distinct values are there in the replacement_cost column in the film table? -> Answer: 21
How many movie titles (title) in the film table start with the letter 'T' and have a rating equal to 'G'? -> Answer: 9
How many country names (country) in the country table are exactly 5 characters long? -> Answer: 13
How many city names in the city table end with the letter 'R' or 'r'? -> Answer: 33


```

-- Task1
SELECT DISTINCT replacement_cost FROM film;

-- Task 2
SELECT COUNT(DISTINCT replacement_cost) FROM film;

-- Task 3
SELECT COUNT(*) FROM film 
WHERE title LIKE 'T%' AND rating = 'G';

-- Task 4
SELECT COUNT(*) FROM country
WHERE country LIKE '_____';

-- Task 5
SELECT COUNT(*) FROM city
WHERE city ILIKE '%r';


```
