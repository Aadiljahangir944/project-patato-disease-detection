# Potato Disease Classification Using Deep Learning

## Overview

This project is a deep learning-based image classification system designed to identify and classify potato leaf diseases using Convolutional Neural Networks (CNNs). The model automatically detects multiple disease categories from leaf images, enabling early diagnosis and supporting precision agriculture practices.

The solution was developed using TensorFlow and Keras, with an automated data preprocessing and training pipeline to improve model accuracy and scalability.

## Key Features

- Multi-class potato disease classification using CNN architecture
- Automated image preprocessing and augmentation pipeline
- Deep learning model built with TensorFlow and Keras
- Real-time disease prediction capability
- Model evaluation using industry-standard performance metrics
- Hyperparameter tuning and performance optimization
- Scalable workflow for training and inference

## Disease Categories

The model classifies potato leaf images into multiple categories, including:

- Early Blight
- Late Blight
- Healthy

*(Categories may vary depending on the dataset used.)*

## Technology Stack

### Programming Language
- Python

### Deep Learning Frameworks
- TensorFlow
- Keras

### Data Processing & Visualization
- NumPy
- Pandas
- Matplotlib
- OpenCV

### Development Environment
- Jupyter Notebook
- Google Colab

## System Workflow

### 1. Data Collection
- Load potato leaf image dataset
- Organize images into disease classes

### 2. Data Preprocessing
- Image resizing
- Normalization
- Dataset splitting (Train/Test/Validation)
- Data cleaning

### 3. Data Augmentation
- Rotation
- Zooming
- Flipping
- Brightness adjustments

### 4. Model Development
- CNN architecture design
- Feature extraction through convolutional layers
- Classification through dense layers

### 5. Model Training
- Batch training
- Validation monitoring
- Loss and accuracy tracking
- Hyperparameter optimization

### 6. Model Evaluation
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### 7. Real-Time Prediction
- Upload leaf image
- Process image
- Generate disease prediction
- Display confidence score

## Project Structure

```
Potato-Disease-Classification/
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
│   └── cnn_model.h5
│
├── notebooks/
│   └── training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── augmentation.py
│   ├── train_model.py
│   ├── evaluate.py
│   └── predict.py
│
├── results/
│   ├── confusion_matrix.png
│   └── training_curves.png
│
├── requirements.txt
│
└── README.md
```

## Model Performance

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model was optimized through hyperparameter tuning and regularization techniques to improve generalization and inference performance.

## Challenges Solved

- Handling image variability across disease classes
- Preventing model overfitting using augmentation techniques
- Optimizing training performance for better classification accuracy
- Building a robust real-time prediction workflow

## Future Enhancements

- Transfer Learning using EfficientNet or ResNet
- Mobile application deployment
- Cloud-based inference API
- Multi-crop disease detection
- Explainable AI using Grad-CAM visualizations

## Author

Aadil Jahangir

## License

This project is intended for educational, research, and portfolio purposes.
