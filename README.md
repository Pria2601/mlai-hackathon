# MLAI-hackathon
### Thought process during working on the solution of hackathon

## Steps
- data fetching
- model training
- model testing
- hyperparameter tuning
- again model testing
- repeat steps 2 to 4 for different model
- selecting some best models
- trying various ensembling methods on it
- model testing each time
- creating submission file
- submission

## Models tried
- logistic regression
- KNN
- Naive Bayes
- Gradient Booster
- Random Forest Classifier
- Deep Learning
- SVC
- Decision Tree Classifier
- LightGBM
- xgBoost

## Ensembling Methods tried
- Voting
- Bagging
- Stacking
- Adaboost

## Final result
- best outcome came from using:-
- Random Forest Classifier, Gradient Boosting Classifier, and Naive Bayes as base models in Voting Classifier
- hyperparameer tuned to soft voting, n-estimator = 100 
- F1 value on test data came to be = 0.6839541547277938
## Submission
- Creating predicted value column along with index and converting it to csv.
## Other details
- First block has all required libraries imported.
- The models used first are stacked in order from bottom to above.
- each block has one model in it.
- F1 value on splited test result is mentioned in comments at the bottom part of code.
- Type of model is mentioned as comment on the top.
- submission file creating block was used repetedly by changing model.
## About me
### PRIYA GAWSHINDE
### 2156
  


  



















