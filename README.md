📚 Library Management System – SQL Database Project
📌 Project Overview

This project is a Relational Database Management System (RDBMS) implementation of a Library Management System using SQL.

The system is designed to manage:

Books

Authors

Publishers

Library Branches

Borrowers

Book Copies

Book Loans

It demonstrates strong understanding of database design, normalization, primary & foreign keys, joins, aggregations, and complex queries.



🎯 Project Objective

The objective of this project is to:

Design a normalized relational database schema

Establish relationships between multiple entities

Implement foreign key constraints

Perform real-world SQL queries using joins and aggregations

Extract meaningful insights from relational data



🛠️ Technologies Used

🗄️ MySQL

💻 SQL (DDL & DML)

🔗 Relational Database Concepts

📊 Joins & Aggregate Functions

🔐 Primary & Foreign Key Constraints

🗂️ Database Schema Design

The project consists of the following tables:

1️⃣ Publisher

Stores publisher details.

Publisher Name (Primary Key)

Address

Phone

2️⃣ Books

Stores book information.

Book ID (Primary Key)

Title

Publisher Name (Foreign Key)

3️⃣ Book Authors

Maps books to authors.

Book ID (Foreign Key)

Author Name

4️⃣ Library Branch

Stores branch information.

Branch ID (Primary Key)

Branch Name

Address

5️⃣ Book Copies

Stores number of copies available at each branch.

Book ID (Foreign Key)

Branch ID (Foreign Key)

Number of Copies

6️⃣ Borrower

Stores borrower details.

Card Number (Primary Key)

Name

Address

Phone

7️⃣ Book Loans

Tracks borrowed books.

Book ID (Foreign Key)

Branch ID (Foreign Key)

Card Number (Foreign Key)

Date Out

Due Date


🔗 Database Relationships

One publisher → Many books

One book → Many authors

One branch → Many book copies

One borrower → Many book loans

One book → Many loans

One branch → Many loans

Foreign key constraints ensure referential integrity across the database.



📊 SQL Queries Implemented

The project includes real-world SQL queries such as:

✅ 1. Total copies of a specific book in a specific branch

Example:
“How many copies of The Lost Tribe are available in the Sharpstown branch?”

✅ 2. Total copies of a book in each branch
✅ 3. Borrowers who have not checked out any books
✅ 4. Books loaned from a specific branch with a specific due date
✅ 5. Total number of books loaned from each branch
✅ 6. Borrowers who have more than 5 books checked out
✅ 7. Books authored by "Stephen King" and copies available in the Central branch

These queries demonstrate:

INNER JOIN

LEFT JOIN

GROUP BY

HAVING

Aggregate functions (COUNT, SUM)

Subqueries

Foreign key usage

Data filtering



🚀 Key Highlights

✔ Complete relational schema design
✔ Proper use of Primary & Foreign Keys
✔ Implementation of ON DELETE and ON UPDATE constraints
✔ Complex JOIN operations
✔ Aggregate functions with GROUP BY & HAVING
✔ Subqueries for conditional retrieval
✔ Real-world business logic queries



💡 Skills Demonstrated

Database normalization

Relational schema design

Query optimization

Data integrity enforcement

Complex SQL querying

Analytical thinking using SQL



🔮 Future Enhancements

Add stored procedures

Implement triggers

Create views for reporting

Add indexing for performance optimization

Develop front-end interface (Web-based library system)



🎯 Conclusion

This project demonstrates strong foundational knowledge in SQL and relational database management. It showcases the ability to design structured databases, enforce referential integrity, and write advanced queries to solve real-world business problems in a library management system.
