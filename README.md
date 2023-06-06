# Breast Cancer Wisconsin (Diagnostic) Dataset

This repository contains a Jupyter Notebook that demonstrates the process of building a machine learning model using the Breast Cancer Wisconsin (Diagnostic) dataset. The dataset consists of features computed from digitized images of breast mass samples, which are used to predict whether a tumor is benign or malignant.

## Dataset Information

- Dataset: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- Attribute Information: Refer to the dataset link for detailed attribute descriptions.
- Target Variable: Diagnosis (0: Benign, 1: Malignant)

## Files

- `BinuDas_model_v1.ipynb`: Jupyter Notebook containing the machine learning model implementation.
- `BinuDas_model_v2.ipynb`: Jupyter Notebook containing the machine learning model implementation.(in another Branch)
- `wdbc.data`: Dataset or can be accessed from (https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))
- `README.md`: Documentation describing the project.

## Requirements

To run the notebook, you need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

## Instructions

1. Clone the repository or download the `ipynb` file.

2. Install the necessary dependencies if you haven't already.

3. Open the Jupyter Notebook .

4. Run the cells in the notebook to execute the code step by step.

## Results

The notebook covers the following steps:

1. Importing the required libraries.
2. Loading and exploring the dataset.
3. Preprocessing the data by removing unnecessary columns and converting the target variable to binary labels.
4. Splitting the dataset into training and testing sets.
6. Training an SVM model on the training data.
7. Making predictions on the test set.
8. Evaluating the model's accuracy and generating a classification report.

The results will be displayed in the notebook, including the accuracy of the model and the classification report.



