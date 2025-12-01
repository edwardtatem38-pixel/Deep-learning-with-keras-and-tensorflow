[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/edwardtatem38-pixel/Deep-learning-with-keras-and-tensorflow/blob/main/Deep_Learning_with_keras_and_tensor_flow%20(1).ipynb)
# 🏆 Weighted Logistic Regression Model: Loan Default Risk Predictor

## Executive Summary
This project develops and optimizes a **Logistic Regression** model using advanced techniques to predict loan default risk (`TARGET=1`). The core challenge of severe **class imbalance** (only **8.07%** default rate) was directly addressed using **scikit-learn's `compute_class_weight`** and **weighted modeling**.

The solution achieved a balance between minimizing False Positives (denying good loans) and maximizing True Positives (identifying actual defaulters) by tuning the classification threshold based on the **F1-Score**.
