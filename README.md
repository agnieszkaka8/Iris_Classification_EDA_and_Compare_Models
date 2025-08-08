# Iris Data Analysis

## 📌 Project Overview
This project presents an analysis of the classic Iris dataset, which contains morphological measurements of three iris flower species (Iris setosa, Iris versicolor, Iris virginica).
The goal is to explore the dataset, visualize feature distributions, and build a simple classification model.

## 📂 Repository Structure
.
├── README.md                # This file
├── iris_analysis.ipynb      # Jupyter Notebook with the analysis
├── requirements.txt         # List of required packages
└── data/
    └── Iris.csv              # Dataset file (optional)

## 📊 Dataset Description
The Iris dataset contains 150 records and 5 columns:
sepal_length – sepal length (cm)
sepal_width – sepal width (cm)
petal_length – petal length (cm)
petal_width – petal width (cm)
species – iris species

## 🔍 Analysis Steps
Load the dataset
Basic exploration – shape, data types, missing values
Data visualization – box plots, histograms, scatter plots
Build a classification model – Logistic Regression, KNN, Decision Tree, Random Forest
Model evaluation – accuracy, F1-score

## 🛠 Requirements
The requirements.txt file may include:
pandas
numpy
matplotlib
seaborn
scikit-learn
Install the dependencies:
pip install -r requirements.txt

## 🚀 Running the Analysis
To run the analysis:
jupyter notebook iris_analysis.ipynb
Then execute all cells in the notebook.

## 📚 Sources
Dataset: [Iris Species on Kaggle by UCI MACHINE LEARNING](https://www.kaggle.com/datasets/uciml/iris)
