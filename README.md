##   DDL-COMMANDS ASSIGNMENT-1 


**Create a database named School and perform all the DDL commands(CREATE, ALTER, DROP, RENAME, TRUNCATE) for the table named STUDENT with fields: Roll_No, Name, Marks, Grade. Create data on your own based on the given columns**

•	1 Use the select command to display the table. 

•	2 Add a column named Contact to the STUDENT table. 

•	3 Remove the Grade column from the Student table.

•	4 Rename the table to CLASSTEN. 

•	5 Delete all rows from the table.

•	6 Remove the table from the database.

### **DDL SQL COMMANDS** 
##### **CREATE DATABASE**
CREATE DATABASE School;
#####  **SPECIFY WHICH DATABASE TO BE USED FOR THE SUBSEQUENT ACTIVITY**
USE School;

#####  **CREATE TABLE**
create table STUDENT
(Roll_no int,
Student_name varchar(30),
Marks int,
 Grade int);  
#####  **ADD A NEW COLUMN TO THE TABLE**
ALTER TABLE student ADD  contact varchar(10);

#####  **VIEW THE DETAILS OF THE TABLE**
select * from student;
#####  **REMOVE COLUMN ‘GRADE’ FROM THE STUDENT**

ALTER TABLE student DROP grade;
####  **CHANGE THE TABLE NAME FROM STUDENT TO CLASSTEN**
ALTER TABLE student RENAME CLASSTEN;
#####  **VERIFY THE TABLE NAMED student does not exist**

  SELECT * FROM STUDENT;

#####  **TO VERIFY THAT THE TABLE HAS CHANGED FROM STUDENT TO CLASSTEN**
select * from CLASSTEN;
#####  **REMOVE ALL THE ROWS FROM THE TABLE**
truncate classten;

#####  **DELETE TABLE FROM THE DATABASE**
DROP TABLE Classten;



