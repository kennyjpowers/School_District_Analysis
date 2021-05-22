# School_District_Analysis

## Overview
I have analyzed the grades across schools in a district and summarized them at by school, and at the district level. There is doubts as to whether the 9th grade scores from Thomas High School are legitimate, so I have rerun the same analysis without those scores to compare. 

## Results
- How is the district summary affected?
    - Original
        ![Original District Summary](Resources/original_district_summary.png)
    - New
        ![New District Summary](Resources/new_district_summary.png)
    - The all the metrics decreased slightly except the average reading score which was unchanged. 
- How is the school summary affected?
    - Original
        ![Original School Summary](Resources/original_school_summary.png)
    - New
        ![New School Summary](Resources/new_school_summary.png)
    - Only the Thomas High School numbers were affected.
    - The metrics for Thomas High School decreased slightly except the average reading score which increased very slightly.
- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
    - Original Top Schools
        -![Original Top Schools](Resources/original_top_5.png)
    - New Top Schools
        -![New Top Schools](Resources/new_top_5.png)
    - The changes were so small that its standing as the 2nd best performing school was unchanged. 
- How does replacing the ninth-grade scores affect the math and reading scores by grade?
    - Original Math Scores by Grade
        -![Original Math Scores by Grade](Resources/original_math_scores_by_grade.png)
    - New Math Scores by Grade
        -![New Math Scores by Grade](Resources/new_math_scores_by_grade.png)
    - Original Reading Scores by Grade
        -![Original Reading Scores by Grade](Resources/original_reading_scores_by_grade.png)
    - New Reading Scores by Grade
        -![New Math Scores by Grade](Resources/new_reading_scores_by_grade.png)
    - The only change is there not being any average scores for the 9th grade at Thomas High School.
- How does replacing the ninth-grade scores affect the scores by school spending?
    - Original
        -![Original Spending Summary](Resources/original_spending_summary.png)
    - New
        -![New Spending Summary](Resources/new_spending_summary.png)
    - There was no change to this summary due to rounding.
- How does replacing the ninth-grade scores affect the scores by school size?
    - Original
        -![Original Size Summary](Resources/original_size_summary.png)
    - New
        -![New Size Summary](Resources/new_size_summary.png)
    - There was no change to this summary due to rounding.
- How does replacing the ninth-grade scores affect the scores by school type?
    - Original
        -![Original Type Summary](Resources/original_type_summary.png)
    - New
        -![New Type Summary](Resources/new_type_summary.png)
    - There was no change to this summary due to rounding.

## Summary
The most notable changes in the updated school district analysis after removing the ninth-grade scores from Thomas High School are as follows:

1. The average math score for the district decreased by 0.1.
2. The % passing math for the district decreased by 0.2%.
3. The % passing reading for the district decreased by 0.3%.
4. The % overall passing for the district decreased by 0.1%.