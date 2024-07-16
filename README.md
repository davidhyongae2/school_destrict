### [Link to Google Slides](https://docs.google.com/presentation/d/1m06_9EaEdJI7jc7BQkQ79riS0W0V0QgkLuyGqa2c2Dc/edit?usp=sharing). Fellowship and application.

## Overview of the school district analysis
School districts are involved with students' reading and math performance which are analyzed as a study for budget and spending regulation. 
    

1. PANDAS, numpy usage.
2. Dataset read with PANDAS.
3. Jupyter notebook to display the result of the PANDAS data frame.
4. Calculate the percentage of reading, math, and overall performance.


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
Math performance does fluctuate based on which high school they are from. For example, Cabrera High School, Griffin High School, Holden High School, and Pena High School, Shelton High School, Wilson High School, Wright High School outperform other high schools. <br>

![Figure 4](https://github.com/davidhyongae2/school_destrict/blob/main/Figure4.png)<br>

Scores by school spending. <br>

The Schools spend less than < 619 dollars per student in comparison to higher-performing high schools. < 619 dollars per student is where most of the cost is spent within this district. <br>

Scores by school size. <br>

![Figure 6](https://github.com/davidhyongae2/school_destrict/blob/main/Figure6.png)<br>
The schools with <2000 students perform better in math and reading in comparison to schools with >2001 students. Schools that are overpopulated perform far worse than those that size  <2000. This demonstrates the reading and math performance plateau at <2000. <br>

Scores by school type. <br>

![Figure 7](https://github.com/davidhyongae2/school_destrict/blob/main/Figure7.png) <br>
For example, the Charter school is suggested to outperform the District school type for both math and reading. 

 
## Summary
These results indicate that Thomas High School does not affect the outcome of the reading performance while it has some effect on the math performance. Math is outperformed in Cabrera High School, Griffin High School, Holden High School, Pena High School, Shelton High School, Wilson High School, and Wright High School. Thomas High School has a nominal effect on the percentage performance of reading.
