Breast Cancer Wisconsin (Diagnostic) Dataset - Machine Learning Models

Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is publicly available in the UCI Machine Learning Repository. 
The dataset contains 569 instances of malignant and benign tumor samples, each described by 30 features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

Installation
Before running the notebooks, ensure you have the following Python packages installed:
ucimlrepo
pandas
scikit-learn
matplotlib
seaborn

1. Random Forest Classifier
This notebook demonstrates the process of building a Random Forest classifier for the dataset. It includes steps for data exploration, preprocessing, model training, and evaluation.
Key Steps:
     Data Loading and Exploration: Load the dataset using ucimlrepo, explore the features, and visualize the target distribution.
     Data Preprocessing: Handle missing values, split the data into training and testing sets, and standardize the features.
     Model Building and Training: Train a Random Forest classifier on the training set.
     Model Evaluation: Evaluate the model's performance using a confusion matrix, classification report, and accuracy score.

2. Support Vector Machine (SVM) Classifier
This notebook demonstrates the process of building an SVM classifier for the dataset. It includes similar steps to the Random Forest notebook but uses an SVM with a linear kernel.

Key Steps:
    Data Loading and Exploration: Load the dataset using ucimlrepo, explore the features, and visualize the target distribution.
    Data Preprocessing: Handle missing values, split the data into training and testing sets, and standardize the features.
    Model Building and Training: Train an SVM classifier with a linear kernel on the training set.
    Model Evaluation: Evaluate the model's performance using a confusion matrix, classification report, and accuracy score.

Both notebooks include detailed results of the model evaluation. The Random Forest and SVM classifiers are compared based on their accuracy, precision, recall, and F1-score to 
determine the best performing model for this dataset.
