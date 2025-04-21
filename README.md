# Iris-Dataset-Analysis-with-KNN

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

## Technologies Used
- Python
- NumPy
- Matplotlib
- Scikit-learn (for KNN implementation)
- Jupyter Notebook
