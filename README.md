# Library-Management-System
## Welcome to Advanced Digital Library

A minimal, user friendly and functional digital library management system to perform CRUD (Create, Read, Update, Delete) operations on student details and book details registered to the library, and issue and return books by valid admin user.

Technologies Used: Java Swing, MySQL, JDBC connector


## INSTRUNCTIONS
  1.	Open library-management-system package as a Java Project in any of the IDEs (VS Code/NetBeans/Eclipse) for better experience.
  2.	Run SignupPage.java (as implementation starts from this point)


## OBJECTIVE
  1. Log In/Sign Up to the application
  2. To fetch details from back-end MySQL tables and perform CRUD (Create, Read, Update, Delete) operations on them.
  3. Tables/Components:
      (i) Users – stores details of all the admins/librarians/staffs who signs up to the application.
      (ii) Student Details – stores academic details of all the registered students.
      (iii) Book Details – keeps track of all the books (names, authors etc) and their respective availabilities, so that when any book gets out of stock, immediate indent can be done.
      (iv) Issued Book Details – stores information of all the books issued along with the student issued to, status of issue (pending/returned) and issue date and due date.
  4. To show details of issued books as and required, given a range of date or all the records.
  5. Log Out of application, when necessary, actions performed.



## FUNCTIONS
1.	Sign Up
    To create a new account, enter new username, password and other credentials to sign up. Any existing username, if given, would immediately warn you to log in if account already exists.

2.	Log In
    To log in to already existing account, give valid account username and password, wrong credentials will pop a warning message up.

3.	Manage Books
    (i)	ADD : this function adds books to the library stock, give unique book id each time a new book is added, with its name, author and number of copies.
    (ii) UPDATE : When any change is required in the book details, update function is used. For example, to change the number of copies are updated as and when additional copies of an existing book comes up.
    (iii)	DELETE : To remove books not required to store in the library.

4.	Manage Students
    (i)	ADD : whenever a new student joins the institute/college/school, his/her details are registered in the library database to be able to issue them books whenever required.
    (ii) UPDATE : to update students’ details to keep it up to date.
    (iii)	DELETE : to remove a student from the database for situations like when students are passing out or leave the institution.

5.	Issue Book
    (i)	Display Student and Book details alongside, against the student id and book id entered.
    (ii)	Check validity and book availability, only if the book is not issued to the student already and book is available, issue the book to the student.

6.	Return Book
    (i)	Doesn’t accept the book return if already returned or not issued at all.
  	
8.	View All Issued Books Record (pending and returned)
   
10.	View only issued books (pending)
    
12.	View Defaulters List (who has not returned within due date)
    
14.	Log Out, and redirect to the login page



