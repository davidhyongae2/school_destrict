## Overview of the school district analysis
School districts analyze students' reading and math performance for budget and spending regulations.
    

1. PANDAS and NUMPY.
2. Dataset read with PANDAS.
3. Jupyter notebook to display results of PANDAS.
4. Calculating reading, math, and overall performance.


## Resources
- Data Source1: schools_complete.csv,
- Data Source2: students_complete.csv
- Program language: Python 3.8.

## Results 
How is the district summary affected?

![Figure 1](https://github.com/davidhyongae2/school_destrict/blob/main/Figure1.png) <br> The charter school and district schools are sub-grouped into different clusters. How is the school summary affected?

![Figure 2](https://github.com/davidhyongae2/school_destrict/blob/main/Figure2.png) <br> Grades 10th, 11th and 12th are included while 9th is excluded from this summary. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Figure 3a](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3a.png) <br> Math score of 9th,10th,11th,12th grade are excluded 70% and below.

![Figure 3b](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3b.png) <br> Reading scores of 9th,10th,11th,12th grade are excluded 70% and below. 

![Figure 3c](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3c.png) <br> Combination of the total summary of 9th only grade versus 10th only and 11th only, 12th only grade. In general math and reading do not improve overall performance by isolating the 9th grade dataset. 

How does replacing the ninth-grade scores affect the following: <br>
Replacing the ninth-grade scores affects performance in math, which varies by high school. Cabrera, Griffin, Holden, Pena, Shelton, Wilson, and Wright High Schools consistently outperform others.

![Figure 4](https://github.com/davidhyongae2/school_destrict/blob/main/Figure4.png)<br>

Scores by school spending. <br>

Schools in this district spend under $619 per student, which is lower than that of higher-performing high schools. <br>

Scores by school size. <br>

![Figure 6](https://github.com/davidhyongae2/school_destrict/blob/main/Figure6.png)<br>
Schools with fewer than 2,000 students perform better in math and reading than those with more than 2,001 students, indicating that performance declines in overpopulated schools. This suggests a performance plateau at the 2,000-student mark. <br>

Scores by school type. <br>

![Figure 7](https://github.com/davidhyongae2/school_destrict/blob/main/Figure7.png) <br>
For example, the Charter school is suggested to outperform the District school type for both math and reading. 

 
## Summary
The results indicate that Thomas High School does not significantly influence reading performance; however, it does have a measurable effect on math performance. Students at Cabrera, Griffin, Holden, Pena, Shelton, Wilson, and Wright High Schools consistently outperform their peers at Thomas in mathematics. Additionally, the impact of Thomas High School on reading performance appears to be minimal.
