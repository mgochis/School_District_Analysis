# School District Analysis

## Overview
The school board found evidence of academic dishonestly for ninth grade reading and math scores at Thomas High School. Without knowing the extent of the grade changes, it was determined that best path moving forward was to remove those test scores from the database and complete the analysis on the school district reading and math scores a second time. We removed the test scores from the dataset and replaced them with NaNs to keep the rest of the data intact. Comparing the analysis prior to removing the scores with the new analysis showed an insignificant change to the overall summaries. 

## Results

### District Summary

![IMG01 - District Summary Before](https://github.com/mgochis/School_District_Analysis/blob/c1f542a883de2aabbd142cf20c1ce0031174a666/Images/IMG01%20-%20District%20Summary%20Old.png)
<sup>District Summary Before</sup>

![IMG02 - District Summary After](https://github.com/mgochis/School_District_Analysis/blob/c1f542a883de2aabbd142cf20c1ce0031174a666/Images/IMG02%20-%20District%20Summary%20New.png)
<sup>District Summary After</sup>


| Analysis | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| --- | --- | --- | --- | --- | --- |
| First Analysis | 79.0 | 81.9 | 75 | 86 | 65 |
| Cleaned Analysis | 78.9 | 81.9 | 74.8 | 85.7 | 64.9 |
| Difference | 0.1 | 0 | 0.2 | 0.3 | 0.1 |

These results show that removing the 9th grade math and reading scores did not significantly affect the overall district scores. 

### School Summary

![IMG03 - School Summary Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG03%20-%20School%20Summary%20Old.png)
<sup>School Summary Old</sup>

![IMG04 - School Summary New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG04%20-%20School%20Summary%20New.png)
<sup>School Summary New</sup>

#### Top Five Performing Schools

![IMG05 - Top Five Performing Schools Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG05%20-%20Top%20Five%20Performing%20Schools%20Old.png)
<sup>Top Five Performing Schools Old</sup>

![IMG06 - Top Five Performing Schools New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG06%20-%20Top%20Five%20Performing%20Schools%20New.png)
<sup>Top Five Performing Schools New</sup>

#### Bottom Five Performing Schools
![IMG07 - Bottom Five Performing Schools](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG08%20-%20Bottom%20Five%20Performing%20Schools%20New.png)

| Analysis | Avg Math Score | Avg Reading Score | % Passing Math | % Passing Reading | % Overall Passing
| --- | --- | --- | --- | --- | --- |
| First Analysis | 83.4 | 83.8 | 93.3 | 97.3 | 90.9 |
| Cleaned Analysis | 83.4 | 83.9 | 93.2 | 97.0 | 90.6 |
| Difference | 0 | 0 | 0.1 | 0.3 | 0.3 |

The scores at Thomas High School decreased slightly when the 9th grade stores were removed, but not enough to affect the overall performance of the school. Prior to removing the 9th grade scores Thomas High School was the second highest performer in the district. That stayed true once the data of the 9th grade scores were removed. The scores did drop in math, reading, and overall passing percentages, but the decrease is not consequential. 

#### Average Math Scores by Grade and School

![IMG09 - Math Scores by Grade & School Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG09%20-%20Math%20Scores%20by%20Grade%20&%20School%20Old.png)
<sup>Math Scores by Grade & School Old</sup>

![IMG10 - Math Scores by Grade & School New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG10%20-%20Math%20Scores%20by%20Grade%20&%20School%20New.png)
<sup>Math Scores by Grade & School New</sup>

![IMG13 - Reading Scores by Grade & School Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG13%20-%20Reading%20Scores%20by%20Grade%20&%20School%20Old.png)
<sup>Reading Scores by Grade & School Old</sup>

![IMG14 - Reading Scores by Grade & School New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG14%20-%20Reading%20Scores%20by%20Grade%20&%20School%20New.png)
<sup>Reading Scores by Grade & School New</sup>


Analyzing the data this way shows that the 9th grade scores have been removed from Thomas High School. Scores from other grades and other schools were not affected by this data removal.

![IMG11 - Math Scores by Grade Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG11%20-%20Math%20Scores%20by%20Grade%20Old.png)
<sup>Math Scores by Grade Old</sup>

![IMG12 - Math Scores by Grade New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG12%20-%20Math%20Scores%20by%20Grade%20New.png)
<sup>Math Scores by Grade New</sup>

![IMG15 - Reading Scores by Grade Old](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG15%20-%20Reading%20Scores%20by%20Grade%20Old.png)
<sup>Reading Scores by Grade Old</sup>

![IMG16 - Reading Scores by Grade New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG16%20-%20Reading%20Scores%20by%20Gread%20New.png)
<sup>Reading Scores by Grade New</sup>

Comparing only the scores by grade we can see that both reading, and math dropped in the 9th grade. This was due to the removal of data from 9th grade Thomas High School. 9th Grade math scores dropped 0.2 percentage points and reading dropped 0.1 percentage points. 

#### Scores by School Spending, School Size and School type

![IMG18 - Scores by Per Capita Spending New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG18%20-%20Scores%20by%20Per%20Capita%20Spending%20New.png)
<sup>Scores by Per Capita Spending</sup>
![IMG20 - Scores by School Size New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG20%20-%20Scores%20by%20School%20Size%20New.png)
<sup>Scores by School Size</sup>
![IMG22 - Scores by School Type New](https://github.com/mgochis/School_District_Analysis/blob/bfad70095a484bcecab8ebe64dbf41688ed241ca/Images/IMG22%20-%20Scores%20by%20School%20Type%20New.png)
<sup>Scores by School Type</sup>

There is no difference between the old analysis and the new analysis once the 9th grade data was removed. There were not enough data points removed to influence these results when analyzing them at this level of granulation.

## Summary

We analyzed scores from a school district, once with some scores showing evidence of academic dishonesty and again once that data was removed. We learned that the removal of those showed a decrease in performance of Thomas High School's math, reading and overall scores. The data did not have a profound effect on the overall dataset, but we learned the importance of having accurate and reliable data. 
