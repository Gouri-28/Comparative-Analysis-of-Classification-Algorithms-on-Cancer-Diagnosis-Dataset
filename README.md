# Comparative-Analysis-of-Classification-Algorithms-on-Cancer-Diagnosis-Dataset

# Project Overview
This project aims to identify the most accurate machine learning model for classifying cancer data. The focus is on distinguishing between benign and malignant tumors using various classification algorithms.



 # Dataset
The dataset used is Cancer_Data.csv, containing patient tumor characteristics.

Preprocessing steps include label encoding, feature scaling, and train-test splitting.

 # Algorithms Used
The following classification algorithms are implemented:

Logistic Regression (LR)

Naïve Bayes (NB)

K-Nearest Neighbors (KNN)

Decision Tree (DT)

Random Forest (RF)

K-Means Clustering (unsupervised)

# Performance Evaluation
The models are evaluated using these classification metrics:

Accuracy

Precision

Recall

F1-Score

The results are presented in a tabular format to compare model performance.

# Installation & Requirements
To run this project, install the necessary dependencies:

sh
Copy
Edit
pip install pandas scikit-learn matplotlib seaborn
Usage
Load the dataset using Pandas.

Preprocess the data: handle missing values, normalize, and split into train-test sets.

Train models using different classification algorithms.

Evaluate model performance using classification metrics.

Compare results and determine the best-performing model.

# Run the Jupyter Notebook:

sh
Copy
Edit
jupyter notebook Comparitive_analysis_of_algo.ipynb
# Results & Conclusion
Based on the analysis, Naïve Bayes was selected as the best-performing model due to its high F1 Score, making it highly effective in distinguishing between benign and malignant tumors. Its balance between precision and recall ensures reliable diagnostic predictions.

# Contributing
If you'd like to contribute or improve the project, feel free to fork the repository and submit a pull request.
