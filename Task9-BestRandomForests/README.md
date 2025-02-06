# Best Random Forests - ML

This project is focussed around finding the best Random Forest through Random Search.

### Task Outcomes

- Built a RandomForest for the above dataset (not one but many with different sets of parameters)
- Explored RandomizedSearchCV in Scikit-learn documentation
- Created a parameter grid with these values
  - n_estimators : between 10 and 200
  - max_depth : choose between 3 and 20
  - max_features : ['auto', 'sqrt', None] + list(np.arange(0.5, 1, 0.1))
  - max_leaf_nodes : choose between 10 to 50
  - min_samples_split : choose between 2, 5, or 10
  - bootstrap : choose between True or False
- Created the estimator (RandomForestClassifier)
- Created the RandomizedSearchCV with estimator, parameter grid, scoring on roc auc, n_iter = 10, random_state=RSEED(50) for same reproducible results
- Fit the model
- Explored the best model parameters
- Used the best model parameters to predict
- Plotted the best model ROC AUC Curve
- Plotted the Confusion Matrix
- Insights or observations recorded

Dataset used: https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system
(The dataset is 516.21MB and github only allows 100MB, so make sure you have enough memory to run this)

Check out the project in this github repo: https://github.com/athikaf/Best_Random_Forests-ML/

If you have any doubts/questions or if you encounter any errors, please reach out to <a href="https://www.linkedin.com/in/athika-fatima/"> Athika Fatima</a>.
