# Breast Cancer Classification

## Overview

This repository contains a machine learning project focused on breast cancer classification. The primary goal of this project is to build a classification model that can effectively classify breast cancer cases into two classes: **Class 2** and **Class 4 **.

## Table of Contents

- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
## Dataset

The dataset used for training and testing the model is available in the file Data.csv, which contains the following columns:
- Sample code number
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses
- Class



## Models

Experimented with several classification models, including:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine (SVM)
- Kernel SVM
- Naive Bayes
- Decision Tree
- Random Forest

Based on the accuracy score of the confusion matrix, the Decision Tree model was selected as the best-performing model for this dataset.

## Results

Here are the accuracy scores for each classification model on the breast cancer dataset:

- Logistic Regression: 0.9474
- K-Nearest Neighbors: 0.9474
- Support Vector Machine (SVM): 0.9415
- Kernel SVM: 0.9532
- Naive Bayes: 0.9415
- Decision Tree: 0.9591
- Random Forest: 0.9474

The Decision Tree model achieved the highest accuracy score of 0.9591 and was selected as the best model for classifying breast cancer cases into Class 2  and Class 4 .

