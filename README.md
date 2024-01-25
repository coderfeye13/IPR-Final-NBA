# IPR-Final-NBA

# IPR-Final

![alt text](https://github.com/coderfeye13/IPR-Final/blob/main/nbalogo.jpeg?raw=true)


Introduction:

This project aims to analyze the games played in the American Basketball League (NBA) between 2016 and 2018.
based on databases where various metrics are recorded. Data in the database is preprocessed 
and data processing steps were applied. In this project, the prediction of match scores 
a classification performance was evaluated.

Data:
There are 4920 samples in total.
Each sample contains 123 features. Therefore, each file contains a table with 4920 x 123 entries. 
2460 samples were collected from 2016-2017 matches and 2460 samples were collected from 2017-2018 matches.
The dataset is provided as 2016-2017.csv and 2017-2018.csv. The first line of the files contains the sample names
while the other rows indicate that the metrics of the relevant instances have been collected.

Objective:
This project aims to achieve the highest percentage of correct classifications.
For this purpose, the target variable was selected and predicted based on other metrics.
Then the accuracy and cross-validation of various classification algorithms were calculated. 

Classification Algorithms:

- Random Forest 
- SVC
- KNeighbors 
- Decision Tree 

Performance Measures:
Sensitivity, specificity and AUC were calculated as outputs of program performance.

Sensitivity: = Number of correct predictions of the first class / Total number of samples in the first class

Specificity = Number of correct guesses in the second class / Total number of samples in the second class

AUC: Area under the ROC curve.
