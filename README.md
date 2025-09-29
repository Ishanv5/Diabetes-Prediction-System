🩺 Diabetes Prediction using Support Vector Machine (SVM)

This project predicts whether a person has diabetes based on medical attributes using a Support Vector Machine (SVM) classifier. The dataset is preprocessed with standardization, and the model performance is evaluated using train-test split and accuracy score.

📌 Project Overview

Dataset: Medical data with attributes such as glucose level, BMI, insulin, age, etc.

Goal: Predict whether a patient is Diabetic (1) or Non-Diabetic (0).

Algorithm: Support Vector Machine (SVM) with data standardization.

Evaluation Metric: Accuracy Score on test data.

⚙️ Features

Data loading and preprocessing

Feature standardization using StandardScaler

Train-test split for unbiased evaluation

Training SVM classifier on scaled features

Accuracy score calculation on predictions

🚀 Tech Stack

Python

NumPy

Pandas

Scikit-learn (SVM, StandardScaler, train_test_split, accuracy_score)

📊 Workflow

Load diabetes dataset (CSV format)

Standardize the feature values using StandardScaler

Split the dataset into training and testing sets using train_test_split

Train an SVM classifier on training data

Evaluate model performance with accuracy score

Make predictions on new/unseen data

✅ Why SVM?

SVM is highly effective in binary classification problems like diabetes prediction.

It works well on high-dimensional data and can find the optimal separating boundary between classes.

SVMs are robust against overfitting, especially when features are standardized.

✅ Why Data Standardization?

SVM is sensitive to the scale of features.

Standardization ensures that all features have the same scale (mean = 0, variance = 1).

Prevents features with large numerical ranges from dominating the model.

Improves model accuracy and stability.

📈 Results

The model achieved a strong accuracy score on test data after standardization.

Performance may vary slightly depending on the dataset split.
