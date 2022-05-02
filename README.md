# School_District_Analysis
Module 4 of Data Analysis Bootcamp Program

# Background of Topic

The goal of the project is to analyee data on school district student outcomes. The project involves replacing 9th grader scores from Thoams High School and to see how their removal impacts the data outputs. 

# Main questions 

* 1 - How is the district summary affected?
* 2 - How is the school summary affected?
* 3 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* 4 - How does replacing the ninth-grade scores affect the following:
*   4a Math and reading scores by grade
*   4b Scores by school spending
*   4c Scores by school size
*   4d Scores by school type

# Results

1) Reviewing the data outptuts beteween the project school district summaries and the original district summaries shows minimal differences between the student outcomes outputs.


2) The student outcomes for Thomas High School students appear to have declined significantly on metrics of overall passing between tthe two data frames.

Below are data charts depicted the outcomes***.
#School Summaries***.

![image](https://user-images.githubusercontent.com/95975772/166305497-4884fdf3-fb97-4db9-925f-a6fabed2e41a.png)

3) in the aggregate, based on the averaages presented above, it appears that the adjustments had a significantly negative affect on Thomas High School's standing compared to other schools in the district.



4.a - Math and reading scores outcomes:The main difference on this metric is that now the 9th graders column for Thomas HS is replaced with "NaN".

#adjusted scores

![image](https://user-images.githubusercontent.com/95975772/166308475-3880c994-48f6-4a4b-bbdc-8f6a02a42bb1.png)


4.b - Scores by School spending: There does not appear to be a signficiant change in the data with the 9th grader Thomas HS data removed. 


#adjusted figures:

![image](https://user-images.githubusercontent.com/95975772/166310215-7b8f7f34-bea4-457f-9d5b-c5c8b573b5ac.png)


4.c - Scores by size: Different methods of binning the data were used between the original and new data frame making comparisons difficult. 


![image](https://user-images.githubusercontent.com/95975772/166311478-2c80c57a-3d1a-4d96-abdf-1f5477160b69.png)



4.d - Scores by type: Overall changes appear to be marginal. 

![image](https://user-images.githubusercontent.com/95975772/166311898-76e30bbc-f851-43a5-a389-c8cc80d98b18.png)



## Summary

When replacing values, it appears that the impact of the removal of 9th grader student grades for Thomas HS had a limited impact. On item 4c, it was noted that we impaired our own analysis by using different binning procedures across the periods of time being reviewed. In the future, it would be best to use the same standardized set of binning procedures across all elements under review.


