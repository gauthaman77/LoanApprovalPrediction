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

## Hill Climbing approach
![alt text](https://github.com/user-attachments/assets/4037e394-0165-4576-ba5e-53f3305545ad)
