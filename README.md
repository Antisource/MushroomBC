# Binary Classification Web App

This is a web application built using Streamlit for binary classification of mushroom types as edible or poisonous. The user can choose from different classifiers (Support Vector Machine, Logistic Regression, or Random Forest) and adjust hyperparameters to classify mushrooms based on their features.

## Usage

To run the web application, execute the following command:

```bash
streamlit run app.py
```

## Features
- Classifier Selection: Choose from Support Vector Machine (SVM), Logistic Regression, or Random Forest.
- Model Hyperparameters: Adjust hyperparameters such as regularization parameter (C), kernel type, maximum number of iterations, number of trees in the forest, and maximum depth of the tree.
- Metrics Visualization: Visualize performance metrics including Confusion Matrix, ROC Curve, and Precision-Recall Curve.
- Raw Data Display: Option to display the raw mushroom dataset used for classification.

## Dependencies
Ensure you have the following dependencies installed:
- streamlit
- pandas
- numpy
- scikit-learn

You can install them using pip:

```bash
pip install streamlit pandas numpy scikit-learn
```



