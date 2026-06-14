# Laryngeal Image Classification with Uncertainty Quantification

## Overview
This notebook performs classification of laryngeal images using Support Vector Machines (SVM). It includes data loading, preprocessing, training, evaluation, hyperparameter tuning using grid search, and uncertainty quantification via bootstrapping and probability visualizations.

## Features
- Loading and preprocessing of laryngeal images from multiple dataset folds
- Visualization of sample images with labels
- Training and evaluation of SVM classifiers
- Model performance assessment with accuracy, precision, recall, F1-score, classification reports, and confusion matrices
- Hyperparameter tuning using GridSearchCV for optimal SVM parameters
- Uncertainty quantification using bootstrapped accuracy confidence intervals
- Visualization of class prediction probabilities for uncertainty analysis

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- Libraries: OpenCV, NumPy, scikit-learn, Matplotlib, Seaborn, pandas

## How to Use
1. Mount Google Drive in Colab to access the laryngeal dataset archive.
2. Extract the dataset and load images from the folders.
3. Run preprocessing steps to resize and normalize images.
4. Train an initial SVM model and evaluate its performance.
5. Tune hyperparameters using grid search to improve model accuracy.
6. Perform uncertainty quantification with bootstrapping and visualize prediction probabilities.
7. Analyze results with classification reports and confusion matrices.

## Status
This notebook is organized and formatted for clear presentation and reproducibility on GitHub.