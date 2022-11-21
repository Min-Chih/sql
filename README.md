# MySQL
A repository to practice MySQL

# Set up with MAMP
- simply set up with [MAMP](https://www.mamp.info/en/mac/)

# Basic query of SQL
- SELECT * FROM table_name
- WHERE : to set the criteria to find certain objects
- ORDER BY (ASC/DESC) : similar to "sort by" on shopping sites
- LIMIT : limit the result amount
- OFFSET : start after
- INSERT INTO table_name (column_name) : add new data to a table, followed by VALUE (data)
- UPDATE table_name SET column_name WHERE the object you want to change
- DELETE FROM table_name WHERE data you want to delete
- JOIN : yuse JOIN to merge two tables to get more data, e.g.
```
SELECT posts.post_title, users.user_nicename
FROM posts
JOIN users ON users.ID = posts.post_author
```

# CRUD
- C : Create
- R : Read
- U : Update
- D : Delete
