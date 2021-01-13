# School District Analysis

## Overview

Standardized testing results have been tabulated for the school district of Py City, and we have been tasked with sorting the data across various points of interest in order the help the school board with next year’s budgeting. The scores were sorted based on school, school type, school budget, school size and more. 

After the initial analysis, possible scholastic dishonesty was brought to our attention. The affected data stemmed from Thomas High School’s 9th grade class. The tainted data was removed, and the analysis was run again, which is shown in “PyCitySchools_Challenge.ipynb”. The original analysis can be found in “PyCitySchools.ipynb”.

## Results

The results of modifying the data based on scholastic dishonesty are surprisingly close to the original data. The margin of difference for both sets was very minimal and will be elaborated upon below. 

-The scores across the district were affected as shown below
![](https://github.com/thomasstvr/School_District_Analysis/blob/main/Resources/district.png)
Thomas High School 9th grade class included
![](https://github.com/thomasstvr/School_District_Analysis/blob/main/Resources/district_challenge.png)
Thomas High School 9th grade class omitted 

-The average scores for Thomas High School are shown below, the former including the 9th grade class and the latter with the 9th grade class removed
Pictures

-With the 9th grade class included in the data, Thomas High School had an overall passing percentage of 90.95%. With the 9th grade class removed, the overall passing percentage of 90.63%. This amounts to a difference of .32% of the students at Thomas High School, or about 5 students.

-Removing the 9th grade scores from the data had little, if any, affect on the data. The scores by grade were not affected for any category except Thomas High School’s 9th grade call where NaN is shown in place of scores. Scores based on school spending, size and type were all unaffected by the removal of the tainted data. 
Useless pictures

## Summary 

The removal of Thomas High School’s 9th grade scores left no major changes in the results. 

The average score for reading in the class is 83.7, .2 points lower than the average of the other three classes at Thomas High School, .2 points lower than reading scores at schools of similar size, 2.1 points higher than schools with similar budget and .2 points lower than average reading score of charter students. 

The average score for math is 83.6, .2 points higher than the average for the other classes at Thomas High School, 5.1 points higher than schools of similar budget, .2 points higher than schools of similar size and .1 points higher than the average math scores of charter school students.

Thomas High School’s 9th grade class comprised 1.2% of the district’s students, 3.8% of charter school students, 4% of students in the same budget range and 5.4% of schools with similar size. 

With a change in the data of such small magnitude, it is no surprise that the results were left largely unaffected.
