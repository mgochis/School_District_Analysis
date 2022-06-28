# School District Analysis

## Overview
The school board found evidence of academic dishonestly for ninth grade reading and math scores at Thomas High School. Without knowing the extent of the grade changes, it was determined that best path moving forward was to remove those test scores from the database and complete the analysis on the school district reading and math scores a second time. We removed the test scores from the dataset and replaced them with NaNs to keep the rest of the data intact. Comparing the analysis prior to removing the scores with the new analysis showed an insignificant change to the overall summaries. 

## Results

### District Summary
![IMG01 - District Summary Before](https://github.com/mgochis/School_District_Analysis/blob/c1f542a883de2aabbd142cf20c1ce0031174a666/Images/IMG01%20-%20District%20Summary%20Old.png)
[IMG02 - District Summary After]

| Analysis | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| --- | --- | --- | --- | --- | --- |
| First Analysis | 79.0 | 81.9 | 75 | 86 | 65 |
| Cleaned Analysis | 78.9 | 81.9 | 74.8 | 85.7 | 64.9 |
| Difference | 0.1 | 0 | 0.2 | 0.3 | 0.1 |

These results show that removing the 9th grade math and reading scores did not significantly affect the overall district scores. 

### School Summary
[IMG03 - School Summary Old]
[IMG04 - School Summary New]
#### Top Five Performing Schools
[IMG05 - Top Five Performing School]
[IMG06 - Top Five Performing School]
#### Bottom Five Performing Schools
[IMG07 - Bottom Five Performing Schools]

| Analysis | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing
| --- | --- | --- | --- | --- | --- |
| First Analysis | 83.4 | 83.8 | 93.3 | 97.3 | 90.9 |
| Cleaned Analysis | 83.4 | 83.9 | 93.2 | 97.0 | 90.6 |
| Difference | 0 | 0 | 0.1 | 0.3 | 0.3 |

The scores at Thomas High School decreased slightly when the 9th grade stores were removed, but not enough to affect the overall performance of the school. Prior to removing the 9th grade scores Thomas High School was the second highest performer in the district. That stayed true once the data of the 9th grade scores were removed. The scores did drop in math, reading, and overall passing percentages, but the decrease is not consequential. 

#### Average Math Scores by Grade and School
[IMG09 - Math Scores by Grade & School Old]
[IMG10 - Math Scores by Grade & School New]
[IMG13 - Reading Scores by Grade & School Old]
[IMG14 - Reading Scores by Grade & School New]

Analyzing the data this way shows that the 9th grade scores have been removed from Thomas High School. Scores from other grades and other schools were not affected by this data removal.

[IMG11 - Math Scores by Grade Old]
[IMG12 - Math Scores by Grade New]
[IMG15 - Math Scores by Grade Old]
[IMG16 - Math Scores by Grade New]

Comparing only the scores by grade we can see that both reading, and math dropped in the 9th grade. This was due to the removal of data from 9th grade Thomas High School. 9th Grade math scores dropped 0.2 percentage points and reading dropped 0.1 percentage points. 

#### Scores by School Spending, School Size and School type
[IMG18 - Scores by Per Capita Spending New]
[IMG20 - Scores by School Size New]
[IMG22 - Scores by School Type New]

There is no difference between the old analysis and the new analysis once the 9th grade data was removed. There were not enough data points removed to influence these results when analyzing them at this level of granulation.

## Summary

We analyzed scores from a school district, once with some scores showing evidence of academic dishonesty and again once that data was removed. We learned that the removal of those showed a decrease in performance of Thomas High School's math, reading and overall scores. The data did not have a profound effect on the overall dataset, but we learned the importance of having accurate and reliable data. 
