#IMP: create a database named users


FOR EDITING PAGES TABLE  --> 


FOR CREATING TABLE OF CREDENTIALS -->

CREATE TABLE `users` ( `userid` INT(7) NOT NULL AUTO_INCREMENT , `username` VARCHAR(50) NOT NULL , `number` INT(15) NOT NULL , `useremail` VARCHAR(60) NOT NULL , `password` VARCHAR(60) NOT NULL, PRIMARY KEY(`userid`), UNIQUE(`username`), UNIQUE(`useremail`), UNIQUE(`number`) );

CREATE TABLE `blog` ( `blogid` INT(7) NOT NULL AUTO_INCREMENT , `data` VARCHAR(20) NOT NULL , `username` INT(50) NOT NULL , `article` text NOT NULL,`comment` text NULL , PRIMARY_KEY(`blogid`) );