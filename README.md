# SyntaxStation

Programming E-Learning system is a app for setup online courses with so many functionality.
It is a PHP project.


Instalation ::
### Steps
1)Copy full folder in your web directory.
2)Import database in your phpmyadmin named project1.sql
3)Edit dbconnection file.change username,password and database name.
- Default user is root,password is null and database name is project1.

Default admin email id is hguarnera@wooster.edu and password is cs200
admin password is md5 encrypted.

## Precise Explanation regarding the work in detail :
INSTALLATION STEPS :
1. Copy zip file and Unzip file on your local server.
2. Put this file inside WAMP or XAMPP server.
3. Database Configuration
- Open phpmyadmin
- Create Database named project1​.
- Import database project1.sql from downloaded folder(inside database)
4. Open Your browser put inside "http://localhost/syntaxstation/"
5. To Login as admin put the following details.
- Admin Login Details
- Login Id: hguarnera@wooster.edu
- Password: cs200


Intermediate Code 2
what’s update?
- almost finished backend and database
- done with admin portion
    - track students
    - track student course history 
    - can see available courses
    - add courses
    - delete courses
    - add prof
    - deleete prof
- now, prof can add course content and quizzes using ckeditor text editor 
    - pdf, images, youtube video

what’s next?
- implement certificate feature
- test backend functionality (some data is not retrieving from database) + test database interaction
- finish frontend
- lock course 
- add progress bar for course progress (admin)
