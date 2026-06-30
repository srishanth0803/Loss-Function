# Loss-Function
A loss function measures how far a model’s predictions are from the actual values. It helps the model learn by minimizing prediction errors during training.

Loss Functions for Regression

In regression, the output is continuous (e.g., house price, temperature). Loss functions measure the difference between predicted and actual numeric values.

Common regression loss functions:

MSE (Mean Squared Error): Squares errors, giving higher penalty to large mistakes.
MAE (Mean Absolute Error): Uses absolute differences and is more robust to outliers.
RMSE (Root Mean Squared Error): Square root of MSE, easier to interpret because it is in the original units.
Loss Functions for Classification

In classification, the output is a category or class (e.g., spam/not spam, cat/dog). Loss functions measure how well predicted probabilities match actual classes.

Common classification loss functions:

Binary Cross-Entropy: Used for two-class problems.
Categorical Cross-Entropy: Used for multi-class problems.
Hinge Loss: Common in scikit-learn SVM models.

The goal in both regression and classification is to minimize the loss so the model makes better predictions.
