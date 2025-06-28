DRW Crypto Market Prediction
This repository contains my submission for the DRW Crypto Market Prediction Kaggle competition. The goal of the competition is to forecast future cryptocurrency market movements using anonymized features and public data.

📁 Files
drw-crypto-market-prediction.ipynb:
Jupyter notebook containing the full modeling pipeline, including:

Data loading and preprocessing

Feature selection (20 anonymous + 5 public variables)

XGBoost model training

Prediction generation and export

prediction results for shiyuan liang.csv:
Final prediction results submitted to the competition.

🧠 Model Summary
Model used: XGBoost Regressor

Selected features: 20 anonymized + 5 public variables

Performance:

Pearson correlation coefficient on the training set: 0.81

Kaggle public leaderboard score: 0.00662 (lower is better)

🚀 Notes
The model combines effective feature selection with a robust boosting algorithm to achieve competitive performance on the leaderboard. Further improvements could include hyperparameter tuning, feature engineering, or model ensemble.
