# Book-Shop
This project was created only with the scope of school project by using only MySQL and Python only for Session 2020-21 (CBSE Board)

In this project modules used are:
  1. smtplib (for sending emails)
  2. mysql.connector (for connection to MySQL Server)
  3. fpdf (to autogenerate pdf invoices)
  4. validate_email (to validate emails of users on sign up)
  5. time (to register the order time)
  6. string (for string formatting)
  7. datetime (for calculating date differences)

Key Features:- 
  1. This code is of approx 1400 lines and it consists of every function which an bookshop owner requires
  2. It helps new users to register themselves and order/return/replace/check details of order/view details of book, etc.
  3. Every time a new user sign up, his/her email is validated that if it exists.
  4. On placing order, user gets a thanks message and an autogenerated PDF invoice on his/her email address given during sign up. (see invoices folder)
  5. Every time a user return/replace/cancel order, he/she will receive an auto generated email.
  6. Administrator has all the rights of viewing, updating, deleting users (not passwords), and also can view/cancel/replace/return orders of a specific user.
  7. ERRORS ARE HANDLED VERY SERIOUSLY.
  
Cons of this project:-
  Since this was a school project, it is only TERMINAL-BASED. NO GUI version.
