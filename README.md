# School_District_Analysis
## Overview of School District Analysis with Python and Jupyter Notebook:

### Purpose
___
The purpose of this analysis was to replace all 9th grade math and reading scores due to evidence of academic dishonesty. Maria has asked us to replace the math/reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

Once this task is completed, Maria would like us to repeat the school district analysis from Module 4 and write up a report describing how the changes from the replacment of 9th grade test score values have affected the overall analysis of the data. 

The data for the project is taken from the multiple cvs files in the **Resources** folder provided throughout **Module 4**.

### School District Analysis Results
___
* As can be observed from the below screenshots, the **district summary** passing math & reading percentages as well as the overall passing percentage slightly decreased after the removal of the 9th grade test scores from Thomas High School.  


Module 4 - PyCitySchools

![image](https://user-images.githubusercontent.com/89520192/135777764-020a7e2c-23bc-4178-8fbd-52242a9bba1d.png)

Module 4 - PyCitySchools_Challenge

![image](https://user-images.githubusercontent.com/89520192/135777798-34dffa90-c0c4-435e-979c-406085638364.png)

* The difference in the school summary can only be seen for Thomas High School, where the values for the test scores (math + reading) for 9th graders were removed. The differences from the removal of the 9th grade scores are highlighted in yellow in the below screenshots. 

Module 4 - PyCitySchools

![image](https://user-images.githubusercontent.com/89520192/135778234-88e0153a-7d90-471a-8f9e-448eed501380.png)

Module 4 - PyCitySchools_Challenge

![image](https://user-images.githubusercontent.com/89520192/135778260-72b1df17-0f82-45be-8162-fd2757d6eb15.png)

* Replacing the ninth graders' math and reading scores slightly lowers Thomas High School's performance relative to the other schools.
* Overall, replacing the ninth-grade scores for 1 specific high school (Thomas High School) has a minuscule effect on the results of the data. The scores by school spending/size/type did not change, and only the district and school summaries were slightly different after the removal of the scores. 

### School District Analysis Summary
___
The four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs were:

* number of total students
* number of students counted at Thomas High School (due to removal of 9th grade scores)
* average math and reading scores
* overall percentages for math and reading at Thomas High

Since the number of scores removed were small, it is safe to come to the conclusion that the removal of math and reading scores at Thomas High School specifically for the 9th graders was not as impactful or significant to the overall data analysis as initially perceived.
