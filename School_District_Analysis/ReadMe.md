# School District Analysis

## Overview of Project
Analysis of school district information using python pandas. Some of the information to be captured are 
- District summary 
- School Summary 
- The top 5 and bottom 5 performing schools, based on the overall passing rate
-Average Math Score 
-The Average reading score 
- The Scores. By School spending per student, by school size, and by school type


### Background and Challenges
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


### Deliverable 1 Requirement
•	The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School. Inside the loc method, the following are completed:
o	A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df 
o	A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df 
o	Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df 
o	Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df 
•	The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs 


### Deliverable 2
The following metrics are captured in deliverable 2
•	The district summary
•	The school summary
•	The top 5 and bottom 5 performing schools, based on the overall passing rate
•	The average math score for each grade level from each school
•	The average reading score for each grade level from each school
•	The scores by school spending per student, by school size, and by school type



### Summary
The above details statistics of election results. A python script was used for the analysis. The analysis was broken down into steps and every step was commented to facilitate easy understanding. The final output was printed in a table that outlines all the summary statistics of the school district analysis after reading and math scores have been replaced