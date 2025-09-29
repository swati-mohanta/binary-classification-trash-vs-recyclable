# Binary Classification

## Overview
This project implements binary classification on a dataset using three feature extraction cases:  
1. HOG  
2. LBP  
3. HOG + LBP  

For each case, we train multiple classifiers:
- SVM
- KNN
- Random Forest
- Naive Bayes
- XGBoost

We compare the **accuracies and classification reports** for all models in each case.

## Dataset
- The dataset is in `garbage.zip`
- Description: Contains two folders inside: `trash` and `recyclable` with images
- Size: 240 images total (120 each)
- To use, download and unzip `garbage.zip`

## Steps
1. Feature extraction (HOG, LBP, HOG+LBP)
2. Train classifiers (SVM, KNN, RF, NB, XGB)
3. Evaluate models (accuracy, classification report)
4. Compare results across cases
