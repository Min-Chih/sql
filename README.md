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
- AS : use AS to rename tables or name the new column, e.g.
```
SELECT p.post_title as "Post Title", u.user_nicename, count(*) as "Total Posts"
FROM posts AS p
JOIN users 
AS u ON u.ID = p.post_author
```
- UNION : combining data from two tables vertically
```
SELECT users.user_email
FROM users
UNION 
SELECT comments.comment_author_email
FROM comments
```

# CRUD
- C : Create
- R : Read
- U : Update
- D : Delete
