# Task-3-Writing-Basic-SELECT-Queries


-- For today's task: Writing Basic SELECT Queries 
-- SELECT Command on the table data......

select * from books;
-- selecting * drags the total data fromm table... 

select title, total_copies from books;
-- above query drags the data in columns from titla and total_copies, as we specified the column_names....

-- Find all books, sorted alphabetically .... 
 select * from books 
 where genre = 'fiction'
 order by title asc;
 
-- find the data from table with book_id with 3 and 5...
 select * from books
 where book_id between 3 and 5;
 
-- find the books with names starting in 'The'......
 select * from books
 where title like 'The%';
 
 -- find the data from order by author_id.....
 select * from books 
 order by author_id;
 
 -- get books from publisher_id with 03 or 05.....
 select * from books
 where publisher_id = 03 or publisher_id = 05; 
  
-- Get the data from table order by author_id with limit 2.....
 select * from books
 order by author_id limit 2;
 
 -- Get the data from talbe order by author_id in desc order.....
  select * from books
 order by author_id desc limit 2;

-- Outcome :
-- How to retrieve data from a table.
-- How to apply filters and conditions.
-- How to sort and limit the results.
