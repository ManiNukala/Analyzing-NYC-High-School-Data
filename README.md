# Analyzing-NYC-High-School-Data

One of the most controversial issues in the U.S. educational system is the efficacy of standardized tests, and whether they're unfair
to certain groups. Given our prior knowledge of this topic, investigating the correlations between SAT scores and demographics might be
an interesting angle to take. We could correlate SAT scores with factors like race, gender, income, and more.

The SAT, or Scholastic Aptitude Test, is an exam that U.S. high school students take before applying to college. Colleges take the test
scores into account when deciding who to admit, so it's fairly important to perform well on it.
The test consists of three sections, each of which has 800 possible points. The combined score is out of 2,400 possible points
(while this number has changed a few times, the data set for our project is based on 2,400 total points). Organizations often ran
k high schools by their average SAT scores. The scores are also considered a measure of overall school district quality.

New York City makes its data on high school SAT scores available online, as well as the demographics for each high school.

We will be using the following relevant datasets from data.cityofneyyork.us :
1) SAT scores by school - SAT scores for each high school in New York City. This is in the file 'sat_results.csv'.
2) School directory - A directory of all the high schools can be found in 'hs_directory.csv'.
3) Class size - Information on class size for each school. You can find this information in the 'class_size.csv' file.
4) AP test results - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn
a student college credit in that subject). The data is in the file 'ap_2010.csv'.
5) Graduation outcomes - The percentage of students who graduated, and other outcome information. Data is included in 'graduation.csv'.
6) Demographics - Demographic information for each school. This data is found in the file 'demographics.csv'.
7) School survey - Surveys of parents, teachers, and students at each school. The data can be found in the files 'survey_all.txt' and 
'survey_d75.txt' which include results from NYC's district 75.

In this project we will be combining these datasets into a single dataframe and dive in with EDA.
