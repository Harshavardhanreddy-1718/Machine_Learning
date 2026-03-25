# Convolutional Neural Networks for Image Classification (CIFAR-10)

##  Overview
This project demonstrates how Convolutional Neural Networks (CNNs) can be used for image classification. The focus is on understanding how architectural improvements and regularization techniques impact model performance.

Three models are implemented and compared:
- Baseline CNN
- Improved CNN (deeper architecture)
- Regularized CNN (Batch Normalization + Dropout)

---

##  Dataset
This project uses the CIFAR-10 dataset, which consists of 60,000 32x32 color images across 10 classes including airplanes, automobiles, animals, and ships.

---

##  Methodology

### 1. Data Preprocessing
- Normalization of pixel values
- One-hot encoding of labels

### 2. Model Architectures
- Baseline CNN: Simple structure for comparison
- Improved CNN: Increased depth for better feature extraction
- Regularized CNN: Batch Normalization + Dropout for improved generalization

### 3. Training Optimization
- Early stopping to prevent overfitting
- Efficient batch size selection

---

##  Results

The regularized CNN achieved the best performance, demonstrating:
- Improved validation accuracy
- Reduced overfitting
- More stable learning curves

---

##  Visualizations

The following visual outputs are included:

- Sample dataset images
- Validation loss comparison
- Validation accuracy comparison
- Confusion matrix
- Model predictions vs true labels
