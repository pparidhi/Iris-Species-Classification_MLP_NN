# Iris-Species-Classification_MLP_NN

## Overview

This project involves the classification of iris species based on various properties of the flowers. The dataset includes three iris species—setosa, versicolor, and virginica—with 50 samples each. The properties considered are Sepal Length, Sepal Width, Petal Length, and Petal Width. The primary objective is to assess the classification performance of a Multi-Layer Perceptron Neural Network (MLP NN) using 5-fold cross-validation.

## Dataset

The dataset is structured as follows:

- Sepal Length (in Cm)
- Sepal Width (in Cm)
- Petal Length (in Cm)
- Petal Width (in Cm)
- Species (target variable: setosa, versicolor, virginica)

## Methodology

1. **Classifier:** MLP NN
2. **Evaluation:** 5-fold cross-validation
3. **Parameters:** Varying the number of hidden layers and neurons in each layer

## Results

The project aims to identify the optimal configuration of the MLP NN for achieving the best classification performance. For each configuration, the following metrics are computed:

- Confusion Matrix
- Sensitivity
- Specificity
- Total Accuracy
- F1-score
- ROC Curve
- Area Under the Curve (AUC)

The results are presented in a comprehensive manner, highlighting the configuration that yields the highest accuracy and corresponding metrics.

## Conclusion

The documentation provides a detailed analysis of the MLP NN configurations and their impact on classification accuracy, aiding future studies and applications in similar domains.
