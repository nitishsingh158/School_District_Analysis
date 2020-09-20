# School District Analysis

## Overview of the project 
The project analyses student's math and reading test scores from 16 different schools in LA county. The goal of the project is to gain key insights from the data on key metrics for each school, which will help the county education board make budget decisions for the next academic year. 

**Note:** Before the results of the analysis were published, the school board was notified about academic dishonesty relating to reading and math grades for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty and is still looking into the matter, they want to continue the analysis while upholding state-testing standards. Therefore, the math and reading scores for Thomas High School have been replaced with NaNs while keeping the rest of the data intact. 

## Results
The district summary table for data with and without Thomas High School is provided below. 
1. The total budget for the academic year for the 15 schools considered is $24,649,428. 
2. The data sets consist of math and reading scores of 39,170 from 15 district schools. After excluding the 9th-grade students from Thomas High School the total student count goes down by 461 to 38,709.  
3. The top 5 performing schools in the district are all charter schools with the following characteristics:
   - They have a low student count with a typical range of 1000-2200 students per school. 
   - They have a generally low per capita budget when compared to the other schools in the district. The per capita budget for this group is in the range of $575-635. 
4. The lowest 5 performing schools in the district are all public schools with the following characteristics:
   -  They have a higher student count with a typical range of 2800-4800 students per school.
   - They have a higher per capita budget when compared to the other schools in the district. The per capita budget for this group is around $650.
5. The district schools on average have a high Reading score than their math score is a higher percentage passing rate in reading than maths.
6. After removing the data from Thomas High School ninth grade tests, the following changes in the district:
   - The average math score changed from 79.0 to 78.9.
   - The number of students passing in maths changed from 75% to 74.8%.
   - The number of students passing in reading changed from 85.8% to 85.7%
   - The overall number of students passing changed from 65.2% 64.9%.
    
7. The changes show that the erroneous average scores from Thomas High School were higher than the math and reading scores of the rest of the schools.

![District with Thomas High School](/Resources/District_summay_w_ths.png)*Summary with Thomas High School*

![District without Thomas High School](/Resources/District_summay_wo_ths.png)*Thomas without Thomas High School*

![Per School Summary](/Resources/Per_School_Summary.png)*School specific summary of test scores*


## Summary
The changes after excluding Thomas Hogh School's math and reading test scores from ninth grade reduced overall all scores and passing percentages. 
Additionally, we can infer that school size has an inverse correlation to the increased test scores. 


