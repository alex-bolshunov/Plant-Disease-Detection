# Detecting Plant Diseases Using Machine Learning

## Project Overview
This project leverages traditional machine learning algorithms to classify healthy and diseased potato leaves using image data from the PlantVillage dataset. The goal was to compare the performance of various models and identify those best suited for real-time agricultural applications.

## Dataset
- **Source**: [PlantVillage Dataset]([https://plantvillage.psu.edu/](https://www.kaggle.com/datasets/emmarex/plantdisease))
- **Subset**: Potato leaf images with three classes (healthy, early blight, late blight)
- **Samples**: 2152 (augmented and oversampled)

## Technologies Used
- Python
- scikit-learn
- img2vec
- matplotlib

## Feature Extraction
- **Tool**: `img2vec` (PyTorch pre-trained models)
- **Model Used**: ResNet-18
- **Output**: 512-dimensional feature vectors

## Machine Learning Models
- Support Vector Machine (SVM)
- Decision Tree
- Naive Bayes
- K-Nearest Neighbor (KNN)
- Perceptron

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Average Inference Time

## Results Summary
| Model         | Accuracy | Precision | Recall | F1-Score |
| ------------- | -------- | --------- | ------ | -------- |
| **SVM (RBF)** | 0.977    | 0.989     | 0.980  | 0.985    |
| Perceptron    | 0.943    | 0.971     | 0.968  | 0.970    |
| KNN (k=7)     | 0.886    | 0.935     | 0.886  | 0.896    |
| Naive Bayes   | 0.842    | 0.881     | 0.950  | 0.913    |
| Decision Tree | 0.770    | 0.866     | 0.853  | 0.859    |




