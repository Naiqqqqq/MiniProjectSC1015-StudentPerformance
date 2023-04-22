# MiniProjectSC1015-StudentPerformance

## About

This is a Mini-Project for SC1015.

### Problem Statement
How can we help students improve their learning proficiency in their respective mother tongue?

### Motivation
Singapore is a multicultural society with a bilingual policy that emphasises the importance of being proficient in both English and one’s mother tongue. Besides language proficiency, it is also about preserving cultural identity and heritage. Being fluent in our mother tongue can also help us communicate effectively with our grandparents, or the older generation who are not fluent in English. Research has also shown that being proficient  in one's mother tongue has multiple benefits. On top of boosting overall academic performance, it also improves cognitive abilities, delays the onset of dementia and enhances an individual's memory. 

### Data Set
UCI Learning Machine: Student Alcohol Consumption (Kaggle)
https://www.kaggle.com/datasets/uciml/student-alcohol-consumption

### Data Cleaning
Total of 1044 entries with 34 unique numerical and categorical variables. 
Cleaned the data by removing unwanted data such as students' maths results. As the data only contained information on each student’s grades for 3 different tests, we wanted an easier way to analyse the data. 
To prepare the data for easier analysis, we generated another column which was the average grades of each student for the 3 tests.


### Exploratory Data Analysis
Correlation matrix to see how each variable correlated to the average grade. 
For the students’ parents’ education, both the mother and father’s education level has a positive correlation with other variables. We noticed that students tend to perform better in school, are healthier with less absences and have better study habits.

For study time, we found that the majority of students spend around 2 to 5 hours studying per week and another big portion of students spend less than 2 hours studying. From the box-plot, we can see that students who spend less than 2 hours have the lowest median average grades whereas students spending 5 to 10 hours show a higher median average grade.

For past failures, student’s with lesser past failures tend to have higher average grades. This shows that these students may have a better foundation, which leads to easier learning. 

For Age, we found that as a student gets older, their median average grade tends to be lower.

For Absences, the student’s median average grades get lower as the absences increase. 

For the student’s alcohol consumption on both weekdays and weekends, the higher the level of alcohol intake, the lower the average total grade.

One Hot Encoding (NEW) + Random Forest (NEW)

Used one-hot encoding to encode the categorical features such as the strength of their family relationship, how often they go out, the students’ health, and their parent’s jobs.  This brings all the features to the same scale so we can assess the importance by coefficients of the linear regression model. 

As seen in the bar plot, the most important features include: failures, daily alcohol intake, higher, free time after school, and how often they go out with their friends. 

Random Forest was used as well to see the most important features that would affect grades.

Based on our exploratory analysis, we have identified the data types, distribution, and summary statistics of the variables, enabling us to visualize data patterns and detect outliers, skewed and unbalanced data.




