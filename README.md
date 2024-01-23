# K-Nearest Neighbors (KNN) for Patient Data Classification

## Project Overview

This project implements the K-Nearest Neighbors (KNN) algorithm to classify patients based on their age and a specific code. The goal is to predict a patient's gender given these two features.

## Key Steps:

1. **Data Loading and Exploration:**
   - Imports data from a CSV file named "data_pasien.csv"
   - Visualizes the distribution of data points based on age, code, and gender

2. **Data Preparation:**
   - Splits data into features (age and code) and target variable (gender)
   - Binarizes the categorical gender variable using LabelBinarizer

3. **Model Building:**
   - Creates a KNN classifier with k=3 neighbors
   - Trains the model on the training data

4. **Prediction:**
   - Demonstrates prediction for a new patient with specified age and code
   - Visualizes the new patient's position relative to the training data

5. **Evaluation:**
   - Evaluates model performance on a test set using accuracy, recall, F1-score, and Matthews correlation coefficient (MCC)

## Repository Structure:

- `knn_fix.ipynb` (Jupyter Notebook containing the code)
- `data_pasien.csv` (dataset, if available)
- `README.md` (this file)

## To run the code:

1. Download or clone this repository.
2. Ensure you have Python and the required libraries installed (pandas, numpy, matplotlib, sklearn, scipy).
3. Open the `knn_fix.ipynb` notebook in Jupyter Notebook or a similar environment.
4. Execute the cells in the notebook sequentially.

## Further Exploration:

- Experiment with different values of k to potentially improve model performance.
- Explore feature engineering techniques to create more informative features.
- Consider using different distance metrics for the KNN algorithm.
- Evaluate the model's performance on different datasets.
