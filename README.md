# Osteoporosis Detection Using Deep Learning on X-Ray Images of Human Spine

## Overview

Osteoporosis is a metabolic bone disease prevalent among the elderly population, leading to weakened bones and an increased risk of fractures. Early detection is crucial as there's no proven cure for Osteoporosis. This project focuses on leveraging deep learning models, particularly Convolutional Neural Networks (CNN), to detect and classify osteoporosis using human spine X-ray images. The dataset comprises grayscale images, with both affected and unaffected samples.

## Motivation

X-rays are cost-effective and widely accessible, making them a prime choice for early disease detection. Most individuals opt for an X-ray when experiencing spine-related issues. Therefore, building a model based on spine X-rays can significantly aid in the early detection of osteoporosis, potentially leading to timely interventions and better patient outcomes.

## Model Architectures and Performance

### VGG16 with Random Forest Classifier:

- **Architecture**: The VGG16 model was modified to work on grayscale images. It was primarily used for feature extraction, and the extracted features were then utilized to build the random forest classification model.
  
- **Performance**:
  - Accuracy: 95%
  - F1 Score: 95.95
  - AUC: 90.95

### Resnet50 with Random Forest Classifier:

- **Performance**:
  - Accuracy: 87%
  - F1 Score: 88.86

### InceptionV3 with Random Forest Classifier:

- **Performance**:
  - Accuracy: 89%
  - F1 Score: 89.89

## Data Preprocessing

The dataset contains different sizes of images, which were resized to 224x224, ideal for deep learning models. Data augmentation techniques were applied to enhance the diversity of the training data and prevent overfitting.

## Conclusion

The project showcases the potential of deep learning models in diagnosing osteoporosis from spine X-ray images. The models, especially when trained on X-ray images, present a promising solution for early and affordable osteoporosis detection.


