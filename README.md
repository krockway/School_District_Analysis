# School_District_Analysis
Analysis of standardized tests

## Project Overview 
The purpose of this analysis is to provide high level statistics for the school board to review. They'll be able to see at a glance different slices of average math and reading scores, percentage of students passing math or reading, the overall percentage of students who pass both, as well as type of school, number of students and annual budget. The school board will be able to review these statistics at the district level, the individual school level, the grade level, the type of school level, the size level and the budget per student level. They'll also be able to see the best and worst performing schools. Combining all of this information, the school board will be able to make decisions around district spending and areas of emphasis.

## Results: 
For all analysis, the amount of change was minimal. Only after extending the decimal point, was one able to find differences. Keeping the desired formatting in place, one would not have detected a difference in these charts, therefore I have removed formatting in the below images to highlight the minimal differences.

* How is the district summary affected?
    * District Summary Original:
    ![School Summary Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/DistrictSummary.png)
    * District Summary Revised (9th Grade Thomas High scores dropped):
    ![District Summary Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/DistrictSummary_Revised.png)
    * The district level average scores for math & reading, percent passing for math & reading and overall passing percentage decreased slightly, as seen in the comparison above. 

* How is the school summary affected?
    * School Summary Original:
    ![School Summary Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/SchoolSummary.png)
    * School Summary Revised (9th Grade Thomas High scores dropped):
    ![School Summary Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/SchoolSummary_Revised.png)
    * The Thomas High School average scores for math, percent passing for math & reading and overall passing percentage decreased slightly, as seen in the comparison above. However the average reading score increased slightly when the 9th grader scores were dropped. All other statistics remained the same.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    * Top Schools Original:
    ![Top Schools Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/TopSchool.png)
    * Top Schools Revised (9th Grade Thomas High scores dropped):
    ![Top Schools Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/TopSchool_Revised.png)
    * In the original analysis, Thomas High School was the 2nd best performing school with 90.94% of overall students passing both math and reading. However, once the 9th grade scores were removed they maintained the 2nd place status, but the overall passing percentage decreased to 90.63%.

* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
        * Grade Level Original:
            ![Grade Level Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/ByGrade.png)
        * Grade Level Revised (9th Grade Thomas High scores dropped):
            ![Grade Level Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/ByGrade_Revised.png)
        * Because the 9th grade scores were dropped, there was a negative impact on that grade level. No other grade levels saw a change in math or reading scores. As seen in the images above.
    
    * Scores by school spending
        * Spending Per Student Original:
    ![Spending Per Student Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Spending.png)
        * Spending Per Student (9th Grade Thomas High scores dropped):
    ![Spending Per Student Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Spending_Revised.png)
        * Thomas High School spends $638 per student. Schools in this spending range ($630-644 per student) saw a slight decrease in all 5 statistics: average scores for math & reading, percent passing for math & reading and overall passing percentage. No other group saw changes to their metrics, as seen in the images above.

    * Scores by school size
        * School Size Original:
    ![School Size Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Size.png)
        * School Size Revised (9th Grade Thomas High scores dropped):
    ![School Size Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Size_Revised.png)
        * Thomas High School has 1,635 students and is considered a medium sized school. The medium sized school statistics were negatively impacted when the 9th grade scores from Thomas High were dropped. As seen in the images above, the average math score, percentage passing math & reading and overall passing percentage decreased. The average reading scores increased slightly. No other group saw changes.
    
    * Scores by school type
        * School Types Original:
    ![School Types Original](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Type.png)
        * School Types (9th Grade Thomas High scores dropped): ![School Types Revised](https://github.com/krockway/School_District_Analysis/blob/main/Analysis/Type_Revised.png)
        * For the most part, the charter schools statistics were negatively impacted when the 9th grade scores from Thomas High were dropped. As seen in the images above, the average math score, percentage passing math and overall passing percentage decreased. The average reading scores and percentage passing reading both increased slightly. District schools saw no change.

## Summary: 
Overall, negligible change was observed when removing the ninth grade math and reading scores from Thomas High School. They saw an overall decrease in average math score (~.06), percentage of students passing math (~.09%) and overall percentage of students passing (~.3%). Interestingly the average reading score increased by .05, but the percentage of students passing reading decreased by .3%.