# Overview of School District Analysis
In this assignment, utilizing Anaconda, Jupyter notebook, NumPy and Pandas I conducted analysis on a school district's standardized test results. The school board requests different performance metrics on the districts operating budget and students' tests results. 

## Resources
data sources: schools_complete.csv, students_complete.csv
Python 3.6.8
Jupyter Notebook 6.0
libs Pandas & Numpy

After review there is an anomally within a certain grade level at a single high school. Looking at initial and modified 
results, I can see where the data was skewed.

# Results 

![] (https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_district_summary.png)
new district_summary img

?How is the district summary affected?
- The overall passing percentage decreased by ~.25% 
- both math and reading scores decreased by .25% as well

old per_school_summary img
new per_school_summary img

?How is the school summary afffected?
- Thomas High School's overall passing percentage decreased by ~33%

?How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School remains at 2nd place when the district is ranked by overall passing percentage. (in reality its only ahead of 3 and 4 by .05%)

How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

# Summary
- District Analysis - the altered numbers slightly increased Thomas High school's 9th grade reading and math scores.
- Top School Ranking - no change in results, Thomas' overall passing percentage decreased by .3%
- Scores by School Size - minimal changes to Medium(1000-2000) with changes less than .5%
- Scores by School Size - minimal changes to Charter type with changes less than .5%
