### Library Management System

---

This is an application that manipulates the database through JAVA Swing GUI interaction. We use the [WindowBuilder](https://www.eclipse.org/windowbuilder/) (GUI Designer Plugin on Eclipse IDE) to handle the graphical swing components and [Java JDBC API](https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/) to connect from Java App to the database through the JDBC driver.. 

This Library Management System is equipped with add, delete, update, and search for books. The underlying implementation principle of these functionalities is relying on the SQL database operation statements.

---

**The project folder structure:** 

├── src
│ ├── com

│ │ ├── ls

│ │ │ ├── dao

│ │ │ ├── graphics

│ │ │ ├── model

│ │ │ ├── util

│ ├── images



*The Dao (Data access object) package contains the methods of accessing the table scripts of user, category, and book information.* 

*The graphics package is Java swing components; The model package contains classes for generating book, user, and category objects.*

*The util package for database connection interface.*

---

**The MySQL Database setting:** 

├── db_book

│ ├── t_book

│ ├── t_booktype

│ ├── t_user



Utilize the architecture designer to link each entry of the book to a t_bookType for the linked relation of category and book.

![mysql](C:\Users\boxiang\Desktop\Github\LibrarySystem\Demo\mysql.png)

---

**Demos: **



The login page:

![loginPage](C:\Users\boxiang\Desktop\Github\LibrarySystem\Demo\loginPage.png)



The Homepage:

![HomePage](C:\Users\boxiang\Desktop\Github\LibrarySystem\Demo\HomePage.png)



The book operation:

![BookOperation](C:\Users\boxiang\Desktop\Github\LibrarySystem\Demo\BookOperation.png)