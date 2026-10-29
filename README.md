# Breast Cancer Classification — Machine Learning Model Comparison

## Project Overview
This project uses Python and Scikit-learn to train, evaluate, and compare machine learning classification models using the Breast Cancer Wisconsin dataset.

The goal is to classify tumor samples as malignant or benign and evaluate how different algorithms perform.

## Technologies Used
- Python
- Scikit-learn
- NumPy
- Matplotlib
- Jupyter Notebook

## Machine Learning Models
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Classifier (SVC)

## Project Features
- Loaded and explored a dataset containing 569 samples and 30 features.
- Split the dataset into training (70%) and testing (30%) sets.
- Trained and evaluated a Gaussian Naive Bayes classifier.
- Generated a classification report and confusion matrix.
- Applied 10-fold cross-validation to evaluate model performance.
- Used Scikit-learn pipelines and feature scaling where appropriate.
- Compared four classification algorithms.
- Visualized model performance using Matplotlib.

## Results

The following results represent mean accuracy from 10-fold cross-validation:

| Model | Mean CV Accuracy |
|---|---:|
| Gaussian Naive Bayes | 93.85% |
| K-Nearest Neighbors | 96.83% |
| Logistic Regression | 97.89% |
| Support Vector Classifier | 97.89% |

Logistic Regression and SVC achieved the highest mean cross-validation accuracy at **97.89%**.

Gaussian Naive Bayes achieved approximately **95% accuracy** on the held-out test set.

## How to View or Run
1. Open `Homework4_Breast_Cancer.ipynb` on GitHub to view the Python code and saved results.
2. To execute the notebook, open it in Jupyter Notebook or Google Colab.
3. Ensure NumPy, Matplotlib, and Scikit-learn are installed.
4. Run the notebook cells in order.

## Project Background
This project was completed as part of my Computer Science coursework. I independently implemented the assignment using course materials and textbook references.

**Note:** This is an educational machine learning project, not a clinically validated diagnostic tool.
