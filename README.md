Online Library Management System

Overview
The Online Library Management System is a web-based application that allows users to browse, search, and read books online. The system is divided into two main roles: Admin and User. Admins can manage books, authors, categories, and issue books to users, while users can browse the available books, read them, and view their borrowing history.

Features

Admin Features:

Login/Logout
Add, Edit, and Delete Books, Authors, and Categories
Issue and Return Books
Manage Registered Students
View Issued Books and Borrowing History

User Features:

Register/Login/Logout
Browse and Search Books
View Borrowing History
Read Books Online

Technologies Used

Front-End: Bootstrap for responsive design
Back-End: PHP for server-side logic
Database: MySQL for data storage
Languages: PHP, CSS, JavaScript

Prerequisites

Before running the project, ensure that the following software is installed:

XAMPP or WAMP (or any local server running Apache and MySQL)
PHP 7.x or higher
MySQL 5.x or higher

Configure the database connection:

In the project folder, open the file dbconfig.php.
Update the database name, username, and password according to your local server setup.

File Structure
admin/: Contains admin-related functionalities such as managing books, authors, and categories.

dashboard.php: Admin homepage.
add-book.php: Form to add new books.
edit-book.php: Form to edit existing books.
manage-books.php: Manage all available books.

user/: Contains user-related functionalities for browsing and reading books.

index.php: User login page.
reg-students.php: User registration form.
get_book.php: Display list of available books.
dbconfig.php: Configuration file for connecting to the MySQL database.

Admin Login Credentials
To access the admin panel, use the following default login credentials:

Username: admin
Password: admin123
