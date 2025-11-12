# Iris Flower Classification

## Project Overview

This project demonstrates a complete, foundational machine learning workflow using the classic Iris dataset. The primary goal is to build a model that accurately classifies Iris flower species (Setosa, Versicolor, and Virginica) based on four features: sepal length, sepal width, petal length, and petal width.

This repository showcases the essential steps of a data science project, from data cleaning and preparation to model training and evaluation.

## Process

1.  **Data Loading:** The dataset (`Iris.csv`) was loaded into a Pandas DataFrame.
2.  **Data Inspection & Cleaning:** Performed an initial analysis of the data types and checked for null values (`.info()`). The non-informative 'Id' column was dropped to prepare the dataset for modeling.
3.  **Model Training:** A `RandomForestClassifier` (an ensemble learning method) was successfully trained on the feature data.
4.  **Evaluation Framework:** A custom function (`get_accuracy`) was defined to calculate and compare training and testing accuracy, demonstrating a clear understanding of model validation and the importance of preventing overfitting. The project is set up to evaluate model performance using standard metrics like `accuracy_score`, `classification_report`, and `confusion_matrix`.

## Core Technologies Used

* **Python:** The core programming language used for the project.
* **Pandas:** For loading, manipulating, and cleaning the data.
* **Scikit-learn:** The primary machine learning library, used for:
    * Model implementation (`RandomForestClassifier`, `LogisticRegression`)
    * Data splitting (`train_test_split`)
    * Hyperparameter tuning (`GridSearchCV`)
    * Performance evaluation (`accuracy_score`, `classification_report`, `confusion_matrix`)
* **NumPy:** For numerical operations.
* **Seaborn & Matplotlib:** For data visualization (libraries are imported and ready for use).
