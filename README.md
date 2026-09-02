# LeetCode SQL Practice mostly for Premium or conceptual tougher problems

This repository contains my solutions, schemas, sample data, and notes for LeetCode SQL problems.
I made this for my reference but you can you  if find helpful. 

## Important: Running LeetCode SQL Problems

For **LeetCode Premium SQL problems**, the SQL editor/schema may not be directly available to me.

To practice these problems outside LeetCode, I use **DB Fiddle**.

### DB Fiddle Workflow

For each SQL problem:

1. Read the problem statement on https://leetcode.doocs.org/  or https://walkccc.me/LeetCode/problems/ .
2. Create the required tables in **DB Fiddle**.
3. Insert the sample data provided in the problem.
4. Write and test the SQL query.
5. Compare the result with the expected output.
6. Save the schema/data and final solution here for future reference.

### DB Fiddle

Use DB Fiddle to recreate the LeetCode database:

- **Schema SQL:** `CREATE TABLE` + `INSERT INTO`
- **Query SQL:** The solution query

Make sure to select the correct SQL dialect, especially **PostgreSQL** if the solution is written for PostgreSQL.

## Why DB Fiddle?

DB Fiddle allows me to recreate the LeetCode environment when the original SQL editor/schema isn't available.

It is particularly useful for:

- LeetCode Premium problems
- Practicing SQL independently
- Testing queries
- Working with multiple tables
- Experimenting with joins, CTEs, window functions, subqueries, etc.

## Problem Structure

Each problem should be saved using the following structure:

```text
## Problem #XXX - Problem Name

### Problem
[LeetCode problem link]

### Concepts
- JOIN
- GROUP BY
- CASE WHEN
- Window Functions
- CTE
- etc.

### DB Fiddle Schema

```sql
-- CREATE TABLE statements
-- INSERT INTO statements
