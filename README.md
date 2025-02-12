Overview

This project implements a Rock vs Mine Detection model using Logistic Regression. The goal is to classify whether an object detected by sonar is a rock or a mine based on the features extracted from sonar signals.

Dataset

The dataset used for this project is the Sonar dataset, which contains 208 samples with 60 feature columns. Each sample represents sonar readings bounced off either a rock or a mine, with corresponding labels:

R (Rock)

M (Mine)

You can download the dataset from the UCI Machine Learning Repository: Sonar Dataset also Uploaded here

Technologies Used

Python

NumPy

Pandas

Scikit-learn



Model Training & Evaluation

Load the dataset and preprocess the data.

Split the data into training and testing sets.

Train the Logistic Regression model.

Evaluate the model using accuracy, precision, recall, and confusion matrix.



Results

Model accuracy: ~72-83%

Confusion Matrix & Classification Report will be displayed after execution.

Contribution

Feel free to contribute by opening an issue or submitting a pull request.
