# hyper-launch-project1
# Iris Flower Prediction Application

This project is a simple, interactive data analysis application built using Python. It uses machine learning to predict the species of iris flowers based on petal and sepal measurements. The application includes data preprocessing, visualization, model building, and evaluation steps.

---

## Features:

* Reads and processes the Iris dataset (CSV file)
* Handles missing values and data types
* Performs univariate and bivariate analysis
* Trains a Random Forest Classifier to predict iris species
* Visualizes results with Matplotlib and Seaborn
* Offers a command-line interface (CLI) for user interaction

---

## Dataset Used:
* **source link**:https://www.kaggle.com/datasets/uciml/iris?resource=download
* **Title:** Iris Dataset
* **Source:** https://www.kaggle.com/datasets/uciml/iris
* **File Format:** CSV

**Dataset Attributes:**
* `sepal length (cm)`
* `sepal width (cm)`
* `petal length (cm)`
* `petal width (cm)`
* `species`

**Target Variable:** `species`

---

## Technologies Used:

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## How to Run:

1. Clone the repository or upload the `.ipynb` file to Google Colab.
2. Upload the dataset (CSV file) to your Colab environment.
3. Run the cells step-by-step to:
   * Load and clean the data
   * Visualize the dataset
   * Train a classification model
   * Evaluate model performance
   * Use the CLI to make predictions interactively

---

## Model Used:

Random Forest Classifier

**Evaluation Metrics:**
* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Visualizations:

* Pairplot of all features
* Correlation heatmap
* Countplot of species distribution
* Confusion matrix heatmap
* Feature importance bar chart

---

## User Interaction:

A simple CLI allows users to:
* View summary statistics
* Explore different visualizations
* Input sepal and petal measurements for species prediction
* View model evaluation metrics

---

## Project Objective:

To develop a simple machine learning pipeline that predicts the species of iris flowers and provides useful insights through data visualizations.
