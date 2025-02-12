# Rock vs Mine Detection using Logistic Regression

## Overview
This project implements a **Rock vs Mine Detection** model using **Logistic Regression**. The goal is to classify whether an object detected by sonar is a **rock** or a **mine** based on the features extracted from sonar signals.

## Dataset
The dataset used for this project is the **Sonar dataset**, which contains 208 samples with 60 feature columns. Each sample represents sonar readings bounced off either a rock or a mine, with corresponding labels:
- **R** (Rock)
- **M** (Mine)

You can download the dataset from the **UCI Machine Learning Repository**: [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar%2C+Mines+vs.+Rocks%29). The dataset is also uploaded here.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

## Model Training & Evaluation
1. Load the dataset and preprocess the data.
2. Split the data into training and testing sets.
3. Train the Logistic Regression model.
4. Evaluate the model using accuracy, precision, recall, and confusion matrix.

## Results
- Model accuracy: ~72-83%
- Confusion Matrix & Classification Report will be displayed after execution.

## Contribution
Feel free to contribute by opening an issue or submitting a pull request.
