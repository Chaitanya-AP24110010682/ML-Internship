# Student Score Prediction Using Machine Learning

## Overview

This project demonstrates a simple Machine Learning model that predicts a student's exam score based on the number of hours studied. The model is built using Python and the Scikit-Learn library and uses the Linear Regression algorithm.

## Problem Statement

The objective of this project is to predict student exam scores based on study hours. By analyzing historical data, the model learns the relationship between study time and academic performance and uses it to make predictions for new inputs.

## Why Machine Learning?

Machine Learning enables computers to learn patterns from data and make predictions without being explicitly programmed. In this project, Machine Learning is used to identify how study hours influence exam scores and to estimate scores for students based on their study time.

## Dataset

The dataset contains two columns:

* Hours: Number of hours studied
* Score: Exam score obtained

Example:

| Hours | Score |
| ----- | ----- |
| 1     | 20    |
| 2     | 30    |
| 3     | 40    |
| 4     | 50    |
| 5     | 60    |
| 6     | 70    |
| 7     | 80    |
| 8     | 90    |

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* Linear Regression

## Project Workflow

1. Load the dataset.
2. Separate features and labels.
3. Split the dataset into training and testing sets.
4. Train the Linear Regression model.
5. Generate predictions.
6. Evaluate model performance using evaluation metrics.
7. Analyze and interpret the results.

## Model Training

The model is trained using the Linear Regression algorithm provided by Scikit-Learn.

```python
model = LinearRegression()
model.fit(X_train, y_train)
```

The `fit()` method allows the model to learn the relationship between study hours and exam scores.

## Prediction

After training, the model can predict scores for new study-hour values.

Example:

```python
prediction = model.predict([[9]])
```

Predicted Output:

```text
Predicted Score for 9 study hours: 100
```

## Model Evaluation

The model performance is evaluated using:

* Mean Absolute Error (MAE)
* R² Score

These metrics help determine how accurately the model predicts student scores.

## Results

The model successfully learned the relationship between study hours and exam scores. Predictions increased as study hours increased, showing a positive linear relationship between the variables.

## Learning Outcomes

Through this project, the following Machine Learning concepts were learned:

* Machine Learning Fundamentals
* Datasets
* Features and Labels
* Data Preprocessing
* Supervised Learning
* Model Training
* Predictions
* Model Evaluation

## Conclusion

This project demonstrates a basic Machine Learning workflow using Linear Regression. It shows how historical data can be used to train a model and generate predictions. The project provides a strong foundation for learning more advanced Machine Learning techniques and real-world applications.
