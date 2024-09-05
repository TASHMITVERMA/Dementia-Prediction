# Dementia Prediction

This project aims to predict dementia using machine learning algorithms such as Random Forest, Support Vector Machine (SVM), and K-Means clustering.

## Table of Contents
- Introduction
- Installation
- Usage
- Algorithms
- Results
- Contributing
- License

## Introduction
Dementia is a general term for a decline in cognitive function severe enough to interfere with daily life. This project leverages machine learning techniques to predict the likelihood of dementia in patients based on various features.

## Installation
To get started, clone the repository and install the required dependencies:

bash
git clone https://github.com/yourusername/Dementia-Prediction.git
cd Dementia-Prediction
pip install -r requirements.txt

python main.py
Algorithms
The following machine learning algorithms were used in this project:

Random Forest: An ensemble learning method that operates by constructing multiple decision trees.
Support Vector Machine (SVM): A supervised learning model that analyzes data for classification and regression analysis.
K-Means Clustering: An unsupervised learning algorithm used for clustering data into k distinct clusters.

# Importing the tabulate library
from tabulate import tabulate

# Data for the table
data = [
    ["Random Forest", 0.90, 0.84, 0.83, 0.83],
    ["SVM", 0.86, 0.81, 0.80, 0.80],
    ["K-Means", 0.78, 0.77, 0.76, 0.76]
]

# Column headers
headers = ["Algorithm", "Accuracy", "Precision", "Recall", "F1-Score"]

# Printing the table
print(tabulate(data, headers, tablefmt="grid"))


Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
