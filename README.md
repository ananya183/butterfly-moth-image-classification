# Butterfly/Moth Image Classification Project

This project aims to classify butterfly and moth species using two distinct methods: traditional machine learning and deep learning. The goal is to compare the performance of these approaches in accurately identifying species from images.

## Methodology

### 1. Traditional Machine Learning
- **Feature Extraction**: Histogram of Oriented Gradients (HOG)
- **Classifiers**: 
  - Support Vector Machine (SVM)
  - Decision Tree
  - Logistic Regression

### 2. Deep Learning
- **Model**: ResNet50 pre-trained model

## Results

The ResNet50 model demonstrated superior performance in classifying butterfly and moth species:

- **Validation Set Accuracy**: 77.80%
- **Testing Set Accuracy**: 79.40%

These results highlight the efficacy of the ResNet50 model, suggesting that the preprocessing steps and chosen architecture were well-suited for this classification task.

## Conclusion

This project provides valuable insights into the effectiveness of traditional machine learning versus deep learning for butterfly image classification. The high accuracy achieved by the ResNet50 model underscores its potential in accurately classifying butterfly and moth species.
