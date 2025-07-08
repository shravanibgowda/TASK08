Breast Cancer Diagnosis using Random Forest

This project uses a Random Forest Classifier to predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset. The dataset is provided by scikit-learn and contains features computed from digitized images of fine needle aspirate (FNA) of breast mass.

Objective

To implement a machine learning classification model (Random Forest) that can accurately diagnose breast cancer based on various cell features.

Files

- `task 8.ipynb`: Jupyter notebook containing code for data preprocessing, model training, evaluation, and visualization.

Dataset

- Source: `sklearn.datasets.load_breast_cancer()`
- Features: 30 numeric features like mean radius, texture, perimeter, area, etc.
- Target: Diagnosis (`0 = malignant`, `1 = benign`)

Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

Steps Covered

1. Data loading and exploration
2. Feature selection
3. Train-test split
4. Model training using Random Forest Classifier
5. Accuracy evaluation
6. Confusion matrix and classification report
7. Visualization of feature importance

Results

The model achieved high accuracy in detecting malignant vs. benign tumors using random forest classification, showing promise for medical diagnostics support.

Requirements

Install required libraries using:

```bash
pip install pandas scikit-learn matplotlib seaborn
