# School_District_Analysis

## Overview of Project
The school board believes the data set shows evidence of academic dishonesty. Thomas High School 9th graders grades for math and reading appear to be altered. We will then reanalyze all data for the school board and represent our analysis.

### Purpose
The goal of this project to is to replace certain grades as NaNs. We used python data frames to accomplish this goal. Pandas and numpy were the only modules imported. 

## Analysis

### District Summary
The district as a whole has no material change. 

### School Summary
Thomas high school is ranked the second-best school in the district based on overall passing rate when omitting 9th grade data. This is the same before omitting 9th grade data.
![Top Schools](https://user-images.githubusercontent.com/103381098/167264906-81a906f1-70d8-40db-a7da-068796500ce0.png)

### Thomas High School Summary
Thomas high school reading score slightly improved to 83.89. The math score slightly decreased to 83.35. Overall, the passing rates barely changed when omitting the 9th grade data.
![Thomas High School Summary](https://user-images.githubusercontent.com/103381098/167265025-3911d2b3-1ec2-4a19-aa7c-fcb7c5d4095b.png)

### Grouping Summary
The was no meaningful impact when looking at schools’ performance based on size, charter, spending per student, or reading/math. When numbers are formatted there is no major difference. The only major change is when analyzing schools based on grade. for Thomas high school on 9th grade our data is NaN.

## Results
Overall, the changes were small when omitting 9th grade scores. The math scores slightly decreased while reading slightly improved. The only major change is when analyzing schools based on 9th grade. When numbers we formatted most changes weren't noticeable. This analysis should be sufficient and have enough confidence when excluding or including 9th grade data at Thomas high school for the school board.
