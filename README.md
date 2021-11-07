# PyCitySchools_Challenge

## Overview
The purpose of this project was to reanalyze the school district data given to us previously. We were now tasked with removing the 9th grader's Math and Reading scores from the data table. Once they were removed we were to run the data again to find how having no 9th grader scores affected the Thomas High School's overall averages in Math and Reading. After, we were assigned to create data tables showing the spending ranges of each school based on their averages and their Per Student budget. Additonally, we grouped schools together based on the size of the school and the typing, respectfully.

## Results
    *If you look at the percent_passing_comparrison.png in the Resources folder of the repository you will see that b removing the 9th grader values both reading and math values fro the district went up about 1%
    *Thomas High School originally had a 66.911315% Passing Math average, a 69.663609% average for passing reading, and a 65.076453% average overall passing before the changes were made. After Thomas High School raised to 93.185690%, 97.018739%, and 90.630324% for math, reading, and overall passing averages, respectfully. 
    *When compared to other schools, after removing the 9th grade scores, Thomas High School comes in second of all the schools listed. However, if they had not been changed then by looking at the bottom_five_schools.png and the orignal averages for Thomas High School listed above you can see that Thomas high School would have one of the lowest % Passing math scores, the lowest % Passing Reading score, and a subpar % Overall Passing score.
    *Replacing the 9th grader scores had the follwoing affects:
        *The math and reading by grades section were left alone, save for the Thomas High School 9th grade column that now had NaN in it's place where the value had been originally.
        *For Scores by School spending, it increased the values in all data variables within the "$630-644" row, bringing % Passing math up 3% and %Passing Reading up 2%
        *For Scores by School size, it slightly inscreased all measured variables by 0.1-0.5 
        *For Scores by School type, it slightly inscreased all measured variables by 0.1-0.5

## Summary
Some of the most notable changes in the data after removing Thomas High School's 9th grade scores was the frop Thomas High School had in it's total number of students going from 39,170 to 38,709, affecting their averages throughout the rest of the analysis. All three averages for % Passing took for Thomas High School saw incredible rises after remvoing the 9th grade student's grades from the data frame. Moreover, those changes lead to the largest change which was moving Thomas High School to the 2nd highest averages of all high schools in the district. Finally, All Averages and % scores for Schools in the spending range of $630-644 saw an increase in values. 