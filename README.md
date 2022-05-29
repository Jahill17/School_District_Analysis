# School_District_Analysis

## Project Overview
The school board believes reading and math grades for Thomas High School ninth graders appear to have been altered. I have been requested to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After replacing the math and reading scores,I repeated the school district analysis initially completed in this module and wrote a report to describe how these changes affected the overall analysis.

## Resources
[Clean Student Data](Resources/clean_students_complete.csv)

[Missing Grades](Resources/missing_grades.csv)

[Schools Listing](Resources/schools_complete.csv)

[Student Complete data](Resources/students_complete.csv)

[School District Analysis Starter Code](PyCitySchools_Challenge_starter_code.ipynb)

## Analysis

### School District Summary
Adding "NaN" to all Thomas High School 9th grade math and reading scores did not have a large impact on the district analysis.  As a reference, it should be considered that there are only 461 students in 9th grade at Thomas High School, and a total student count is 39,170 for all schools.  Therefor the 9th grade students at Thomas High School comprise approximately 1% of the total student count, so removing the math and reading scores for Thomas High School had minimal effect on averages.
- Total Students: Remains unchanged
- Total Budget: Remains unchanged
- Average Math Score: Dropped from 79.0% to 78.9% (decrease of 0.1%)
- Average Reading Score: Remained approximately the same at 81.9%
- Percent Passing Math: Remained approximately the same
- Percent Passing Reading: Remained approximately the same
- Percent Overall Passing: Remained approximately the same

*Original Summary*

![Original Summary](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_District_Summary_Original.png)

*Updated Summary*

![Updated Summary](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_District_Summary_Updated.png)

### School Size Summary
Thomas high school is considered to be in the medium school size category of 1000-2000 students.  Replacing the 9th grade scores minimally effected the overall percent passing reading percentage; the percent passing dropped from 97% to 96%.  All other categories (average math score, average reading score, percent passsing math, overall passing) remained uneffected.

*Original Summary*

![Original School Size](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_Size_Summary_Original.png)

*Updated Summary*

![Updated School Size](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_Size_Summary_Updated.png)

### School Type Summary
Thomas high school is a charter school therefore would have no effect on the district schools.  The only category that changed as a result of replacing the 9th grade scores was the percent passing reading; the percentage dropped from 97% to 96%.

*Original Summary*

![Original School Type](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_Type_Summary_Original.png)

*Updated Summary*

![Updated School Type](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/School_Type_Summary_Updated.png)

### Spending Summary
Thomas high shcool has a $638 average spent towards each student so falls in the spending range of $631-$645 per student.  All other spending range categories would be unaffected by replacing the 9th grade scores. The only category effected was the percent passing reading which dropped from 84% to 83%.

*Original Summary*

![Original School Spending](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Spending_Summary_Original.png)

*Updated Summary*

![Updated School Spending](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Spending_Summary_Updated.png)

### Top 5 and Bottom 5 Summary

*Original Top 5 Summary*

![Original Top 5](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Top5_Schools_Original.png)

*Updated Top 5 Summary*

![Updated Top 5](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Top5_Schools_Updated.png)

*Original Bottom 5 Summary*

![Original Bottom 5](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Bottom5_Schools_Original.png)

*Updated Bottom 5 Summary*

![Updated Bottom 5](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Bottom5_Schools_Updated.png)

### Reading and Math Scores
![Original Reading Scores](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Reading_Scores_Original.png)

![Updated Reading Scrores](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Reading_Scores_Updated.png)

![Original Math Scores](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Math_Scores_Original.png)

![Updated Math Scrores](https://github.com/Jahill17/School_District_Analysis/blob/main/PNG%20Files/Bottom5_Schools_Updated.png)
