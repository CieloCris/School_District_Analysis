# School District Analysis

## Overview of the School District

In this project, we helped Maria to perform an analysis of budgets and high schoolers' grades in a School District using Python, Jupyter Notebook, and Pandas. 

Our **purpose** was to analyze and report School District data such as school fundraising and student graders in order to support Maria and the School Board Superintendent in making better decisions about high school priorities.

We conducted two analyses because, after the first one, Maria told us that the ninth-graders at Thomas High School cheated in their math and reading scores. Due to this dishonest situation, we did another analysis.
We analyzed 15 high schools, 8 of the Charter type and 7 of the District type. We examined two datasets, one about the schools and the other one about data from 39,170 students.

## Resources

We conduct the analysis with Python 3.9.7, Jupyter Notebook, and Pandas. We studied two CSV files to report the results.
* Data Source:
  - shools_complete.csv
  - students_complete.csv
* Data size: 
   - schools_complete.csv size.- 16 rows and 5 columns (_Shool ID, school_name, type, size, budget_).
   - students_complete.csv size.- 39,171 rows and 7 columns (_Student ID, student_name, gender, grade, school_name, reading_score, math_scoore_).
   - Software: Python 3.9.7, Anaconda, Jupyter Notebook, and Pandas.

## Results

In the second analysis, we imported the dependencies and cleaned the data, removing suffixes and prefixes from the student names. The following stages are listed below:

* We replaced the math and reading scores from the Ninth-grades of Thomas High School with **NaN**, which means "Not a Number" because the students cheated on their assessments. The dishonest students were 461 out of 39,170 students, which signified 1.2% of the total sample

* After the data transformation, we merged the _csv files_ into a new dataframe. We used various Pandas and Python methods and functions to create a dataframe of the School District. 

The following dataframes show the results of the School District of the first and second analysis, respectively:

Imagen de distric 1
imagen de distric 2

As we can see, there were no significant changes in the average scores and passing percentages, only a slight decrease in the data.

* The next step was to make a dataframe showing the academic performance and the budget per student by the school. In the "Per School Summary," we can see that Thomas High School lowered its Averages Math and Reading scores, and Passing Math and Reading Percentages. The Overall Passing Percentage dropped from 90.948012% to 65.076453%, as we can notice in the followings dataframes:

Imagen 3 per school summary viejo
Imagen 4 per school summary nuevo

* After reviewing these results, we got the number and data of students from 10th to 12th grades at Thomas High School to repeat the analysis (without considering the 9th-grade students).

* The analysis was performed again and we obtained a _new_ Per School Analysis dataframe, adding the Spending Ranges (Per Student) column. The results are shown in the following screenshot:

Imagen 5 - challenge_bins_school

As can be seen, with these adjustments and modifications, the changes in the Passing Percentages and Averages Scores of Thomas High School (THS) are no longer the same: 

* The new Average Math Score is now 83.350937; the Average Reading Score changed to 83.896082, the Passing Math Percentage now is 93.185670%, the Passing Reading Percentage adjusted to 97.018739%, and te Overall Passing changed to 90.630324%. These last modifications revealed that the Overall Passing Percentage of the first study was 90.948012%, and in the new analysis the percentage dropped to 90.630324%. 

* After modifying the data for Thomas High School, we identified the best and worst-performing schools.

The following dataframe shows the top 5 schools in the district:

Imagen 6 - Top schools

Despite having dropped 9th graders for cheating, We can observe that Thomas High School is still among the top-performing schools. Although there were changes in the average scores and passing percentages (because some points decreased), these didn't t portray an impact on the data.

The bottom schools are presented in the following dataframe. In this case, there was no change in the school's data:

Imagen 7 - Bottom schools

* Our next step was to collect the math and reading average scores and the passing math and reading percentage by grade and school. In the coming screenshots we show the dataframes in this regard:

Imagen 8 grados mate
Imagen 9 grados reading

We can observe that Thomas High School's 9th-grades data is shown as NaN and was not part of the analysis.


* In the last section of the study, we analyzed the academic performance scores by school spending, school size, and school type.

Imagen 10 Spending
Imagen 11 size
Imagen 12 type

After analyzing the previous dataframe, we can say there were no substantial changes in the data, but we can communicate that the budget per student doesn't have a decisive and unique influence on the math and reading scores and the approval percentages. That means that a school spending more per student will not always mean better academic performance.

For instance, in our data, we have Cabrera High School, which is among the top 5 schools with the best academic performance with an Overall Passing Percentage of 91.334769%, and a budget of $592 dollars per student. In contrast, Johnson High School is among the lowest-performing schools, with an Overall Passing of 53.539172% and a per-student budget of $650 dollars.

Regarding size, we can observe that schools with the best academic performance are the medium ones, which have between 1,000 and 1,999 students. Finally, and depending on the type of school, we can deduce that Charter-type schools perform better than District-type schools since the former have an overall passing rate of 90% while the latter only reaches 54%.

## Summary

We can conclude that it is valuable to do this type of analysis to know the situation of the Schools District to make adjustments in academic strategies and the budget per school. We can conclude the performance in scores doesn't depend much on the budget but rather on the type, size of the school, and other aspects.

The School Board Superintendent and Maria must research other elements that could influence the student's academic performance (i.e., the student's socioeconomic level and family situation, among many other factors).

Finally, we don't have to forget that the dishonest behavior of the Ninth-graders at Thomas High School complicated our analysis and we had to make adjustments to the data in order to prevent additional bias in the project.
