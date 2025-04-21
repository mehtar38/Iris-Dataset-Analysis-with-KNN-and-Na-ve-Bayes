# Iris-Dataset-Analysis-with-KNN-and-Naive-Bayes

This project explores the Iris dataset and implements classification techniques, including K-Nearest Neighbors (KNN) and Naïve Bayes classifiers.

## Project Overview
The project consists of three main problems:
1. **Exploratory Data Analysis (EDA) on the Iris Dataset**
2. **KNN Predictions on CIFAR-10 Dataset**
3. **Naïve Bayes Classifiers for Email Classification**

## Problem 1: Iris Dataset EDA
### Tasks Performed:
1. **Dataset Shape Analysis**  
   - Extracted the number of features and data points using `X.shape`.
2. **Feature Histograms**  
   - Plotted histograms for each feature using `plt.hist`.
3. **Feature Statistics**  
   - Computed mean and standard deviation for each feature using `np.mean` and `np.std`.
4. **Feature Pair Scatterplots**  
   - Generated scatterplots for feature pairs (1,2), (1,3), and (1,4), colored by target class.

## Problem 2: KNN Predictions (CIFAR-10)
### Tasks Performed:
- Implemented K-Nearest Neighbors (KNN) for image classification on the CIFAR-10 dataset.
- Dataset sourced from [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html).
- Filled in the provided Jupyter notebook with KNN classification logic.

## Problem 3: Naïve Bayes Classifiers (Email Classification)
### Tasks Performed:
1. **Probability Computations**  
   - Calculated class probability `p(y)` and feature probabilities `p(xi|y)` for the Naïve Bayes classifier.
2. **Class Predictions**  
   - Predicted class for `x = (0 0 0 0 0)` and `x = (1 1 0 1 0)`.
3. **Posterior Probability Calculation**  
   - Computed `P(y = +1 | x = (1 1 0 1 0))`.
4. **Joint vs. Naïve Bayes Analysis**  
   - Discussed why a joint Bayes classifier is unsuitable for this dataset.
5. **Model Retraining Scenario**  
   - Analyzed retraining implications if feature `x1` (author known) is unavailable.

## Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn (for KNN implementation)
- Jupyter Notebook
