# Supervised ML Kaggle competion
(link to competition)[https://www.kaggle.com/c/cais-exec-team-in-house/overview]

# Program Flow
- Data exploration
  - pairwise correlation matrix with RMSE
  - histogram for data distribution
- Data cleaning
  - remove grade == 0 data, probably noise
  - one hot encoding for categorical data
- Training
  - random forest classifier
  - XG Boost
- Testing
  - 70% train, 30% test
  - cross validation
- Tuning
  - grid search hyperparameter tuning
  - bruteforce search
  - feature importance plot
- Improvements
  - reduce columns to save training time

# Result
top 3
