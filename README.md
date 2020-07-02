# School_District_Analysis
Module 4 -Python
### Problem 
The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.

After assessing the situation, I decide the best approach is to:

* Replace the ninth-grade math and reading scores from Thomas High School.
* Keep all other data associated with the ninth-grade students and Thomas High School intact.

### Instructions
* Create a duplicate of PyCitySchools.ipynb and rename it PyCitySchools_Challenge.ipynb.
* Correct the students' names so there are no professional prefixes or suffixes.
* Replace the reading and math scores for ninth graders at Thomas High School with NaN.
  * Use loc on the student_data_df DataFrame to select the columns by condition.
  * Set the column you want equal to "NaN" by using np.nan for the reading and math scores separately. 
    * To use np.nan, you’ll need to import Numpy with the following: import numpy as np.
After you replace the reading and math scores for ninth graders at Thomas High School with NaN, the student data DataFrame after replacing the math and reading scores for Thomas High School with NaN.

* Merge the clean student data with the school dataset.
* After replacing the reading and math scores, complete the following steps and answer the questions for each step.
  * Recreate the district and school summary DataFrames.
  * How is the district summary affected?
  * How is the school summary affected?
* Recalculate the high- and low-performing schools.
  * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
* Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
  * How does replacing the ninth-grade scores affect the following?
    * Math and Reading Scores by Grade
    * Scores by School Spending
    * Scores by School Size
    * Scores by School Type
    
 ### Summary of Findings 
  * How is the district summary affected?
     * The averages of the math and reading scores lowered, which caused the overall passing percentage to go from 65% to 64%. 
  * How is the school summary affected?
     * Thomas High School dropped from a top five spot (No. 2) to 8th place. Scores of the average math, passing math percentage, passing reading percentage and overall passing percentage dropped for Thomas high school.
  * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
     * Thomas High School dropped from a top five spot (No. 2) to 8th place. 
After recalculating the scores by grade, scores by school spending, scores by school size, and scores by school type, the ninth-grade scores were affected in the following ways:
    * Math and Reading Scores by Grade - All other school averages for math and reading scores remained unaffected. However, the overall average reading score lowered from 81.8778 to 81.8558 and math score from 78.9853 to 78.9305.
    * Scores by School Spending - Spending percentage per student lowered for the $630-644 bin, droping from 62.86% to 56.39%. This was due to also lower percentages from reading and math scores. 
    * Scores by School Size - The medium (1000-2000) school size percentage dropped by 6 points for the passing math, reading and overall passing percentage. 
    * Scores by School Type - Charter schools suffered a percentage decrease after Thomas High School's grades were replaced with NaN. Lower percentages for the subjects lowered the overall passing percentage by more than 3%, from 90.4% to 87.2%.
