# School_District_Analysis

## Initial Analysis 

In this project we were tasked to analyze the data of a School District; we performed different analysis to look tat the aggregate distric level of the School Type, Total Students, Total School Budger, Per Student Budget, Per Student Budger, Average Math Schore, Avergate Reading Score, % Passing Math, % Passing Reading and %Overall Passing. We the performed analysis with the same values grouping by school, grade, spending by school, school size and school type. 

## Challenge

The school district notifies that the score average oh the "Thomas High School" were incorrect. Thus, they were replaced to missing value to minimize the effect of the wrongful values in our calculations. 

After replacing the values to NaN; we see no significant changes in the the average mathand reading score at any level. There is a slight change at the district level of the percentage of passing math, reading and overall passin by approximately 1%. When the results are divided by schooll; there is a big change decrease in the percentage pass in math, reading and overall by 26.36%, 27.6% and 25.9% respectively. We see the drop of the Thomas High School from 2nd to 8th when sortend in descending data by overall passing percentage. The only change when bseparated by grade and group by school is that there missing values for all the 9th graders scores. Finally since the Thomas High School is the medium sized group (1000 - 2000 students) we see a lower pass percentage in math and reading and therefore overall percentage. Finally, we see a drop in the same paramaeter for the charter schools. 

In conclusion, scores were inflated in the first analysis and we see a general decrease in the % pass; although there is little to no change in the average scores.
