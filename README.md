# Machine Learning Fundamentals Checkpoint (CodeGrade)

## Overview
This checkpoint is designed to test your understanding of the content from the Machine Learning Fundamentals Cumulative Lab.

Specifically, this will cover:

- Performing a train-test split to evaluate model performance on unseen data
- Applying appropriate preprocessing steps to training and test data
- Identifying overfitting and underfitting

- This project uses a Ridge Regression model to predict house sale prices. The goal is to improve model generalization and reduce overfitting compared to standard Linear Regression.

- We preprocess the data using StandardScaler, fit a Ridge Regression model with a regularization strength (alpha) of 100, and evaluate the model performance using Root Mean Squared Error (RMSE) and R-squared (R²).

## Tools and Resources
In order to complete this assignment, you will need:

- Files for this assignment:
  - ml_fundamentals_checkpoint.ipynb
  - data_description.txt
  - ames.csv
- Computer with code editor
- Anaconda environment
- Any notes you might wish to use (previous lectures, cheatsheets, etc…)

## Key Steps
- Preprocessing: Standardizing feature data using StandardScaler.
- Modeling: Training a Ridge Regression model (alpha=100, solver='sag').
- Evaluation:
   - Calculated RMSE and R² for both training and testing sets.
   - Compared Ridge Regression against standard Linear Regression.

## Future Improvements
- Tune the alpha hyperparameter with cross-validation.
- Try other regularization models like Lasso Regression.
- Feature selection or engineering to improve model accuracy.

## Author
- Created as part of a machine learning exercise.
- Feel free to fork or improve this project!