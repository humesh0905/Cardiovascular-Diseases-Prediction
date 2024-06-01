# Team Members:
1) Humesh Reddy Venkatapuram
2) Mohith Krishna Reddy Donthireddy
3) Jaya Jwalitha Nagulla

Codebase Organization:

final_code_phase_5.py: This script contains the complete analysis for the Heart Disease Prediction using various statistical visualizations and data preprocessing. 
It includes:
- data visualization
- data splitting
- data normalization
- using the base classifiers models
- printing ROC curves for all models
- printing confusion matrix for all models
- Hyperparameter Tuning with GridSearchCV for Various Classifiers
- Including the Stacking Classifier and ROC Curves
- evaluating all models with varying parameter sets
- K-Fold Cross-Validation for Multiple Classifiers and plot

How to Run the Code:

Ensure that Python 3.x is installed on your system. Install the required libraries using the command: pip install pandas matplotlib seaborn.
Run the script from the command line or any Python IDE: python final_code_phase_5.py

3. Required Libraries and Versions:

pandas: For data manipulation and analysis.
matplotlib: For creating static, interactive, and animated visualizations in Python.
seaborn: For making statistical graphics in Python. It is based on matplotlib and integrates closely with pandas data structures.

Ensure all libraries are up-to-date as this script uses features from recent releases.

4. Dataset Information:

Dataset 1: 
Processed Cleveland Dataset: This dataset is the processed dataset of the original Cleveland dataset which is the only on that has been used by ML Researchers till date. The original dataset has 76 attributes but all published requirements refer to using a subset of 14 of them. The processed Cleveland data contains 303 rows and 14 columns.

Dataset 2:
Heart Disease Dataset: This dataset contains 1025 records with features such as age, sex, chest pain type(cp), resting blood pressure (trestbps), cholesterol levels (chol), fasting blood sugar (fbs), resting electrocardiographic results (restecg), maximum heart rate achieved (thalach), exercise-induced angina (exang), ST depression induced by exercise relative to rest (oldpeak), slope of the peak exercise ST segment (slope), number of major vessels colored by fluoroscopy (ca), thalassemia (thal), and the target variable indicating the presence of heart disease

Dataset 3:
Heart Failure Prediction Dataset: There are 918 records in the dataset. They have mostly similar features as Heart disease dataset but some have slight
differences in names and additional categories, like types of chest pain and results from resting electrocardiograms results.

Links For the datasets:

Heart Disease Dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
Heart Failure Prediction:https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
Cleveland Dataset: https://archive.ics.uci.edu/dataset/45/heart+disease
