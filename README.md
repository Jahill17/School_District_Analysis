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
Adding "NaN" to all Thomas High School 9th grade math and reading scores did not have a large impact on the district analysis.  As a reference, it should be considered that there are only 461 students in 9th grade at Thomas High School, and a total student count is 39,170 for all schools.  Therefor the 9th grade students at Thomas High School comprise approximately 1% of the total student count, so removing the math and reading scores for Thomas High School had minimal effect on averages.
- Total Students: Remains unchanged
- Total Budget: Remains unchanged
- Average Math Score: Dropped from 79.0% to 78.9% (decrease of 0.1%)
- Average Reading Score: Remained approximately the same at 81.9%
- Percent Passing Math: Remained approximately the same
- Percent Passing Reading: Remained approximately the same
- Percent Overall Passing: Remained approximately the same

*Original Summary*

![This is an image](PNG Files/School_District_Summary_Original.png)

*Updated Summary*

![This is an image](PNG Files/School_District_Summary_Updated.png)

### School District Summary
### Reading and Math Scores
