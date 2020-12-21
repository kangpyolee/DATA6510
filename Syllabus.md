<img src="https://github.com/christopherhuntley/BUAN5405-docs/blob/master/Slides/img/Dolan.png?raw=true" width="180px" align="right">

# BUAN 6510 Databases for Business Analytics
*Spring 2021*
## Course Description
This course introduces databases and data management in five parts:
1. __Fundamentals__, with hands-on instruction in Structured Query Language (SQL) SELECT queries needed to extract data from a relational database
2. __Data Modeling__, including normalization and diagrammming, with an emphasis on data integrity
3. __SQL Data Definition and Data Manipulation__, with hands on practice with SQL queries (and their Python equivalents, if desired) that affect data
4. __Business Applications__, with links to business intelligence, data warehousing, and advanced SQL and NoSQL technologies  
5. __Final Project__, which gives each student the opportunity to integrate and apply their new knowledge and skills 

(Prerequisites: Graduate Standing; Credit hours: 3)

## Desiderata

### Course Goals / Theory
* To introduce and reinforce fundamentals of database technology and theory
* To master the syntax, structure, and execution of SQL code
* To survey fundamentals of logical design of relational databases
* To apply course concepts through a database-backed business analytics project

### Learning Objectives / Practice
* To write, validate, and debug SQL queries of moderate complexity
* To design, develop, and populate relational databases from source data
* To develop proficiency with professional-level data tools used as in the field
* To craft repeatable ETL processes for analytics projects

## Instructor
Christopher L. Huntley  
Dolan School of Business, DSBN 205E  
Email: chuntley@fairfield.edu (please use sparingly) 

## Office Hours
* When needed we will have Sunday evening Zoom workshops
* Usually, however, it is best to contact Dr. Huntley directly on Slack, with general questions in the #buan6510 channel or more confidential requests in a direct message

## Resources
* **Online Tutorials:** [DataCamp](https://www.datacamp.com)'s online SQL courses plus a few bespoke case projects designed to accompany the lectures.
* **Software:** Google Colab (editor & runtime environment), various cloud-based database servers, SQLite (file-based RDB), Lucidchart (diagramming tool), and Google Classroom (for assignments).
* **Reference Docs:** The official [MySQL Manual](https://dev.mysql.com/doc/refman/5.7/en) covers the MySQL server and coding. SQLite is covered [here](https://www.sqlite.org/docs.html). When in doubt, [RTFM](https://en.wikipedia.org/wiki/RTFM).
* **Hardware:** All work is online, in the cloud. However, please be aware that even cloud-based software can use up significant system resources. It is also generally better to have a large screen, keyboard, and mouse setup. Some things can be done on touch-based devices but it's not ideal. 
* **Websites:**  
    * Class documents (including this syllabus, lesson notebooks, and data files) are in [Dr. Huntley's BUAN6510 GitHub repository](https://github.com/christopherhuntley/BUAN6510).
    * Coding assignments are posted and submitted though [GitHub Classroom](https://classroom.github.com).

## Student Expectations
This is a graduate class intended for serious professionals:
* Expect to spend 6-10 hours per week completing your assignments (and be pleasantly surprised if you finish early). While most work will be asyncronous, dues dates on assignments will be strictly enforced. 
* Do your own work. There is no professional benefit to pretending that somebody else's work is your own. We will follow the university's academic honesty policy to the letter.
* Be a good teammate and class citizen. Free-riding and other unprofessional behavior will result in immediate consequences, which may include failing the course.
* This is a SQL-based introduction to relational databases. The goal is language fluency. That means writing lots of SQL code by hand on keyboard, eventually without referring to the manual.  

*If you cannot abide by these policies then please take another course.*

## Assignments and Course Grade
### Quizzes (50% of Course Grade)
There will be five quizzes, with the lowest grade dropped from your quiz average. They will be given on the days shown in the attached schedule of classes. Quizzes are closed book and closed notes. They are designed to last about 25 minutes, though students will will be permitted to work on them up to 40 minutes. Please notify the instructor if you require extra time or support services.  
### Final Project (40% of Course Grade)
The final project is meant to a demonstration that the course objectives have been met. Teams will work in teams of 2-3 students to complete a project of intermediate complexity and scope. Project details and requirements will be distributed in the 11-th week of class.
### Conspicuous Professionalism (10% of Course Grade)
Given the large class enrollment, the asynchronous delivery, and technical nature of the subject, it is critical that everyone behave as a professional at all times. Students are expected to complete all lessons and participate in all activities to the best of their abilities. Cheating, free-riding, and other unprofessional behavior will not be tolerated. **If at the end of the course the professor does not know who you are or has found evidence of unprofessional behavior, then expect to get a failing professionalism score.**
### Grading Scale
All assignment grades are entered into the gradebook on a GPA scale, where A is 3.67+, A- is 3.34-3.66, etc. The overall course grade is then the weighted average of the grades.

Any assignment that is not scored on a GPA scale will be normalized as follows:  
    
    Grade Points = 3.5 + ½(x-μ)/σ,   

where
- x is the student’s raw score for the assignment
- μ and σ are the class average and standard deviation for the assignment
- Note that the average score is always 3.5, which is an A-. 

After scaling, the expected grade distribution is approximately:

| Grade      | GP Range         | Frequency |
| :--------- | ---------------- | --------- |
| A          | Above 3.66       | 30%       |
| A-         | \[3.34, 3.66)    | 40%       |
| B+         | \[3.0 3.34)      | 24%       |
| B or lower | Below 3          | 6.5%      |



## Schedule
- [DataCamp](https://www.py4e.com/) exercises are assigned and tracked online. 
- Lessons and projects are assigned and tracked via [Google Classroom](https://classroom.google.com), with work completed in [Google Colab](https://colab.research.google.com/).
- Quizzes and other assignments will be graded within two days of the submission deadline.

| Weeks   | Topic/Assignment                 |    Release | Deadline   |
| :--:    |----------------------------------|   -------: |  --------: |
| **0**   | **Course Onboarding**            | January 25 |            | 
|         | Lesson 0: Course Introduction    |            | February 1 |
| **1**   | **Overview**                     |            |            |
|         | Lesson 1: Principles             |            | February 8 |
|         | **_Quiz 1_**                     | February 8 | February 9 |
| **2-3** | **SQL Intro**                    |            |            |
|         | Lesson 2: SQL Select Basics      |            | February 15|
|         | Lesson 3: SQL Select Advanced    |            | February 22|
|         | **_Quiz 2_**                     | February 22| February 23|
| **4-6** | **Data Models**                  |            |            |
|         | Lesson 4: Relational Models      |            | February 29|
|         | Lesson 5: Normalization          |            | March 7    |
|         | Lesson 6: ER Models              |            | March 14   |
|         | **_Quiz 3_**                     | March 14   | March 15   |
| **7-8** | **Data ETL**                     |            |            |
|         | Lesson 7: SQL DDL                |            | March 21   |
|         | Lesson 8: SQL DML                |            | March 28   |
|         | **_Quiz 4_**                     | March 28   | March 29   |
| **9-12** | **Data Models**                 |            |            |
|         | Lesson 9: BI and DW              |            | April 4    |
|         | Lesson 10: Star Schema           |            | April 11   |
|         | Lesson 11: NoSQL                 |            | April 18   |
|         | Lesson 12: Distributed DBMS      |            | April 25   |
|         | **_Quiz 5_**                     | April 25   | April 26   |
| **13-15** | **Final Projects**             | April 18   |            |
|         | Normalized RDBMS                 |            | May 2      |
|         | Data Warehouse (star schema)     |            | May 9      |
|         | Final notebook submissions       |            | May 14     |
|         | **_Final Presentations_**        |            | May 15     |



