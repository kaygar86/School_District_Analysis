# School_District_Analysis
 
The analysis should contain the following:
# Overview of the school district analysis
In Module 4 we used Pandas to create an analysis of school data of student math and reading scores and the budget for each school. The purpose of this analysis was to take the existing code we wrote in the module and to replace Thomas High School's 9th grade student data with NaN. By removing 461 student's scores from the data set we expected to see a difference in the average scores for the rest of the students (grades 10 through 12). Unfortunately we did not get the expected result, therefore we conclude that something went wrong in our refactored code. We ran out of time so we only were able to get to the point of reporting the Top 5 and Bottom 5 schools. 

# Results

## How is the district summary affected?
Looking at the results we received the over all grades were not affected, therefore we conclude that something did not go right in our refactored code. Removing 461 students from the data set for Thomas High School should have yielded a significant difference in the total percentage with passing scores. The Challenge instructions indicated we should have gotten the following result. 
<img width="1009" alt="THS_updated_summary_dataframe" src="https://user-images.githubusercontent.com/66224990/167341377-c334ad82-062a-4e86-8a2b-478da4b94d67.png">

Our results showed the following. 
<img width="979" alt="THS_refactored_results" src="https://user-images.githubusercontent.com/66224990/167341035-6921ae7b-020a-442f-b206-71284eef287a.png">


## How is the school summary affected?
Going off of the correct answer given in the Challenge instructions, Thomas High School should have seen an increase in their average scores of 20% or more across the board for math, reading, and overall score. 

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By replacing 9th graders' scores it should have moved Thomas High School into the top 5 performing schools, whereas before they were much lower ranking. 

## How does replacing the ninth-grade scores affect the following:
We got the following results for top 5 and bottom 5 schools. 
## Top 5 Schools 
<img width="977" alt="Top 5" src="https://user-images.githubusercontent.com/66224990/167342213-6cd19091-463a-4158-b9bb-5b63093f7ba2.png">

## Bottom 5 Schools
<img width="977" alt="Bottom 5" src="https://user-images.githubusercontent.com/66224990/167342244-481e6486-15d7-4568-b888-8390e1859aab.png">

## Math and reading scores by grade
- Replacing the 9th grade scores would not affect the other grade's scores at Thomas High School. 

## Scores by school spending
- Scores do not seem to play a significant role in the school spending, however lower performing schools have a slightly higher per student spending amount. It seems more likely that spending is affected by the school type as the higher spending schools are all District, which may be getting more funding than a private school. 

## Scores by school size
- Removing the 9th grade data would affect the groups of schools with smaller size. Thomas High was one of the smaller schools to begin with so having a higher average passing percentage would make smaller schools appear more successful. 

## Scores by school type
- The top 5 performing schools are charter schools and Thomas High is also a charter school. With a higher average score it would affect the charter schools' performance as a group. 

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- The changes by removing 9th grade scores were:
- Higher percent of students passing math
- Higher percent passing reading 
- Higher percent passing overall
- The changes in above 3 data outputs would have moved Thomas High School into one of the Top 5 performing schools
