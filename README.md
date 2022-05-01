# School District Analysis

## Overview of the School District

In this project, we helped Maria to performe an analysis about budgets and highschoorlers grades in a School District using Python, Jupyter Notebook and Pandas. 

Our **purpose** was to analyze and report School District data such as school fundraizings and student graders in order to support Maria and the School Board Superintendent in making better decisions about high schools priorities.

We conducted two analyses because, after the first one, Maria told us that ninth graders at Thomas High School cheated in their math and reading scores. Due to this dishonet situation, we did another analysis.
We analyzed 15 high schools, 8 of the Charter type and 7 of the District type. We examined two datasets, one about the schools and the other one were about data from 39,170 students.

## Resources

We conduct the analysis with Python 3.9.7, Jupyter Notebook, and Pandas. We studied  two CSV files to report the results.

* Data Source:
  - shools_complete.csv
  - students_complete.csv

* Data size: 
  - schools_complete.csv size.- 16 rows and 5 columns (_Shool ID, school_name, type, size, budget_).
  - students_complete.csv size.- 39,171 rows and 7 columns (_Student ID, student_name, gender, grade, school_name, reading_score, math_scoore_).
  - Software: Python 3.9.7, Anaconda, Jupyter Notebook, and Pandas.

## Results

In the second analysis we imported the dependencies and cleaned the data, removing suffixes and prefixes from the student names. The following steps are listed below:

* We replaced the math and reading scores from the Ninth-grades of Thomas High School with **NaN**, which means "Not a Number", because the students cheated on their assessments. The dishonest students were 461 out of 39,170 students, which signified 1.2% of the total sample.

* After that change, we merged the _csv files_ into a new dataframe. We used various Pandas and Python methods and functions to create a dataframe of the School District. The following dataframes shows results of the School Distric of the first and second analysis, respectively:

Imagen de distric 1
imagen de distric 2

As we can see, there were no significant changes in the average scores and passing percentages, only a slight decrease in the data.

* The next step was to made a dataframe showing the academic performance and the budget per student by school. In the "Per School Summary" we can see that Thomas High School lowered its averages math and reading scores and passing math and reading percentages. The Overall Passing Percentage dropped from 90% to 65%, as we can notice in the following dataframe. 

Imagen 3

* After reviewing these results, we got the number and data of students from 10th to 12th grades at Thomas High School to repeat the analysis (without considering the 9th-grade students).

* The analysis was performed again and we obtained a _new_ Per School Analysis dataframe. The results are shown in the following screenshot:

Imagen 3

As can be seen, with these adjustments and modifications, the changes in the Passing Percentages and Averages Scores of Thomas High School (THS) are no longer the same: 

* The new Average Math Score is now 83.350937; the Average Reading Score changed to 83.896082, the Passing Math Percentage now is 93.185670%, Passing Reading Percentage adjusted to 97.018739%, and Overall Passing change to 90.630324%.

-After modifying the data for Thomas High School, we identified the best and worst performing schools.





As we can see, there were no significant changes in the average scores and passing percentages, only a slight decrease in the data.How is the District Summary afected?

How is the School Summary affected?

How does replacing the ninth-graders math and reading scores affect Thomas High School performance relative to other schools?

How does replacing the ninth-graders scores affects the following:
-Math and reading scores by grade
-Scores by school size
-Scores by school spending
-Scores by school type


## Summary
School District Analysis



Results
In the first analysis for the School District, we included all the student data, but in the second research, we remplaced the math and reading scores from the 9th grades of Thomas High School  with NaN (which means "Not a Number") because they cheated.

We also considered that there were 461 students in the Ninth-grade of Thomas High School (THS). That means that the dishonest studets represents only 1.2% of the total sample.

The following dataframe shows results of the School Distric after the second analysis was done.
