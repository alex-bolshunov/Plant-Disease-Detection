# Detecting Plant Diseases Using Machine Learning

## Project Overview
This project focuses on the early detection of plant diseases using machine learning techniques. Timely disease detection can significantly minimize crop damage and prevent potential harvest losses. By analyzing images of bell pepper leaves, both healthy and diseased, we trained and evaluated multiple machine learning models to assess their suitability for real-time agricultural applications.

## Dataset
- **Source**: [PlantVillage Dataset]([https://plantvillage.psu.edu/](https://www.kaggle.com/datasets/emmarex/plantdisease))
- **Subset**: Bell pepper leaves (healthy and affected by bacterial spot)
- **Samples**: 2474 images (1477 healthy, 997 diseased)

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
| Model          | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| SVM            | 0.990    | 0.990     | 0.995  | 0.992    |
| Decision Tree  | 0.913    | 0.918     | 0.942  | 0.930    |
| Naive Bayes    | 0.936    | 0.964     | 0.930  | 0.946    |
| K-Nearest Neighbor | 0.976 | 0.972    | 0.989  | 0.980    |
| Perceptron     | 0.995    | 0.995     | 0.997  | 0.996    |



