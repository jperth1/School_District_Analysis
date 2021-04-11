# School_District_Analysis


# Overview of School District Analysis

This analysis aims to present the school board with performance trends at the school and district level. This analysis uses standardize math and reading data test data to calculate the following key metrics: average math and reading scores, percentage of students passing math and reading, and the overall percentage of students passing both math and reading at the district and school level. The patterns and trends in this analysis are intended to help inform the school board in making decisions related to the school district budget allocation.

Due to evidence of academic dishonesty, this report will provide a comparison of an original analysis and two updated analysis that includes amendments to the data to take into consideration the evidence of academic dishonesty. The first updated analysis replaces the key metrics –reading and math scores—for the 9th grade cohort at Thomas High School with the value “NaN” (not a number). The second updated analysis eliminated the 9th grade math and reading scores from Thomas high school, and only evaluates key metrics from the 10th to 12th grade at Thomas high school. These amendments are an attempt to uphold state-testing standards. The data from all other schools in the district are left intact. 

The analysis completed the following tasks on the original and updated data to provide the school board with performance trends on the district and school level:

A district summary based on the original and updated data comprising the following key metrics:

-	Total number of students in the district
-	Total number of schools in the district
-	The total budget for the district
-	The average math score for the district
-	The average reading score for the district
-	The percentage of students in the district passing math
-	The percentage of students in the district passing reading
-	The overall percentage of students in the district who passed math and reading

-	A school summary based on the original and updated data comprising of the following key metrics:
-	School name
-	School type 
-	Total number of students at the school
-	The school’s total budget 
-	The school’s per student budget
-	The school’s average math score 
-	The school’s average reading score
-	The percentage of students at the school passing math
-	The percentage of students at the school passing reading
-	The overall percentage of students in the school passing math and reading

## Resources

-	Data Source: school_complete.csv, students_complete.csv
-	Software: Python 3.9.1, Jupyter Notebook 6.1.4


# Results

Replacing the math and reading scores with “nan” for the 9th grade cohort at Thomas High School as well as eliminating the math and reading scores for the same 9th grade cohort affects the key metrics on the district level and school level.

## District Level Affect

The district summary was slightly affected after the reading and writing scores for 9th graders at Thomas High School were replace. Replacing those scores with “nan” resulted in the following effects on district level averages:
- The average math scores dropped by 1/10 of a percent, from 79.0 to 78.9
- the average reading scores stays the same at 81.9
- the percentage of students passing math dropped by 2/10 of a percent, from 75% to 74.8%
- the percentage of students passing reading dropped by 3/10 of a percent, from 86% to 85.7%
- the overall percentage of students passing both math and reading dropped by 1/10 of a percent, from 65% to 64.9%
- No affect was present on the total number of schools, total number of students, or total district budget


### District Summary from Original Data
![PySchool_Challenge_District_Summary_Original](/Resources/PySchool_Challenge_District_Summary_Original.png)

### District Summary from Updated Data

![PySchool_Challenge_District_Summary_Updated](/Resources/PySchool_Challenge_District_Summary_Updated.png)





## School Level Affect

After replacing the math and reading scores with “nan” for the 9th grade at Thomas High School, only Thomas High School’s school summary was affected. Replacing those scores with “nan” had the following effect on Thomas High School’s school level summary:
-	The average math score at Thomas high school dropped by less than 1/10 of a percent, from 83.418349 to 83.350937
-	The average reading score at Thomas high school increased by less than 1/10 of a percent, from 83.848930 to 83.896082
-	The percentage of students at Thomas high school passing math fell significantly, from approximately 93.272% to 66.911%; this is a decrease of approximately 26.361%
-	The percentage of students at Thomas high school passing reading fell significantly, from approximately 97.308% to 69.663%; this is a decrease of approximately 27.645%
-	The overall percentage of students at Thomas high school passing both math and reading fell significantly, from approximately 90.948% to 65.076%; this is a decrease of approximately 25.875%

### School Summary from Original Data

![PySchool_Challenge_School_Summary_Original](/Resources/PySchool_Challenge_School_Summary_Original.png)

### School Summary After Replacing 9th Grade Scores at Thomas high school with “NaN” 

![PySchool_Challenge_School_Summary__Nineth_Grade_Included_Updated](/Resources/PySchool_Challenge_School_Summary__Nineth_Grade_Included_Updated.png)


### School Level Affect After Eliminating 9th Grade Scores at Thomas High School

The school summary was further reevaluated by eliminating the math and reading scores for 9th graders at Thomas high school and replacing it with only the scores from 10th- 12th grade at Thomas high school. Replacing the data with only scores from the 10th-12 grade at Thomas high school had the following effect on Thomas high school’s school level summary:
-	The average math score at Thomas High School became 83.350937
-	The average reading score at Thomas high school became 83.896082
-	The percentage of students at Thomas high school passing math became approximately 93.186%
-	The percentage of students at Thomas high school passing reading became approximately 97.019%
-	The overall percentage of students at Thomas high school passing both math and reading became 90.630%
-	Metrics for other district schools were not affected 

![PySchool_Challenge_THS_Summary_Updated_ninth_grade_removed](/Resources/PySchool_Challenge_THS_Summary_Updated_ninth_grade_removed.png)


## Thomas High School’s Relative Performance 

Prior to replacing the ninth graders’ math and reading scores, Thomas High School’s ranked second of the top five schools in the district, based on its overall passing percentage, 90.948%

![PySchool_Challenge_Top_Schools_Original](/Resources/PySchool_Challenge_Top_Schools_Original.png)

After replacing the ninth graders’ math and reading scores, Thomas High School’s ranking fell to the eighth position in the district, based on its overall passing percentage, 65.076%

![PySchool_Challenge_THS_Relative_Performance](/Resources/PySchool_Challenge_THS_Relative_Performance.png)

After eliminating the nineth-grade math and reading scores, Thomas high school returned to its original second place rank for schools in the district, based on its overall passing percentage, 90.630%

![PySchool_Challenge_Top_Schools_Update_Grade9_Removed](/Resources/PySchool_Challenge_Top_Schools_Update_Grade9_Removed.png)



### Math and Reading Scores by Grade Level

Prior to replacing the ninth graders’ math and reading scores, the ninth grade at Thomas high school had an average math score of 83.6 and an average reading score of 83.7. 

### Average Math Scores by School and Grade Level from Original Data

![PySchool_Challenge_Math_Scores_By_Grade_Original](/Resources/PySchool_Challenge_Math_Scores_By_Grade_Original.png)

### Average Reading Scores by School and Grade Level from Original Data

![PySchool_Challenge_Reading_Scores_By_Grade_Original](/Resources/PySchool_Challenge_Reading_Scores_By_Grade_Original.png)


After replacing the ninth-grade math and reading scores, the ninth grade at Thomas high school did not have an average math or reading scores, as each student’s score was replaced with “nan”, also known as “not a number”. The scores replacement among the ninth-grade students had no effect on score averages among 10th-12th graders at Thomas high school, nor on any other grade-level averages for schools in the district. 

### Average Math Scores by School and Grade Level from Updated Data

![PySchool_Challenge_Math_Score_By_Grade_Updated](/Resources/PySchool_Challenge_Math_Score_By_Grade_Updated.png)

### Average Reading Scores by School and Grade Level from Updated Data

![PySchool_Challenge_Reading_Scores_By_Grade_Updated](/Resources/PySchool_Challenge_Reading_Scores_By_Grade_Updated.png)


## School Spending Per Student and Scores

There was no effect on the scores and school spending per student after eliminated the 9th grade math and reading scores from Thomas high school.

### School Spending Per Student and Scores from Original Data

![ PySchool_Challenge_Performance_By_Spending_Bins_Original](/Resources/PySchool_Challenge_Performance_By_Spending_Bins_Original.png)


### School Spending Per Student and Scores from Updated Data

![PySchool_Challenge_Performance_By_Spending_Bins_Updated](/Resources/PySchool_Challenge_Performance_By_Spending_Bins_Updated.png)


## School Size and Scores 
There was no effect on the scores and school size after eliminated the 9th grade math and reading scores from Thomas high school.

### School Size and Scores from Original Data

![PySchool_Challenge_Performance_By_Size_Bin_Original](/Resources/PySchool_Challenge_Performance_By_Size_Bin_Original.png)


###School Size and Average Scores from Updated Data

![PySchool_Challenge_Performance_By_Size_Bin_Updated](/Resources/PySchool_Challenge_Performance_By_Size_Bin_Updated.png)


## School Type and Scores

There was no effect on the scores and school type after eliminated the 9th grade math and reading scores from Thomas high school.

### School Type and Average Scores from Original Data

![ PySchool_Challenge_Performance_By_Type_Original](/Resources/PySchool_Challenge_Performance_By_Type_Original.png)

### School Type and Average Scores from Updated Data

![PySchool_Challenge_Performance_By_Type_Updated](/Resources/PySchool_Challenge_Performance_By_Type_Updated.png)


