# Comparative Study of Classification Models Using the Iris Dataset

## Overview
This project implements and compares four supervised machine learning classification algorithms using the Iris Flower Classification dataset.

## Objectives
- Implement SVM, Decision Tree, K-Nearest Neighbours (KNN), and Gaussian Naïve Bayes.
- Evaluate the models using accuracy, macro precision, macro recall, macro F1-score, and log loss.
- Compare model performance using classification reports, confusion matrices, and visualizations.

## Dataset
The Iris dataset is obtained from `scikit-learn`. It contains 150 samples, four numerical features, and three classes: Setosa, Versicolor, and Virginica.

## Algorithms Used
1. Support Vector Machine (SVM) with an RBF kernel
2. Decision Tree Classifier
3. K-Nearest Neighbours (KNN), with k = 5
4. Gaussian Naïve Bayes

## Tools and Libraries
- Python
- Google Colab
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Seaborn

## Results

| Model | Accuracy | Macro F1-score | Log Loss |
|---|---:|---:|---:|
| SVM | 96.67% | 0.9666 | 0.1125 |
| Decision Tree | 93.33% | 0.9333 | 2.4029 |
| KNN | 93.33% | 0.9327 | 0.1196 |
| Gaussian Naïve Bayes | 96.67% | 0.9666 | 0.1420 |

SVM achieved the lowest log loss and tied with Gaussian Naïve Bayes for the highest accuracy in this experiment.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells in sequence.
3. Review the evaluation metrics, classification reports, comparison graphs, and confusion matrices.

## Conclusion
SVM and Gaussian Naïve Bayes achieved the highest accuracy on the selected test split. SVM had the lowest log loss among the four models. The results illustrate the importance of comparing multiple evaluation metrics when selecting a classification model.

## Author
Aparna Dongale

## Academic Context
MDM AIML Practical Assignment 4
