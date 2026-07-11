# Bagging Ensemble Learning for Classification

## Project Overview

This project explores the effectiveness of **Bagging (Bootstrap Aggregating)** as an ensemble learning technique by comparing its performance against individual machine learning classifiers.

Three base learners were evaluated:

- Decision Tree
- Logistic Regression
- Support Vector Machine (SVM)

Each model was trained individually and then evaluated using Bagging to analyze improvements in predictive performance.

---

## Problem Statement

Individual machine learning models may suffer from overfitting or unstable predictions depending on the dataset.

This project investigates whether applying **Bagging Ensemble Learning** can improve classification performance, reduce variance, and increase model stability.

---

## Technologies Used

- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Machine Learning Pipeline

✔ Data Loading

✔ Data Preprocessing

✔ Model Training

✔ Bagging Ensemble Construction

✔ K-Fold Cross Validation

✔ Model Evaluation

✔ Performance Comparison

---

## Models Evaluated

### Individual Models

- Decision Tree
- Logistic Regression
- Support Vector Machine (SVM)

### Bagging Ensemble Models

- Bagging + Decision Tree
- Bagging + Logistic Regression
- Bagging + SVM

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Confusion Matrix
- K-Fold Cross Validation
- Average Cross-Validation Accuracy

---

## Results

The Bagging Decision Tree model achieved the strongest overall performance with an average K-Fold accuracy of approximately **97.47%**, outperforming the other evaluated models.

Bagging with Logistic Regression produced moderate performance, while Bagging with SVM resulted in significantly lower classification accuracy on the selected dataset.

---

## Visualizations

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

---

### K-Fold Cross Validation Accuracy

![K-Fold Accuracy](kfold_accuracy.png)

---

## Repository Files

- `bagging-ensemble-classification.ipynb`
- `README.md`
- `confusion_matrix.png`
- `kfold_accuracy.png`

---

## Future Improvements

- Perform hyperparameter tuning using GridSearchCV
- Evaluate Random Forest and AdaBoost ensembles
- Test on larger and more diverse datasets
- Deploy the best-performing model as a web application
