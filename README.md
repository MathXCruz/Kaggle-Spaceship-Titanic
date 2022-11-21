# Spaceship Titanic

This project shows my solution to the [Spaceship Titanic Kaggle competition](https://www.kaggle.com/competitions/spaceship-titanic/overview).

I'm updating this repo with every major update I make, to record how I got to each score.

 - **Attempt 1 [Score = 0.80243]:** the focus was 100% on the EDA and Feature Engineering. I used a GradientBoostClassifier with no hyperparameter tuning.

 - **Attempt 2 [Score = 0.80336]:** Added a few more ML models to compare the results and also hyperparamter-tuning with cross validation for the model that best performed.

  - **Attempt 3 [Score = 0.80406]:** Added LGBM and model stacking, with some new features and deeper feature engineering. The model started to overfit a lot, with ~.9488 being my best local validation score, so I started removing some variables to try to addres this problem.

 _Next steps: feature engineering refinement, feature selection refinement, possibly adding a NN._

