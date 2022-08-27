# School_District_Analysis
GitHub repository  for school analysis
## Overview of the School District Analysis
    * The purpose of this analysis is to determine how the altered data or accedemic dishonesty would affect the state testing standard,by looking at the effects of         the altered reading and math grades for Thomas High School ninth graders on the district summary dataframe,school summary dataframe and other metrics.
  * All the interested metrics include the following:
     * The district summary DataFrame.
     * The school summary DataFrame. 
     * The top 5 performing schools, based on the overall passing rate. 
     * The bottom 5 performing schools, based on the overall passing rate.
     * The average math score for each grade level from each school. 
     * The average reading score for each grade level from each school. 
     * The scores by school spending per student. 
     * The scores by school size. 
     * The scores by school type. 
### Resources
    * Software : Anaconda Juypter Notebook
    * Files : students_complete.csv,schools_complete.csv
#### Results
     *The district summary was affected as follows
![district_summary _df_ before_ altered](https://user-images.githubusercontent.com/64270455/187047447-1590aece-adff-4851-b064-51f056af5cb2.png)![district_summary _df_ after_ altered](https://user-images.githubusercontent.com/64270455/187047473-d3bf39f7-f684-4af8-97b9-406f5450fb62.png)
        
        *Total Students was reduced by 461 to 38.709 while Total Schools and Total Budget of the district remain unchanged.
        *The Average Math Score was reduced by 0.1 unit to 78.0 while the Average Reading Score  was unchanged 81.9.
        *The Percentage Passing Math was reduced by 0.2% and to new value of 74.8%.
        *The Percentage Passing Reading was reduced by 0.1% and to new value of 85.7%
        *The Percentage Overall Passing was also reduced by 0.3% and to new value of 64.9%.
     *The school summary dataframe affected :
        * Whereas the Total students for Thomas High School reduced by 461 to 1174,the Per Student Budget went up by $250.53 to $888.53.
        * The Total School Budget,The Average Math Score,The Percentage Passing Math and The Percentage Passing Reading for Thomas High School remain unchanged.
        * The Average Reading Score went up by 0.1 unit to 83.9 and the Percentage Overall Passing went up 9% to 100%
        * The Percentage Overall Passing was found to across many schools including those in the bottom 5 schools.
        * Trend of increase in the Percentage Overall Passing in the other schools was found with replacement the ninth graders’ math and reading scores.
      * The replacement of the ninth-grade scores affected the following:
        * Math and reading scores by grade the top 5 remain unchanged
        * Scores by school spending was mostly the same except the Percentage Overall Passing that went up across all groups
        * Scores by school size was mostly the same except the Percentage Overall Passing that went up across all groups
        * Scores by school type was mostly the same except the Percentage Overall Passing that went up across both groups
##### Summary
        * Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
           * Total Students was reduced by 461 to 38.709 and the Average Math Score was reduced by 0.1 unit to 78.0
           * The Percentage Passing Math was reduced by 0.2% and to new value of 74.8%.
           * The Percentage Passing Reading was reduced by 0.1% and to new value of 85.7%
           * The Percentage Overall Passing was also reduced by 0.3% and to new value of 64.9% 
           These goes to show the need for a good data governance accross the school district as any altered school data would actually affect the quality of the                   school district analysis
