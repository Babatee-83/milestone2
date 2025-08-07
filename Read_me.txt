

PCA for Cancer Dataset Analysis

Project Description
This project demonstrates the use of Principal Component Analysis (PCA) to reduce the dimensionality of the Scikit-learn Wisconsin Breast Cancer dataset. The original 30 features are reduced to 2 principal components, which are then used to train a logistic regression model for tumor classification (malignant vs. benign).

 Files: The zip file contains two files. A python code file and the corresponding Read_me.
- milestone_2.py`: The main Python script containing the full analysis.
- README_me`: This file.

Prerequisites
You will need the following Python libraries installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install them using pip:
`pip install pandas, numpy, scikit-learn , matplotlib and seaborn respectively.

How to Run
To run the analysis, execute the Python script from your terminal:
milestone_2.py`

The script will perform the following steps:

1. Pip install scikit-learn
2. Load and standardize the cancer dataset.
3. Apply PCA to reduce the dataset to two(2) components.
4. Print the explained variance ratio.
5. Generate and display a scatter plot of the 2 principal components.
6. Train a logistic regression model on the PCA-transformed data.
6. Print the accuracy of the classification model.