# School District Analysis
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help.

## Overview of the School District Analysis
The purpose of this analysis is to repeat the school district analysis performed in the module after replacing the math and reading scores for Thomas High School ninth graders with **NaNs** while keeping the rest of the data intact. This report describes how these changes affect the overall analysis.

## Resources
- Data Source: [Students Complete CSV File](Resources/students_complete.csv), [Schools Complete CSV File](Resources/schools_complete.csv)
- Software: Jupyter Notebook

## Results :school:
- The district summary was virtually not affected by the exclusion of the ninth graders from Thomas High School. The Average Math Score decreased by a tenth of a point and the Average Reading Score remained unchanged. The percentages of passing math/reading and overall passing percentage remained approximately the same when rounded to the whole dollar. 

- After cleansing the data of the ninth graders from Thomas High School, the school summary percentages of passing math/reading and overall passing percentage slightly decreased for Thomas High School.

- Replacing the ninth graders’ math and reading scores only caused a slight change in the percentages of passing math/reading and overall passing percentage. Thomas High School’s performance relative to the other schools remained intact.

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade: Only the ninth grade scores will be affected and specifically for Thomas High School since those were the only scores we replaced with *NaNs*
    - Scores by school spending: Minimal impact due to the slight decreases in the percentages of passing math/reading and overall passing percentage; the school spending remained unchanged
    - Scores by school size: Minimal impact due to the slight decreases in the percentages of passing math/reading and overall passing percentage; the school size remained unchanged
    - Scores by school type: Minimal impact due to the slight decreases in the percentages of passing math/reading and overall passing percentage; the school type remained unchanged

## Summary
- Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
    - The Average Math Score decreased to 78.9 due to the exclusion of the ninth graders
    - The % Passing Math decreased to 74.8% due to the exclusion of the ninth graders
    - The % Passing Reading decreased to 85.7% due to the exclusion of the ninth graders
    - The % Overall Passing decreased to 64.9% due to the exclusion of the ninth graders
