# **Module 4 School District Analysis Challenge**

## **Overview of Project:**
### **Purpose of the Analysis**
The purpose of this analysis was to take the previous data analysis of the school district's math and reading scores from each of the high schools in the district. The school board suspects that the 9th grade reading and math scores from Thomas High School may have been altered and they have asked us to replace all of the 9th grade reading and math scores from Thomas High School with a NaN designation. NaN refers to a designation of Not a Number - this allowed us to remove those scores from the analysis without affecting the results which could have happened if we have replaced all the scores with zeros. Once the Thomas High School's 9th grade scores have been removed and the remaining data is intact - the school board wanted us to re-run all of the district anaylsis we previously did and then see what impact the questionable scores may have had. 

## **Results**
#### Inital District Summary
![Inital District Summary](/Resources/Inital%20District%20Summary.png)

#### Updated District Summary
![New District Summary](/Resources/New%20District%20Summary.png)

* In reviewing the inital district summary versus the district summary once the 9th grade scores were removed from the analysis and overall the passing percentages for reading, math and overall only shifted slighty. The passing percentage for math started at 74.9% and went down to 74.8%, the overall passing reading percentage went from 85.8% down to 85.7% amd finally the overall passing percentage went from 65.1% down to 64.1%. We can assume that because the 9th grade class from Thomas High School was only 461 students out of the overall number of students which was 39,170 or 1.2% of the total number of students, it doesn't affect the overall percentages very much. 

#### Inital School Summary
![Inital School Summary](/Resources/Inital%20Per%20School%20Summary.png)

#### Updated School Summary
![Updated School Summary](/Resources/Per%20School%20Summary.png)

* The only difference in these two DataFrames is the % Passing Math, % Passing Reading and % Overall Passing for Thomas High School because this was the only school that had data changed/removed from the analysis. Initally with the 9th grade scores included Thomas High School had the following passing percentages: 66.9% math, 69.6% reading and 65.07% overall. When reviewing the scores from the 10th to 12th grade students at Thomas High School, we found the passing percentages to be: 93.2% math, 97.0% reading and 90.6% overall. This is a significant increase in the overall passing percetnages for Thomas High School. 

* When looking at the inital school summary, Thomas High School was in the bottom half of schools based on those passing percentages. Now after removing the 9th grade scores, Thomas High School lands in the Top 5 schools.

![top 5](/Resources/New%20Top%205%20and%20Bottom%205.png)

* Math and Reading Scores by Grade - removing the 9th grade students grades from Thomas High School will not have any affect on the 10th thru 12th grade scores at all, it will only slightly affect the 9th grade scores overall due to their inital scores being close to the overall average of all the schools. 

* When replacing the 9th grade scores - it did not have any significant impact on the scores by school spending, scored by school size and scores by school type. This can be attributed to the small number of overall scores being adjusted to NaN. 1.2% or 461 student scores out of the total number of students of 39,170 students. 

## Summary
### **Four Changes to School District Analysis**
In conclusion, the four changes we saw to the updated school district analysis was the % Passing Math, % Passing Reading and % Overall Passing all decreased about 1% to account for the 461 scores from the 9th graders at Thomas High School being removed from the analysis. The four change and the biggest seem to be that once the 9th grade scores were removed from Thomas High School, they went from being in the bottom half of school based on scores and when the analysis was redone without the 9th grade data, Thomas High School was 2nd of the 15 schools for performance. This was a drastic shift up in performance againist the other schools in the district. 