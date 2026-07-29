# Breast-Cancer-Detection-Model
<img width="1920" height="1281" alt="image" src="https://github.com/user-attachments/assets/644bc6f9-5464-466c-bbec-fa237293d07a" />

## Overview
This repository contains a machine learning project focused on breast cancer (BC) detection. The data is derived from the **Breast Cancer Wisconsin (Diagnostic) Data Set** and includes diagnoses and cell nuclei characteristics extracted from digitized images of fine needle aspirate (FNA) samples, such as radius, texture, area, and more. The primary objective is to build a predictive model that accurately classifies breast tumors as malignant or benign. By supporting earlier and more accurate diagnosis, this model may help improve prognosis and survival chances. 

## Problem
In this project, we analyze a dataset containing cell nuclei characteristics from digitized images of breast mass samples, along with their corresponding diagnoses (M = malignant, B = benign). Our goal is to develop a predictive model capable of accurately classifying tumors as malignant or benign. Given the severe consequences of misclassifying a malignant tumor as benign (i.e. a false negative), our primary emphasis is on maximizing the model's ability to correctly identify malignant cases while maintaining strong overall predictive performance.

## Objectives
The objectives of the project are as follows:
1. **Data Understanding**: Familiarize ourselves with the dataset and its features.
2. **Data Preprocessing**: Prepare the data for future machine learning tasks.
* Remove irrelevant features
* Address missing values
3. **Exploratory Data Analysis (EDA)**: Discover patterns, trends, and relationships between different variables.
* Univariate Analysis
* Multivariate Analysis
4. **Model Building**: Develop and refine the prediction models.
* Implement and tune models including Logistic Regression, Decision Tree, and Random Forest
5. **Evaluate and Compare Model Performances**: Utilize a Confusion Matrix to test each models' accuracy.

## Dataset
The dataset comprises various cell nuclei metrics related to BC. The features of the dataset can be found [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

## File Descriptions
* Breast Cancer Detection.ipynb : Google Colab code containing all the data pre-processing and exploration, visualization, modeling, and evaluation.
* README.md : This file, providing the overview of the project. 
