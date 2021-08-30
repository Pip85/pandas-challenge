# **practice-pandas**

Student project - analyze school district data using pandas & Jupyter Notebook

## **software/tools used**

> pandas:  https://pandas.pydata.org/<br>
> Jupyter Notebook:  https://jupyter.org/<br>

## **data resources**

*Resources provided by:* <br>
 © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.<br>
> -  https://github.com/Pip85/pandas-school_district_analysis/blob/main/PyCitySchools/Resources/schools_complete.csv<br>
> -  https://github.com/Pip85/pandas-school_district_analysis/blob/main/PyCitySchools/Resources/students_complete.csv<br>

## **project background**<br>

Well done! Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

Your final report should include each of the following:

### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

![district_summary](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/district_summary.png)<br>

### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

![school_summary](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/school_summary.png)<br>

### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

![top_performing](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/top_performing_schools.png)<br>

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

![bottom_performing](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/bottom_performing_schools.png)<br>

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

![math](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/math.png)<br>

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

![reading](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/reading.png)<br>

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

![spending](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/spending.png)<br>

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

![scores_size](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/scores_size.png)<br>

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District)

![scores_type](https://github.com/Pip85/pandas-school_district_analysis/blob/main/Images/scores_type.png)<br>

## **acknowledgments**

* *Background and datasets provided as part of Georgia Tech Data Analytics Boot Camp:*<br>

    © 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

*  Project Author:  Valerie Pippenger - https://github.com/Pip85

## **process**

* This project required merging two data files of metrics on a school district, cleaning and organizing data into tables
for data analysis on school performance.<br>
* Metrics include school size, spending, type of school (district or charter) and performance in math, reading & both.<br>
* The first table provides a summary shot of performance in reading, math and overall in the district as a whole.<br>
* The second table provides a more detailed look at performance in those same categories at the individual school level.<br>
* The following two tables look at the top and bottom performers indicating the better performance in charter type schools.<br>
* Tables 5 & 6 examine performance by school across each grade (9th through 12th).<br>
* The final three tables examine performance based on school spending per student, school size and type.<br>

* Jupyter Notebook link:<br>
  https://github.com/Pip85/pandas-school_district_analysis/blob/main/PyCitySchools/PyCitySchools.ipynb<br>

* Analysis:  <br>
https://github.com/Pip85/pandas-school_district_analysis/blob/main/PyCitySchools/pandas_challenge%20-%20PyCitySchools%20Analysis.docx