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
     * Thomas High School dropped from a top five spot (No. 2) to 8th place. 
  * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
     *
  * How does replacing the ninth-grade scores affect the following?
    * Math and Reading Scores by Grade
    * Scores by School Spending
    * Scores by School Size
    * Scores by School Type
