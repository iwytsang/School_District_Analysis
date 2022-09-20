# School District Analysis

## Purpose
The purpose of this analysis was to assist Maria, the chief data scientist for a city school district with analyzing, reporting, and presentating the standardization of student test data. For our analysis, we received a new version of student data with a new column "school budget" to examine. 

## Analysis
With our analysis using pandas, we can determine that although the average budget for public schools is higher than charter schools, the average reading score of charter schools and public schools is roughly the same, with the charter school being higher by only 0.169384. 

![School_Budget](https://user-images.githubusercontent.com/108503112/191361093-90cb603e-a53a-4af2-a601-0f705c2e15b5.png)  ![Average_Reading_Math_Score](https://user-images.githubusercontent.com/108503112/191361107-a5f4b97b-6448-496a-942b-12009617844e.png)

However, the average math score of charter schools is higher than public schools by 3.810307. When further broken down by grade, the average math scores for every grade in charter schools is higher than public school (with the exception of grade 12).

![Math_Score_by_Grade](https://user-images.githubusercontent.com/108503112/191361212-eca708f4-e2c1-4064-9333-282c02cb1f6c.png)

## Proposed Additional Analysis
A useful additional analysis would be to further examine which specific public schools have a lower average math score than charter school. We can look at each public school individually and examine the schools with the average math score lower than the charter school score of 66.761883. After identification of the schools with a lower score, the school district can determine the next steps in order to bring the average math grades up for those particular public schools that have students struggling in math.
