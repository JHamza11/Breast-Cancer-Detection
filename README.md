# Breast-Cancer-Detection

## Problem Statement
Breast cancer is the most commonly diagnosed cancer and second-leading cancer death among women in the U.S. with 1 in 8 expected to develop it in her lifetime. Its overall death rate has steadily decreased by 1% per year from 2013 to 2018 which has thought to be from treatment advances and earlier detection.

Since earlier detection is thought to be a cause in decreasing breast cancer deaths, the predictive model built in this notebook serves as an attempt to fill this purpose as a classification problem. Preliminary analysis is done to make conclusions based on the data and select the best features for predictive accuracy.

## Description
Pulled from the [University of California at Irvine Machine Learning Repository’s Wisconsin Breast Cancer Database](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)), cells were measured through a digitized image of a fine needle aspirate (FNA), a biopsy procedure where a sample is collected through inserting a needle. Because all samples contained more than one cell, their physical characteristics were averaged with respect to the amount of cells in the sample.

Diagnosis is a categorical variable defined in the data as:
  * B - Benign (non-cancerous)
  * M - Malignant (cancerous)

For classification purposes, the data will be formatted such that 0 represents benign and 1 represents malignant.

Thus, the goal of this project is to use machine learning classification methods to predict which samples are most likely to be benign or malignant.

## Methods
* Machine Learning
* Data Analysis and Visualization
  * Unimodal
  * Multimodal
* Inferential Statistics
* Predictive Classification (Support Vector Machine)

## Technologies/Tools Used
* Python
* NumPy, pandas
* scikit-Learn
* Jupyter
* Google Colab (not necessary, however if not used then dataset must be referenced locally with pd.read_csv())
