# Decision Tree for Iris Dataset

**Author:** Kunal Yadav  
**Email:** mailmekunal2002@gmail.com

## Abstract

This project explores the application of Decision Trees in machine learning, specifically for classification and regression tasks using the famous Iris dataset. Decision Trees are powerful tools for both classification and regression, and in this report, we delve into their usage for predicting the species of Iris flowers and the sepal length of the flowers. We analyze the data, split it into training and testing sets, and evaluate the model's performance, achieving a classification accuracy of approximately 63.33% and a mean squared error of 0.1337.

## Introduction

Decision Trees are versatile machine learning algorithms that can be used for classification and regression tasks. In this project, we utilize Decision Trees to classify Iris flowers' species and predict their sepal length based on other attributes.

## Methods

### Data Preparation

- The Iris dataset, a well-known benchmark dataset, was used for this project.
- The dataset includes attributes such as Sepal Length, Sepal Width, Petal Length, Petal Width, and Species.
- The data was loaded and examined to understand its structure.

### Classification with Decision Trees

- For classification, we used the DecisionTreeClassifier from scikit-learn.
- The dataset was split into training and testing sets.
- The model was trained on the training set and evaluated on the testing set.
- Classification accuracy was computed to measure model performance.

### Regression with Decision Trees

- For regression, we used the DecisionTreeRegressor from scikit-learn.
- We predicted the sepal length of Iris flowers based on their petal length.
- Mean Squared Error (MSE) was calculated as a metric for regression performance.

## Results

### Classification Results

- Classification Accuracy: ~63.33%
- Confusion Matrix:

  |            | Predicted Setosa | Predicted Versicolor | Predicted Virginica |
  |------------|------------------|-----------------------|----------------------|
  | True Setosa     | 22             | 0                     | 1                    |
  | True Versicolor | 5              | 6                     | 8                    |
  | True Virginica  | 0              | 5                     | 13                   |

### Regression Results

- Mean Squared Error (MSE) for Sepal Length Prediction: ~0.1337

## Discussion

The Decision Tree model achieved a classification accuracy of approximately 63.33%, indicating its effectiveness in classifying Iris flower species. For regression, the model's MSE was found to be approximately 0.1337, demonstrating its ability to predict sepal length based on petal length.

## Conclusion

In this project, we explored the use of Decision Trees for both classification and regression tasks on the Iris dataset. Decision Trees proved to be valuable tools for these tasks, and their performance was evaluated with promising results.

---
