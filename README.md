# Hyperspectral Image Classification

This project focuses on the classification of hyperspectral images using three different models: K-Nearest Neighbors (KNN), Random Forest (RF), and Artificial Neural Network (ANN). The Pavia University dataset was utilized for training and testing the models.

## Dataset
The Pavia University dataset consists of hyperspectral images captured by the Reflective Optics System Imaging Spectrometer (ROSIS) sensor over Pavia University in Italy. The dataset contains spectral information for each pixel, making it suitable for classification tasks.

## Models Implemented

### K-Nearest Neighbors (KNN)
The K-Nearest Neighbors algorithm is a non-parametric method used for classification and regression tasks. It classifies a data point based on the majority class of its k nearest neighbors in the feature space.

### Random Forest (RF)
Random Forest is an ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes as the prediction of individual trees. It offers robustness against overfitting and high accuracy in classification tasks.

### Artificial Neural Network (ANN)
In this project, Artificial Neural Networks (ANNs) were employed for hyperspectral image classification both without and with Principal Component Analysis (PCA) dimensionality reduction. ANNs are computational models inspired by the structure and function of the human brain. PCA was applied to reduce the dimensionality of the input data before training the ANN from 103 bands to 20.

## Results

### KNN
- **Accuracy:** 0.79
- **F1 score:** 0.51

### RF
- **Accuracy:** 0.94
- **F1 score:** 0.92

### ANN
- **Accuracy:** 0.95
- **F1 score:** 0.92

### ANN with PCA
- **Accuracy:** 0.91
- **F1 score:** 0.89

## Conclusion
In conclusion, this project demonstrates the application of machine learning techniques for hyperspectral image classification using the Pavia University dataset. Each implemented model offers different advantages and performance characteristics, which can be further explored and optimized for specific classification tasks.

## Contributors
- Mehdi Ben Salha
- Zakaria Soussi
- Yassine Dhaouadi
- Wissem Yousfi



