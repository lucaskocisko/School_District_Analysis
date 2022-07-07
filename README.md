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
old district summary
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_district_summary.png)
new district summary
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_disctrict_summary.png)

?How is the district summary affected?
- The overall passing percentage decreased by ~.25% 
- both math and reading scores decreased by .25% as well

old per school summary
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_per_school_summary.png)
new per school summary
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_per_school_summary.png)

?How is the school summary afffected?
- Thomas High School's overall passing percentage decreased by ~33%

?How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School remains at 2nd place when the district is ranked by overall passing percentage. (in reality its only ahead of 3 and 4 by .05%)

?How does replacing the ninth-grade scores affect the following?:

old math
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_math.png)
new math
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_math.png)

old reading
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_reading.png)
new reading
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_reading.png)

old scores by school spending
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_scores_by_spending.png)
new scores by school spending
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_scores_by_spending.png)

old scores by school size
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_school_size.png)
new scores by school size
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_school_size.png)

old scores by school type
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/old_school_type.png)
new scores by school type
![](https://github.com/lucaskocisko/School_District_Analysis/blob/main/pics/new_school_type.png)

# Summary
- District Analysis - the altered numbers slightly increased Thomas High school's 9th grade reading and math scores.
- Top School Ranking - no change in results, Thomas' overall passing percentage decreased by .3%
- Scores by School Size - minimal changes to Medium(1000-2000) with changes less than .5%
- Scores by School Size - minimal changes to Charter type with changes less than .5%
