# EXPERIMENT 3

## Exercise 1 - Find all the Toy Story movies
```sql
SELECT * FROM movies WHERE title LIKE 'toy Story%';
```
---
## Exercise 2 - Find all the movies directed by John Lasseter
```sql
SELECT * FROM movies WHERE director = 'John Lasseter';
```
---
## Exercise 3 - Find all the movies (and director) not directed by John Lasseter
```sql
SELECT title , director FROM movies WHERE director NOT LIKE 'John Lasseter';
```
---
## Exercise 4 - Find all the WALL-* movies
```sql
SELECT * FROM movies WHERE title LIKE 'WALL-%';
```
---

