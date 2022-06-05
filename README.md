### [Link to Google Slides](https://docs.google.com/presentation/d/10CvPK2qqDjlCGKCmx7MFF_FP-1T87Tl57Uyzh-Up120/edit#slide=id.g1316cf23dc4_3_75) Fellowship and application.

## Overview of the school district analysis

School districts are involved with students' reading and math performance which are analyzed as a study for budget and spending regulation. 
    

1. PANDAS, numpy usage.
2. Dataset read with PANDAS
3. Jupyter notebook to display the result of PANDAS dataframe.
4. Calculate the percentage of reading, math, and overall performance.


## Resources
- Data Source1: schools_complete.csv,
- Data Source2: students_complete.csv
- Program language: Python 3.8

## Results 
-How is the district summary affected?

![Figure 1](https://github.com/davidhyongae2/school_destrict/blob/main/Figure1.png). The charter school and district schools are sub grouped into different clusters. 

-How is the school summary affected?

![Figure 2](https://github.com/davidhyongae2/school_destrict/blob/main/Figure2.png). Grades 10th, 11th and 12th are included while 9th is excluded from this summary. 

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Figure 3a](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3a.png). Math score of 9th,10th,11th,12th grade are excluded 70% and below.

![Figure 3b](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3b.png). Reading scores of 9th,10th,11th,12th grade are excluded 70% and below. 

![Figure 3c](https://github.com/davidhyongae2/school_destrict/blob/main/Figure3c.png). Combination of the total summary of 9th only grade versus 10th only and 11th only, 12th only grade. In general the math and reading does not improve overall performance by isolating the 9th grade dataset. 

How does replacing the ninth-grade scores affect the following:

Math performance does fluctuate based on which high school they are from even if math is excluded from Thomas High School. For example, Cabrera High school, Griffin High school, Holden High school, and Pena High school, Shelton High School, Wilson High School,Wright High School outperform other high schools. While reading performance does not. 

![Figure 4](https://github.com/davidhyongae2/school_destrict/blob/main/Figure4.png).

Scores by school spending. 

![Figure 5](https://github.com/davidhyongae2/school_destrict/blob/main/Figure5.png). The Schools spend less than <$619 dollars per student in comparison to high cost >$620 dollar students in higher performing high schools. The difference is bigger on the higher cost per students range than the <$620 range costing students. Lastly, the <$619 dollar per student is where most of the cost is spent within this district. 

Scores by school size.

![Figure 6](https://github.com/davidhyongae2/school_destrict/blob/main/Figure6.png).
The schools with <2000 students perform better in math and in reading in comparison to schools with >2001 students. Schools which are overpopulated with >2000 students perform far worse than size  <2000. Clearly, demonstrating the reading and math performance plateau at <2000. 

Scores by school type.

![Figure 7](https://github.com/davidhyongae2/school_destrict/blob/main/Figure7.png.
For example, the Charter school is suggested to outperform the District school type for both math and reading. 

 
## Summary
These results indicate the reduction of Thomas High School has no effect on the outcome of the reading performance while it has some affect on the math performance. Math is out performed in Cabrera High school, Griffin High school, Holden High school, and Pena High school, Shelton High School, Wilson High School,Wright High School than other high schools. While the reduction of Thomas High School for reading has a nominal effect on the percentage performance of reading on all grades in district or in charter schools.
