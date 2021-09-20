# School_District_Analysis
School District Analysis with Python

## Overview of the Project
According to the school board, reading and math grades for Thomas High School ninth graders appear to have been altered. Therefore, the goal of this project is to repeat the school district analysis without the data that the school board perceived to be altered.

###Specifically, the purpose of this project are as follows:
i.	To replace the math and reading scores for Thomas High School with NaNs (missing data) while keeping the rest of the data intact.
ii.	To repeat the school district analysis after replacing the math and reading scores with NaNs, and 
iii.	to report and describe how these changes affected the overall analysis.

### Effect of changes in the data on the school district summary.
-	Results from the new analysis show a slight change in one metric on the school district summary, “% Overall passing”, and the other six metrics remain the same as the result from the original analysis. Specifically, in the original analysis “% Overall passing” is 65.17% and it is 64.9% in the new analysis. 
(See “Original_District_Summary_Table” and “New_District_Summary_Table” in the Images folder)  

### Effect of New Analysis on Thomas High School Summary
-	Results from the new analysis show very slit drop in the Thomas High School summary metrics. (See “Original_Thomas_High_Summary_Table” and “New_Thomas_High_Summary_Table” in the Images folder) 

### Effect of replacing the ninth graders’ math and reading scores on Thomas High School’s performance relative to the other schools
In the original analysis, Thomas High School is the second best school in the district based on “% overall passing”. The school retains the same second position in the new analysis. Hence, the data changes did not result in any change in Thomas High School overall performance relative to the other schools. 
(See “Original_Top_Performing_School table” and “New_Top_Performing_School table” in the Images folder)  

### Effect of replacing the ninth-grade scores is examined on the following key metrics:

-	Math and reading scores by grade
Replacing the ninth-grade scores affected Thomas High School only and has no effect on the ninth-grade scores for other schools. The analysis shows no ninth_grade scores for Thomas High School and scores for the other schools remains the same as the results from the original analysis.
(See “Original_Math_Scores_Grade” table and “New_Math_Scores_Grade” table in the Images folder)  

-	Scores by school spending
Replacing the ninth-grade scores affected Thomas High School has no effect on scores by school spending. Results from the original analysis show that schools in the lower range of spending (i.e., less than $584 and $585-$629) performed better than schools with higher range of spending. The new analysis confirms the same result.
See tables leabed “Original_Math_Scores_Grade” table and “New_Math_Scores_Grade” table in the Images folder.  

-	Scores by school size
Again, replacing the ninth-grade scores affected Thomas High School has no effect on scores by school size. The results show that small-size (less than 100 students) and medium-size (1000-2000 students) schools performed better than large-size schools (2000-5000 students) in the new analysis.  This original analysis shows the same result.
See tables labeled “Original_Score_By_School_Size_Summary” table and “Original_Score_By_School_Size_Summary” in the Images folder.  

-	Scores by school type
Replacing the ninth-grade scores affected Thomas High School has no effect on scores by school type. In the original analysis, charter schools performed better overall than district schools. The new analysis shows the same result.
-	See tables labeled “Original_Score_By_School_Type_Summary” table and “Original_Score_By_School_Type_Summary” in the Images folder.

## Summary
This project requires changing the underlying data and conducting the school district analysis over again. The ‘loc” method was used to affect this change in the data and most of the analysis in the original exercise where replicated. Results show that the data change resulted in very slight change compared to results from the original analysis, as metrics at all levels of analysis remained unchanged.

-	School district summary
The new analysis resulted into a slight change in the original % overall passing score. The original score is 65.17% and the new score is 64.9%, resulting in 0.27% change.

-	school summary
Very slight drop (0.15%) in Thomas High School “% overall passing” score as a result of changing the data.

-	Math and reading scores by grade
This score remains the same for all school except for Thomas High School.

-	Scores by school type
Again, this score remains the same after the data change.

Based on these results we can conclude that the math and reading scores for Thomas High School were not altered. 
