# School District Analysis
  Analysis of school data using Python, Jupyter and Pandas

## Overview of school district analysis
The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turnepd to us for help. I was asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I’ve replaced the math and reading scores, I will repeat the school district analysis previously done and write up a report to describe how these changes affected the overall analysis.  The following analysis will be performed:

- Replacing the reading and math score
- Repeating the school district analysis, performing the following reports:
  1. District Summary
  2. School Summary
  3. High and Low Performing Schools
  4. Math and Reading Scores by Grade
  5. Scores by School Spending
  6. Scores by School Size
  7. Scores by School Type

## Resources
- Data Source: students_complete.csv and schools_complete.csv
- Software: Python 3.7.6, Anaconda

## Results
The analysis of the school district show that:
  - The didtrict summary doesn'y show any significative change given the low weight of one grade in one school is not relevant, and the the change on this grade results was not significative
  - The school summary was marginally affected to the downside, reinforcing suspicious activities on the 9th grade.  Average Math score was roughly unchanged at 83.4, Average Reading Score came from 83.8 to 83.9, % Passing Math from 93.3%to 93.2%, % Passing Reading from 97.3% to to 97.0 and % Overall Passing from 90.9 to 90.6.  The fact the the average did't have much impact and % Passing was lower makes us believe that only Non-Passing grades could have been altered, especially in reading.
  - However, the change on the scores was not enough to make Thomas High School loses the second position on Overall Passing Ranking.
  - Replacing the ninth-grade scores had the following impacts:
    - Math and reading scores were changed only to Thomas High Scholl 9th grades, all other grades and schools were unchanged as expected
    - Scores by school spending didn't have signicant changes
    - Scores by school size dindn't have signicant changes
    - Scores by school type didn't have signicant changes

## Summary

Major changes in the updated schoool district analysis were:

  - Thomas High School % Passing Reading came from 97.3 to 97.0
  - Thomas High School % Passing ath came from 97.3 to 97.2
  - Thomas High School % Overall Passing came from 90.9 to 90.6
  - Thomas High School Average Reading Score came from 83.8 to 83.9
  
The fact the the average scores were unchanged, and the % Passig Rate Decreased make us believe there are good chances in having alterations in the Non-Passing scores only, specially in readig.

  
  
  
   
   
