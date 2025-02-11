# Cancer Prediction Using Logistic Regression
This project implements a Logistic Regression model to predict whether a tumor is malignant or benign based on various clinical features extracted from breast cancer tumors. The dataset used is the Breast Cancer Wisconsin Diagnostic Dataset available on Kaggle.

## Project Overview
-Uses Logistic Regression, a supervised classification algorithm, to diagnose breast cancer.
-Implements data preprocessing, feature selection, and model evaluation techniques.
-Performance is assessed using accuracy, precision, recall, F1-score, and ROC-AUC curve.
-Visualizes dataset features using histograms, scatter plots, and correlation matrices.

## Dataset
Source: Breast Cancer Wisconsin Dataset - [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
This dataset contains 569 instances with 30 numerical features describing the characteristics of cell nuclei.

## Key Features:
Mean radius, texture, perimeter, and area of the tumor
Compactness, symmetry, and fractal dimension
Diagnosis: M (Malignant) or B (Benign) (Target variable)

## Installation & Dependencies
To run this project, install the required dependencies:
pip install -r requirements.txt

## Running the Notebook
Open Jupyter Notebook:
-Jupyter notebook
-Run Cancer_LogisticRegression1.ipynb and Cancer_LogisticRegression2.ipynb.
-Ensure the dataset (Cancer_Data.csv) is in the same directory.

## Model Training & Evaluation
Data Preprocessing:
-Handled missing values
-Converted categorical labels (M & B) into numerical values
-Standardized feature scaling using StandardScaler

## Model Training:
Implemented Logistic Regression using sklearn
Optimized hyperparameters using GridSearchCV

## Performance Metrics:
-Accuracy: XX% (Update with actual accuracy)
-Precision, Recall, and F1-Score
-Confusion Matrix & ROC Curve Analysis

## Project Structure
Cancer_Prediction_Logistic_Regression/
│── Cancer_LogisticRegression1.ipynb
│── Cancer_LogisticRegression2.ipynb
│──Cancer prediction dataset.csv
│── requirements.txt
│── README.md
│── .gitignore

## Results & Insights
-The model accurately differentiates between malignant and benign tumors.
-High recall ensures minimal false negatives, which is crucial for cancer detection.
-Feature importance analysis highlights radius_worst, texture_mean, and concavity_worst as key indicators.

## Contributing
Please feel free to fork the repository, open an issue, or submit a pull request if you'd like to improve the project.

## Contact
For any inquiries, reach out via GitHub Issues or email at sweetyrao670@gmail.com.
