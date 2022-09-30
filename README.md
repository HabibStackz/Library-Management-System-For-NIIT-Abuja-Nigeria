# Library-Management-System-For-NIIT-Abuja-Nigeria

Library Management System Project in Python and SQlite3
Python Library Management System is crucial software that can be used in schools and college libraries to add new books to the collection, issue books to students, and keep track of books that are returned. This project is developed in the Python programming language using SQLite3 for the database at the backend.
 
Importance of Library Management System Project
The Library Management System assists in the management of information about books issued to students and books available in the library. This aids librarians in locating any particular book in the library at any given time. 
Library Management System Project in Python Beneficiaries
•	Schools / Universities
•	Libraries

A Library Management System is capable of handling all aspects of book publishing. It keeps track of all the facts and details about the book’s release. This implements CRUD (Create, Read, Update, and Delete) operations for data management.

What is it going to do actually?

This Library Management System will consist of:
1. 	Admin Panel – where only authorized admins will be logged in for managing the library through id and password. Also, it includes the change password option.
2.	Dashboard – it will include the name of the logged-in admin, date, and clock. Also, it’s the main core of the project as it will be designed for 8 functionalities: 
I.	Add Books – add books to store
II.	Issue Books – issue books to students, max limit is 3, and the date of the last issue book will be considered while returning
III.	Edit Books – edit details of the books
IV.	Return Books – return the book and check for fine charges
V.	Delete Books – delete books from the store
VI.	Search Books – details about the book
VII.	Show Books – show the whole book
VIII.	Log out – log out from the current admin session
And most importantly, it is considered here that students and admins are already registered.
How I built this?

This is a database and GUI-based project, hence I will be using Tkinter and sqlite3 libraries from Python. Before moving ahead, let’s go for a short intro to these modules:
Tkinter: It is the standard GUI library in python. It also provides full OOP programming support and it’s easy and fast.
sqlite3: SQLite3 can be integrated with Python using the sqlite3 module. It provides an SQL interface compliant.
I didn’t have to install these modules as they come built-into the python package.
Note: In this project, a total of 3 databases will be created as per the functionality. So, it is easier to create them visually instead of writing SQL queries. Hence, it is recommended to install SQLite studio or any other workbench to create a database consisting of tables and add rows and columns with desired constraints with ease.
 
