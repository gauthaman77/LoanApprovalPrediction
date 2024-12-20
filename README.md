## Loan Approval Prediction

### Problem Statement
Given a set of features with outcome as loan approved, predict the outcome. The competition details are given [here](https://www.kaggle.com/competitions/playground-series-s4e10) . This solution was among the top 8% of all solutions

### What worked
- Using Catboost with all features labelled as categories
- Hill Climbing with various models, cross validation also present for a robust model and avoid overfitting.
- Stacking with various models, cross validation also present.
  (Both solutions have been provided as separate ipynb files. Although stacking gave good results, the best result was given by hill climbing approach)

### What did not work
- Feature Engineering

### Hill Climbing approach
![alt text](https://github.com/user-attachments/assets/ffc8948c-274f-4be7-8fca-cf4209b6c799)

### Stacking Approach
![alt text](https://github.com/user-attachments/assets/caba84f1-3ebc-4ed3-8e59-7d3ce2e13d9a)
