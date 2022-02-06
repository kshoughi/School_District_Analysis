# School_District_Analysis
## Project Overview
The purpose of this analysis is to analyze the performance of students from different schools after removing the grade 9 math and reading scores for one of the schools, Thomas High School.

## Results
1- How is the district summary affected?
Since the number of students whose grades were affected were small compared to the total number of all students across different schools, the district summary has not changed much. The biggest effect, was on % Passing Reading. Before adjustments, it was 86% and after fixing the dataset, it dropped to 85.7%.

2- How is the school summary affected?
As expected, the school summary is the same except for the Thomas High School row. Since some of the grades have been removed for this school, the scores for reading, math as well as overall scores and percentages are different by order of one tenth.

3- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before replacing the grades, Thomas High School was the second high school in terms of Overall Passing Percentages. After replacing the grades, it still remained the second top school in terms of Overall Passing Percentages. Therefore, it can be concluded that replacing the grade nine scores, did not affect the relative performance of Thomas High School.

4- How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade:
The grades have not changed since the ninth grades were replaced with NaN and no other grade has been changed.
- Scores by school spending:
The scores by school type have not changed, since very small amount of data have been removed from the dataset. 
![img0](https://github.com/kshoughi/School_District_Analysis/blob/main/school_spending.png)
- Scores by school size:
The scores by school size have not changed, because the size of grade 9 students from Thomas High School were very small compared to the number of total students across all schools, as shown below.
![img1](https://github.com/kshoughi/School_District_Analysis/blob/main/school_size.png)
- Scores by school type:
The scores by school type have not changed, since very small amount of data have been removed from the dataset, as shown below. 
![img2](https://github.com/kshoughi/School_District_Analysis/blob/main/school_type.png)
## Summary
The four changes to the school district analysis after reading and math scores have been replaced are as follows:

- Before removing grade nine scores, the average math score was 83.42, however, after replacing the scores, the score dropped slightly to 83.35.
- Before removing grade nine scores, the average reading score was 83.85, however, after replacing the scores, the score increased slightly to 83.90.
- Before removing grade nine scores, the % passing math was 93.27, however, after replacing the scores, the score decreased to 93.19.
- Before removing grade nine scores, the % overall passing was 90.95, however, after replacing the scores, the score dropped slightly to 90.63.
