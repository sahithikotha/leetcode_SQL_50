
# 📊 SQL Practice: SELECT Basics – SQLZoo

This repository contains my personal SQL learning journey using [SQLZoo](https://sqlzoo.net/) tutorials. It includes notes, solved examples, and query experiments based on:

- 📘 [SELECT Basics](https://sqlzoo.net/wiki/SELECT_basics)
- 🧪 [SELECT Quiz](https://sqlzoo.net/wiki/SELECT_Quiz)

---

## 🧠 What I’ve Learned

1️⃣ SELECT with WHERE

Goal:Get data based on specific conditions

Example: Show the population of Germany  

SELECT population FROM world
WHERE name = 'Germany';

2️⃣ SELECT with IN

Goal: Get values from a list of possible values

Example: Show the name and population for Sweden, Norway, and Denmark

SELECT name, population FROM world
WHERE name IN ('Sweden', 'Norway', 'Denmark');

3️⃣ SELECT with BETWEEN

Goal: Get data in a specific numeric range

Example: Show countries with an area between 200,000 and 250,000 sq km

SELECT name, area FROM world
WHERE area BETWEEN 200000 AND 250000;


## 🧪 SQLZoo SELECT Quiz – Questions and Answers

### Question 1:
Select the code which produces this table  
**name population**  
Bahrain 1234571  
Swaziland 1220000  
Timor-Leste 1066409  

```sql
SELECT name, population
  FROM world
 WHERE population BETWEEN 1000000 AND 1250000



