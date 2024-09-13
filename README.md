# ML-Classification-of-Sloan-Digital-Sky-Survey
ML Classification of Sloan Digital Sky Survey


# Machine Learning Classification of Celestial Objects in the Sloan Digital Sky Survey (SDSS) Dataset

Hello, I am **Khaled Ashraf**. I am an AI Engineer with a focus on machine learning and deep learning. In this project, I have worked on analyzing the Sloan Digital Sky Survey (SDSS) dataset, which is a fascinating collection of astronomical data.

## Overview

This project focuses on applying machine learning techniques to classify celestial objects in the Sloan Digital Sky Survey (SDSS) dataset. The dataset includes classifications of astronomical objects into three categories: stars, galaxies, and quasars. The goal of this project is to build and evaluate a classification model to distinguish between these categories effectively.

## Dataset

The SDSS dataset is comprised of several features that describe the characteristics of celestial objects. Each object is labeled as one of the following classes:
- **Star**: A luminous sphere of plasma held together by its own gravity.
- **Galaxy**: A massive, gravitationally bound system of stars, stellar remnants, interstellar gas, dust, and dark matter.
- **Quasar**: A highly energetic and distant active galactic nucleus with an extremely bright center.

## Objective

The objective of this project is to build and evaluate a machine learning classification model to accurately distinguish between stars, galaxies, and quasars based on their features. The project involves the following key steps:

1. **Data Preprocessing**:
   - **Data Cleaning**: Handle missing values and any inconsistencies in the dataset.
   - **Outlier Removal**: Identify and remove outliers using the Interquartile Range (IQR) method to improve model accuracy.
   - **Normalization**: Scale the data to ensure all features contribute equally to the model's performance.

2. **Model Training and Evaluation**:
   - **Train-Test Split**: Split the dataset into training and testing sets.
   - **Model Selection**: Use a Decision Tree Classifier, tuned with GridSearchCV to find the best hyperparameters.
   - **Evaluation**: Assess model performance using accuracy and confusion matrix.

## Steps Performed

1. **Data Preprocessing**:
   - **Normalization**: Applied `Normalizer` to scale the feature values, ensuring that each feature's contribution to the model is balanced.
   - **Outlier Removal**: Removed outliers using the Interquartile Range (IQR) method to clean the data.

2. **Model Training**:
   - **Model Definition**: Defined and trained a `DecisionTreeClassifier` using the optimal hyperparameters found through GridSearchCV.
   - **Hyperparameter Tuning**: Optimized the model's hyperparameters such as `criterion`, `max_depth`, `min_samples_split`, and `min_samples_leaf`.

3. **Model Evaluation**:
   - **Accuracy Calculation**: Evaluated the model's performance on the test set to determine its accuracy.
   - **Confusion Matrix**: Generated a confusion matrix to visualize the performance of the classification model and identify any misclassifications.

## Results

The trained model achieved an accuracy of 98% on the test set. The confusion matrix provided insights into the distribution of true and predicted classes, helping to understand the model's performance in more detail.

## Conclusion

The analysis demonstrated the capability of the Decision Tree Classifier in classifying celestial objects into their respective categories. The model can be further refined by exploring additional features, advanced models, and tuning techniques.

## Author

This project was conducted by **Khaled Ashraf**, an AI Engineer with a focus on machine learning and deep learning. Khaled is dedicated to leveraging data-driven insights to solve complex problems and advance the field of artificial intelligence.

---
