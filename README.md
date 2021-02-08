# Machine-Learning-Project ( Basketball tournament prediction)

Objective
The objective of this project is to determine which basketball teams are most likely to make it to the semifinal round of the College Basketball Tournament known as the Final Four.
Introduction
In this scenario, as a Data Scientist working for a college basketball team. Your coaches have asked you to look at historical data to see which team metrics (individually or in combination) make a team more likely to make it into the Final Four. For example, if a team is more efficient defensively, does this have a direct relationship to their ability to get into the Final Four? What about defensively efficiency along with overall wins? Your job is to figure out if there is a combination of metrics that give a team more of a chance of making it into this tournament.
Something to keep in mind is that when trying to predict results of basketball tournaments there are many variables that need to be taken into account. As a result of this creating accurate models is incredibly hard. In the sports betting industry an accuracy rate of anything over 55% is considered good as it indicates profits.
I will load a historical data set from previous seasons, clean the data, and apply different classification algorithms to the data. These are the model i will be using for the analysis. 
- k-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression
The results are reported as the accuracy of each classifier, using the following metrics when applicable:
- Jaccard index
- F1-score
- Accuracy


| Algorithm          | Accuracy | Jaccard  | F1-score | LogLoss |
| ------------------ | -------- | -------- | -------- | ------- |
| KNN                | 0.628571 | 0.458333 | 0.628571 | NA      |
| Decision Tree      | 0.642857 | 0.473684 | 0.642857 | NA      |
| SVM                | 0.685714 | 0.521739 | 0.685714 | NA      |
| LogisticRegression | 0.685714 | 0.521739 | 0.685714 | 1.03719 |
