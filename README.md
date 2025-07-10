#Fisher's Linear Discriminant Projects – Synthetic & Iris Dataset

Overview
This repository contains two projects demonstrating the application of Fisher’s Linear Discriminant Analysis (LDA) for binary classification using both a synthetic 2D dataset and a real-world Iris dataset.
The aim is to explore class separability by projecting high-dimensional data onto a one-dimensional space using the optimal direction (v) found via LDA, and evaluating performance using custom classification criteria.

Project 1: LDA on Synthetic Gaussian Data
Class A: 50 samples from 2D Normal distribution with mean (-2, -2), std = 1
Class B: 50 samples from 2D Normal distribution with mean (2, 2), std = 2
Tasks:
Computed the Fisher discriminant direction v
Visualized both classes and projection line
Projected data onto v and defined a custom classification boundary
Classified new points: (0, 0), (0, -0.5), (0.5, 0)
Tools: Python, NumPy, Matplotlib

Project 2: LDA on Iris Dataset (Versicolor vs Virginica)
Features used: Petal Length & Petal Width
Training data: 40 randomly selected points from each class
Test data: Remaining 10 points per class
Tasks:
Computed LDA direction v for class separation
Visualized data and v
Projected data onto v and created a custom classification threshold
Classified test points and reported accuracy
Tools: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Skills Demonstrated
Fisher’s Linear Discriminant Analysis (LDA)
Dimensionality reduction for classification
Custom thresholding
Data visualization and projection
Evaluation on test data (accuracy measurement)
