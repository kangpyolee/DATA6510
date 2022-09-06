<img src="https://github.com/christopherhuntley/BUAN5405-docs/blob/master/Slides/img/Dolan.png?raw=true" width="180px" align="right">

# DATA 6510 Data Warehousing and Visualization
*Fall 2022*
## Course Description
This course introduces databases and data management in five parts:
1. __Databases__, with hands-on instruction in Structured Query Language (SQL) SELECT queries needed to extract data from a relational database
2. __Data Modeling__, focusing on the relational data model and entity relationship diagrams
3. __Data Warehousing__, with emphasis on dimensional modeling and advanced SQL queries
4. __Data Visualization__, with a focus on data storytelling 
5. __Final Project__, which gives each student the opportunity to integrate and apply their new knowledge and skills 

(Prerequisites: Graduate Standing; Credit hours: 3)

## Desiderata

### Course Goals / Theory
#### Be able to explain ...
* Fundamentals of database technology and relevant theory
* Syntax, structure, and execution of SQL SELECT queries
* The relational database model and its implications
* Dimensional Data Warehouses and variations  
* Visualization models and data storytelling

### Learning Objectives / Practice
#### Know how to ...
* Write, validate, and debug SQL queries of moderate complexity
* Read and interpret entity relationship models
* Extract and integrate data from data warehouses
* Build database backed visualization models

## Instructor
Christopher L. Huntley  
Dolan School of Business, DSBN 205E  
Email: chuntley@fairfield.edu (please use sparingly) 

## Office Hours
* Class time will be used like office hours, with lots of time devoted to completing homework
* If you need 1-on-1 time then book an appointment here: https://calendly.com/christopher-huntley
* Usually, however, it is best to contact Dr. Huntley directly on Slack, with general questions in the #data6510 channel or more confidential requests in a direct message

## Resources
* **Lessons:** Each week there will be an interactive lesson to be accompanied by a class lecture covering the highlights.
* **Textbook:** We will use *Storytelling with Data* by Cole Nussbaumer Knaflic in the later part of the course.
* **Online Tutorials:** [DataCamp](https://www.datacamp.com)'s online SQL courses plus a few bespoke case projects designed to accompany the lectures.
* **Software:** Slack (communications), Google Colab (editor & runtime environment), various cloud-based database servers, SQLite (file-based RDB), Lucidchart (diagramming tool), Google Data Studio (data visualization), and Google Classroom (for assignments).
* **Hardware:** All work is online, in the cloud. However, please be aware that even cloud-based software can use up significant system resources. It is also generally better to have a large screen, keyboard, and mouse setup. Some things can be done on touch-based devices but it's not ideal. 
* **Website:** Lessons and assignments are posted and submitted though [Google Classroom](https://classroom.google.com).

## Student Expectations
This is a graduate class intended for serious professionals:
* Expect to spend 6-10 hours per week completing your assignments (and be pleasantly surprised if you finish early). While most work will be asynchronous, due dates on assignments will be strictly enforced. 
* Do your own work. There is no professional benefit to pretending that somebody else's work is your own. We will follow the university's academic honesty policy to the letter.
* Be a good teammate and class citizen. Free-riding and other unprofessional behavior will result in immediate consequences, which may include failing the course.
* By the end of this course you should be proficient in SQL and data visualization.  That means lots of hands on work, eventually without referring to the manual.  

*If you cannot abide by these policies then please take another course.*

## Assignments and Course Grade
### Quizzes (50% of Course Grade)
There will be four quizzes. They will be given on the days shown in the attached schedule of classes. Quizzes are closed book and closed notes. They are designed to last about 25 minutes, though students will be permitted to work on them up to 40 minutes. Please notify the instructor if you require extra time or support services.  
### Final Project (40% of Course Grade)
The final project is meant to assess whether the course objectives have been met. Teams will work in teams of 2-3 students to complete a project of intermediate complexity and scope. 
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
- Starting with Lesson 2, you are expected to **read each lesson before coming to class** and then **read it again after class**.   
- Quizzes are to completed by **7:15pm on the date given**. If you need more time (or have a work conflict), then Slack DM the instructor to start early. You are on your honor to keep the quiz to yourself. 
- Lessons and projects are assigned and tracked via [Google Classroom](https://classroom.google.com), with work completed in [Google Colab](https://colab.research.google.com/).
- Quizzes and other assignments will be graded within two days of the submission deadline.

| Module   | Topic/Assignment                | Due Date   |
| :--:    |----------------------------------|  --------: |
| **1**   | **Databases**                    |            |
|         | Lesson 0: Course Onboarding      | September 6 (in class) | 
|         | Lesson 1: Database Systems       | September 11 |
|         | Lesson 2: SQL Select Basics      | September 13 |
|         | DataCamp: Introduction to SQL    | September 13 |
|         | Lesson 3: SQL Select Advanced    | September 20 |
|         | DataCamp: Joining data in SQL    | September 20|
|         | **_Quiz 1_**                     | September 27 (in class) |
| **2**   | **Data Models**                  |            |
|         | Lesson 4: Relational Models      | September 27 |
|         | DataCamp: Intermediate SQL       | October 4  |
|         | Lesson 5: ER Models              | October 18   |
|         | **_Quiz 2_**                     | October 25 (in class)  |
| **3**   | **Data Warehouses**              |            |
|         | Lesson 6: BI & DW                | October 25   |
|         | Lesson 7: Star Schema            | November 1   |
|         | **_Quiz 3_**                     | November 8 (in class)  |
| **4**   | **Data Visualization**           |            |
|         | Lesson 8: Analytical Framing     | November 8    |
|         | Lesson 9: Visual Design          | November 15   |
|         | Lesson 10: Data Storytelling     | November 22   |
|         | **_Quiz 4_**                     | November 29 (in class) |
| **5**   | **Final Projects**               |                 |
|         | Final notebook submissions       | December 11     |
|         | **_Final Presentations_**        | December 13     |



