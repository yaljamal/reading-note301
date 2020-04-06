# SQL (Structure Query Languege )
it is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. 
1. SELECT queries 
>Select query for a specific columns
SELECT column, another_column, …
FROM mytable;
>Select query for all columns
SELECT * 
FROM mytable;
2. Queries with constraints
>Select query with constraints
SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
3. Select query with unique results
> SELECT DISTINCT column, another_column, …
FROM mytable
WHERE condition(s);
4. Select query with ordered results
> SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC;
5. Select query with limited rows
> SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset;