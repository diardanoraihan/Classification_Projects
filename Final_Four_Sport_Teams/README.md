# Final Four Basketball Teams
<hr>
In this scenario, we work as a Data Scientist for a college basketball team. The coaches have asked us to look at historical data to see which team metrics (individually or in combination) make a team more likely to make it into the Final Four. 
For example, if a team is more efficient defensively, does this have a direct relationship to their ability to get into the Final Four? What about defensively efficiency along with overall wins? Your job is to figure out if there is a combination of metrics that give a team more of a chance of making it into this tournament.

Something to keep in mind is that when trying to predict results of basketball tournaments there are many variables that need to be taken into account. As a result of this creating accurate models is incredibly hard. In the sports betting industry an accuracy rate of anything over 55% is considered good as it indicates profits.

## Machine Learning Models

We will load a historical data set from previous seasons, clean the data, and apply different classification algorithms to the data. We are expected to use the following algorithms to build your models:

- k-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression

The results are reported as the accuracy of each classifier, using the following metrics when applicable:

- Jaccard index
- F1-score
- Accuracy
- LogLoss (for Logistic Regression)

## Report

In short, the performance of these models are as follows:

| Algorithm          | Accuracy | Jaccard  | F1-score | LogLoss |
| ------------------ | -------- | -------- | -------- | ------- |
| KNN                | 0.628571 | 0.458333 | 0.628571 | NA      |
| Decision Tree      | 0.642857 | 0.473684 | 0.642857 | NA      |
| SVM                | 0.685714 | 0.521739 | 0.685714 | NA      |
| LogisticRegression | 0.571428 | 0.400000 | 0.571428 | 0.87827 |

