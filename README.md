# School_District_Analysis

## Overview: 
The purpose of this project was to gain experience using Python in Jupyter Notebook to perform an analysis on .csv files, handling missing values, creating data frames as well as using the command line to add, commit, and push files to the appropriate repository. 

The math and reading scores of all students among every school within a single district were analyzed, and provides many different measures of performance to compare. After the inital analysis was completed, the math and reading scores of 9th graders from Thomas High School were replaced with NaN. Then, the same analysis was performed on the data with the replaced values. This report summarizes how replacing these students' grades with NaN affected the overall analysis.

## Results:

How is the district summary affected?

* Before replacing THS ninth grade math and reading scores
  ![image](https://user-images.githubusercontent.com/84869167/126256795-d152aaa8-e84a-402e-92b6-788f1c1a4cbf.png)

* After replacing THS ninth grade math and reading scores
  ![image](https://user-images.githubusercontent.com/84869167/126256831-d1398523-1cf7-464b-bacc-48c78753ab8a.png)

* Conclusion: This dataFrame displays a summary of statistics for the entire school district. The total number of schools, total students, and total budget remained constant. However, the average math score, average reading score, percent passing math, percent passing reading, and overall passing percentage slightly drops when looking at the tens and hundreds places of the values.  


How is the school summary affected?

* Before replacing THS ninth grade math and reading scores
  
  Top Schools in the school summary dataFrame: 
  
  ![top_schools_summary_1](https://user-images.githubusercontent.com/84869167/126257703-316d383e-1928-4e46-beff-dcdd9dedc689.PNG)
  
  Bottom Schools in the school summary dataFrame:
  
  ![bottom_schools_summary_1](https://user-images.githubusercontent.com/84869167/126257763-f46940be-29ef-481e-9271-2e8ccba5a08e.PNG)

* After replacing THS ninth grade math and reading scores
  
  Top Schools in the school summary dataFrame: 
  
  ![top_schools_summary_2](https://user-images.githubusercontent.com/84869167/126257801-df3536d2-ddba-4b00-8c51-47c6dfb54fd3.PNG)

  Bottom Schools in the school summary dataFrame:
  
  ![bottom_schools_summary_2](https://user-images.githubusercontent.com/84869167/126257833-e3b5dcee-316e-4510-9509-c6e50159a846.PNG)
  
* Conclusion: This dataFrame displays a summary of statistics for each of the schools within the school district. The school type, total students, total school budget, and per student budget remained constant. The only changes that occur within this dataframe after replacing the values is a slight decrease in test score average, math/reading passing percentage, and overall passing percentage for Thomas High School. The decrease in these values is limited to not more than a few tenths of a percentage that does not make any major difference in data.


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* THS performance before replacing THS ninth grade math and reading scores

  ![THS_performance_1](https://user-images.githubusercontent.com/84869167/126258170-6108b74b-e6ed-4e23-912f-1fcbbbcda51d.PNG)

* THS performance after replacing THS ninth grade math and reading scores

  ![THS_performance_2](https://user-images.githubusercontent.com/84869167/126258187-71002a86-8d46-46a6-bc20-c51f66bf93d6.PNG)
  
* Conclusion: As discussed in the previous answer, the statistics for Thomas High school changed within the school summary dataFrame after replacing the values. This slight decrease in values had almost little to no effect on the school's perormance. 


### How does replacing the ninth-grade scores affect the following:


Math and reading scores by grade

*   Before replacing THS ninth grade math and reading scores
    
    Math Score Averages by Grade
    
    ![math_scores_1](https://user-images.githubusercontent.com/84869167/126258678-899069ca-0c4b-404f-8ae0-98a79546ea51.PNG)
    
    Reading Score Averages by Grade
   
    ![reading_scores_1](https://user-images.githubusercontent.com/84869167/126258687-1a1197c5-9c22-4247-a14d-4598b3593d5c.PNG)

*   After replacing THS ninth grade math and reading scores
    
    Math Score Averages by Grade
    
    ![math_scores_2](https://user-images.githubusercontent.com/84869167/126258712-5d7c39c6-7352-4be3-a0b1-2e9e7bdd93ae.PNG)
    
    Reading Score Averages by Grade
    
    ![reading_scores_2](https://user-images.githubusercontent.com/84869167/126258713-ba732055-55cb-473e-a8de-0672a3a54ebb.PNG)

*   Conclusion: Before replacing the values, the math and reading score averages for every grade at each school was visible. After replacing the values, the math and reading scores for 9th graders at Thomas High School displayed "NaN". The replacement of values for only 9th graders at Thomas High School had no effect on the average scores of the other grades at Thomas High School, not did it affect the grade averages for different grade levels at different schools. 



Scores by school spending

*   Before replacing THS ninth grade math and reading scores

    ![image](https://user-images.githubusercontent.com/84869167/126259213-b85351b9-5fac-4287-a952-85aabceab9f8.png)

*   After replacing THS ninth grade math and reading scores

    ![image](https://user-images.githubusercontent.com/84869167/126259277-8df03cdc-2669-47f6-b10b-9a108fd40616.png)

*   Conclusion: Images of the unformatted scores by school spending were used for comparison because the formatted version with rounded values showed zero differences before and after replacment. We can see from the school summary dataFrame that  Thomas High School spends $638 per student and belongs to the $630-$644 spending range. When examining the spending ranges per student dataFrame, we can see a slight decrease in average math and reading score, as well as percent passing math, percent passing reading, and overall passing percentage for the $630-$644 spending range. This decrease in values is so minute, it mainly affected values in the hundredths value, with overall passing percentage decreasing in the tens value. 



Scores by school size

*   Before replacing THS ninth grade math and reading scores
    
    ![image](https://user-images.githubusercontent.com/84869167/126260018-70bf26f9-e9bc-4760-a780-b5efdb0096ed.png)

*   After replacing THS ninth grade math and reading scores

    ![image](https://user-images.githubusercontent.com/84869167/126260065-75efc734-92ee-4d52-b816-7d3b0c636b5d.png)

*   Conclusion: Images of the unformatted scores by school size were used for comparison because the formatted version with rounded values showed zero differences before and after replacment. When looking at the school summary dataFrame, we can see that Thomas High School has 1,635 students, placing it in the "Medium" school size category. Again, the only changes we see is within the category Thomas High School falls under, and the decrease in statistics is so minute that the rounded scores basically don't change. 



Scores by school type

*   Before replacing THS ninth grade math and reading scores

    ![image](https://user-images.githubusercontent.com/84869167/126260998-65321c36-fac3-417d-86bd-483d7fe5104a.png)

*   After replacing THS ninth grade math and reading scores

    ![image](https://user-images.githubusercontent.com/84869167/126261032-fa182a7e-b5a5-45bd-8287-5b2ca23e0c2c.png)
    
*   Conclusion:  Images of the unformatted scores by school type were used for comparison because the formatted version with rounded values showed zero differences before and after replacment. When looking at the school summary dataFrame, we can see that Thomas High School is a Charter School. For the parameter of school type, we can see a slight INCREASE in performace statistics for Charter schools after the replacement of values. 



## Summary: 
* The performance statistics for the entire school district and for Thomas High School decreased slightly
* Math and reading scores by grade displayed "NaN" instead of numerical values
* Minute decrease in scores based on school spending and scores based on school size
* Increase in average scores, passing percentages, and overall passing percentage for Charter Schools

The changes in the performance statistics at over a wide spectrum of parameters were so minute that they did not make any major difference in outcome the analysis after replacing values with NaN. 
