# School_District_Analysis
## Module4 Anaconda/Jupyter notebook 
# Purpose
- A project to create a script using Panda to analyze a city school district data to analyze performance test data to help the school board with the student funding & student standardized test scores. After the initial analysis the school board notified that students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. So the reporting data needs to be replace with the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

## Analysis & Challenges
- Two .csv file were provided with boards Schools listing and Student detail which were analyzed to create the overall school performance. So, we had to refactored the code to remove the data for the particular school and regenerate the below reporting:
-	The district summary
-	The school summary
-	The top 5 and bottom 5 performing schools, based on the overall passing rate
-	The average math score for each grade level from each school
-	The average reading score for each grade level from each school
-	The scores by school spending per student, by school size, and by school type

## Results

After removing the Thomson High School’s 9th grade data the overall district metrics was effected per below:
![District_summary_before](https://user-images.githubusercontent.com/85530486/125210781-e5d32780-e26f-11eb-9f16-b4370f0bd20a.png)

   •	Average Math score dropped from 79 to 78.9

   •	Average Reading Score remain unchanged at 81.9

   •	Math pass percentage dropped from 75% to 74.8%
  
   •	Reading pass percentage dropped from 86% to 85.7%

   •	Overall pass percentage for both math and reading dropped from 65% to 64.9%

![District_summary_after](https://user-images.githubusercontent.com/85530486/125209978-c38adb00-e26a-11eb-8121-584345995661.png)

## Summary

-	The drop of the 9th grade score didn’t change the core matrix of the district schools. Overall analysis reflects below:

  •	The schools spending highest amount per students has the lowest overall passing rate:
  
  ![Spending_range_per_student](https://user-images.githubusercontent.com/85530486/125210643-1e263600-e26f-11eb-84e1-e899a2dec7ca.png)

  •	The larger school sizes have the lowest average passing grades:
  
  ![School_size](https://user-images.githubusercontent.com/85530486/125210690-62193b00-e26f-11eb-8a0d-27853beb3337.png)
  
  
  •	The Charter schools has higher overall passing rate than the district schools
  
  ![School_type](https://user-images.githubusercontent.com/85530486/125211194-c4276f80-e272-11eb-9185-bda29a9185a0.png)


