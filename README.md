# loginapp
INSTALLATION GUIDE:


Requirements:

MySQL Server >= 5.6
Node.js
Express - Install with command: npm install express --save.
Express Sessions - Install with command: npm install express-session --save.
MySQL for Node.js - Install with command: npm install mysql --save.


Follow the below instructions:

Create a new directory called loginapp, which can be created anywhere on your environment.
Open command line as administrator, and navigate to your new directory with the following command: cd c:\nodeprojects\loginapp
Run the command: npm init - it will prompt us to enter a package name, enter: login.
When it prompts to enter the entry point, enter login.js.
We need to install the packages listed in the requirements, so we must execute the commands listed in the requirements above.

After that the file structure and code can be followed as uploaded.

NOTE:change the mysql root password in the js file according to yours.

MYSQL DATABASE TO BE CREATED IN MYQSL COMMAND LINE(or other appropriate framework):

CREATE DATABASE IF NOT EXISTS `loginapp` DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
USE `loginapp`;

CREATE TABLE IF NOT EXISTS `users` (
  `name` varchar(50) NOT NULL,
  `email` varchar(100) NOT NULL
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

INSERT INTO users VALUES ('Muskan','muskan@gmail.com');

After this code can be run using "node login.js" in terminal
and run on localhost 3000 in your browser.
