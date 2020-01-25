# Analyzing NYC High School Data
## Introduction
New York City has a significant immigrant population and is very diverse, so comparing demographic factors such as race, income, and gender with SAT scores is a good way to determine whether the SAT is a fair test. For example, if certain racial groups consistently perform better on the SAT, we would have some evidence that the SAT is unfair. 

A significant amount of data has been published, concerning student SAT scores by high school, along with additional demographic data sets. The datasets are the following:

* [SAT scores by school](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4) - SAT scores for each high school in New York City
* [School attendance](https://data.cityofnewyork.us/Education/2010-2011-School-Attendance-and-Enrollment-Statist/7z8d-msnt) - Attendance information for each school in New York City
* [Class size](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3) - Information on class size for each school
* [AP test results](https://data.cityofnewyork.us/Education/2010-AP-College-Board-School-Level-Results/itfs-ms3e) - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject)
* [Graduation outcomes](https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a) - The percentage of students who graduated, and other outcome information
* [Demographics](https://data.cityofnewyork.us/Education/2006-2012-School-Demographics-and-Accountability-S/ihfw-zy9j) - Demographic information for each school
* [School survey](https://data.cityofnewyork.us/Education/2011-NYC-School-Survey/mnz3-dyi8) - Surveys of parents, teachers, and students at each school

## Scope 

This project reads a number of different datasets (see above), combines them into a single one, clean pandas dataframe and further processes it, aiming to investigate potential relationships between demographics and SAT scores.

## Outcomes 

* North districts are characerized by higher safety scores. Specifically, the Upper Manhattan, the Bronx and parts of Queens have on average higher safety scores, in contrast to Brooklyn.

* There is suspicion the SAT Scores to distribute "unevenly" among the races, with the "white" and "yellow" students to "enjoy" higher scores.

* The higher the number of students in a High School that take at least on AP exam, does not necessarily mean that this school will note higher SAT scores.

[*It was created while studying Data Science in DataQuest platform, in an effort to enhance my ability to Communicate results using Visualitzations, Reason about data from varied sources and stay Motivated to continuously implement newly aquired skills & capabilities, so as to enrich my portfolio of data science-oriented projects*] 