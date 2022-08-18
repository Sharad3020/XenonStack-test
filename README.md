# XenonStack-test

This file contains the completed tasks as asked in the problem statement:

1. A database having different tables for 'users', 'new registered users', and the users that contact the company.
2. Login Page connected to database on 'phpmyadmin'. The 'Login page' is coded in Intellij idea community edition using java as the language. And, a GUI login form is made for the user.
![Screenshot 2022-08-18 065723](https://user-images.githubusercontent.com/56599307/185282511-8caf6199-27a1-455c-87db-d81cc523927d.png)
![Screenshot 2022-08-18 072133](https://user-images.githubusercontent.com/56599307/185282550-4e14876f-c5a7-4d93-bdd5-5d76bb464283.png)

3. Registration Form connected to database on 'phpmyadmin'. The 'Registration form' is coded in Intellij idea community edition using java as the language. And, a GUI registration form is made for the user. Whenever a new user registers himself/herself, he/she gets added in the 'users' table in the database automatically.
![Screenshot 2022-08-18 070428](https://user-images.githubusercontent.com/56599307/185282597-7e1c7dfd-6306-4cbe-8533-0a1e3f286159.png)
![Screenshot 2022-08-18 072317](https://user-images.githubusercontent.com/56599307/185282660-04c108ba-e3c7-4865-b3f8-11c75a82e8dc.png)

4. Dashboard Form connected to database on 'phpmyadmin'. The 'Dashboard form' is coded in Intellij idea community edition using java as the language. And, a GUI dashboard form is made for the user. The dashboard form opens up the 'login page' when the number of user in the database is greater than zero. And, if the number of users in database is zero than the dashboard form opens up the 'registration form' directly to add users in the database.
5. Contact Us dialog box connected to database on 'phpmyadmin'. The 'Contact Us' box is coded in VS code as Intellij idea community edition is not compatible with 'css file'. Whenever a user tries to contact the following system its details gets attached in the database in a specific table.
![Screenshot 2022-08-18 072554](https://user-images.githubusercontent.com/56599307/185282712-4d37f723-2027-42d7-87b4-a41f0ecdaeba.png)
![Screenshot 2022-08-18 072636](https://user-images.githubusercontent.com/56599307/185282748-28e10abe-78e8-4838-acac-a42004181f2e.png)

Frontend for the dialog box - HTML, CSS, JS
Backend for the forms - Java
Database - MySQL

Steps to perform: -

1. Download XAMPP from https://www.apachefriends.org/download.html and install it.

2. Open XAMPP Control Panel and start 'apache' and 'mysql'.

3. Download Intellij idea community edition from https://www.jetbrains.com/idea/download/#section=windows and install it.

4. Download my-sql-connector-java from https://dev.mysql.com/downloads/connector/j/8.0.html and select 'platform independent' in 'select operating system' dialog box.

5. Open localhost/phpmyadmin/.

6. Create a new database of your choice and insert a table for 'user' with columns like 'id', 'name', 'email', 'address', 'phone' and 'password'.

7. Download some images for the different styling of forms.

8. Open Intellij idea and create a new file for your project.

9. Add images and my-sql-connector-java to 'src' of your project. Click on 'Refactor'.

10. Right click on 'src', go to 'new', then to 'swing ui designer' and select 'GUI form'.

11. Make three form for 'Login', 'Registration' and 'Dashboard' and add the code in there java file.

12. Now, run different forms to test them. If the code runs perfectly it will give the output in the terminal and the dialog box will pop up. Add the necessary details and it will be added to the database.

13. Open 'htdocs' folder in XAMPP folder in your computer system and create a folder there for the 'Contact Us' form.

14. Open that folder in VS code and create three files for 'contactform.php', 'save.php', and 'style.css' and create a folder also for the image you want to use as background.

15. Code for the three files.

16. Go to your database in 'myphpadmin' and create a new table for the users that contacted.

17. Enter columns like 'First_name', 'Last_name', ' Email', 'Mobile'. Select the type as 'varchar', enter the values and click on 'save'.

18. In 'save.php' give database name in '$conn' for the connection of the database.

19. Now go to 'localhost/(name of the folder that you gave in htdocs)/', fill the following details and click on 'submit' button.

20. The details will be now shown in the new table for the users that contacted.
