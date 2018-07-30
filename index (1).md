
# Selecting Data Lab

In this lab, we will use SQLite browser to practice querying a database with various `SELECT` statements using `nasa` database that we created in the previous lab. 

## Objectives

1.  Use the `SELECT *` statement to pull all values from a table
2.  Use `SELECT` with specific `column_name(s)` to pull only certain columns from a table
3.  Use `WHERE` and conditionals to pull more specific information from a table

We will query from the same `planets` table featured in the Solar System lab. Here is the information which we provided:

|name   |color |num_of_moons|mass|rings|
|-------|-------|-------|-------|-------|
|Mercury|gray   |0      |0.55   |no     |
|Venus  |yellow |0      |0.82   |no     |
|Earth  |blue   |1      |1.00   |no     |
|Mars   |red    |2      |0.11   |no     |
|Jupiter|orange |67     |317.90 |no     |
|Saturn |hazel  |62     |95.19  |yes    |
|Uranus |light blue|27  |14.54  |yes    |
|Neptune|dark blue|14   |17.15  |yes    |

## Queries

Go to 'Execute SQL' tab in SQLite browser and execute all of the following queries.

* Return all of the data featured in the `planets` table

* Return the name and color of each planet

* Return all columns for each planet whose mass is greater than 1.00

* Return the name and mass of each planet whose mass is greater than or equal to 1.00

* Return the name and color of each planets that has more than 10 moons

* Return the planet that has at least one moon and a mass less than 1.00

* Return the name and color of planets that have a color of blue, light blue, or dark blue

## Summary

Great work! In this lab we practiced writing select statements that query a single table to get specific information as long as it meets the condition we provided. 
