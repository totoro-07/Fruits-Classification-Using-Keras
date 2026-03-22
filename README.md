# 🍎 Fruits Classification Using Keras

A deep learning project for classifying different types of fruits using Convolutional Neural Networks (CNN) built with Keras/TensorFlow.

---

## 📌 Project Overview

This project implements a deep learning model to automatically classify fruit images into different categories. The model is trained using Keras, a high-level neural networks API, and TensorFlow as the backend. The system can recognize and classify various fruits with high accuracy.

---

## 🎯 Objectives

- Build a robust CNN model for fruit image classification
- Achieve high accuracy in distinguishing between different fruit types
- Export models in multiple formats (Keras, H5, TFLite, TensorFlow.js)
- Create a scalable and deployable solution

---

## 🧠 Technology Stack

- **Python** - Programming language
- **Keras** - High-level neural networks API
- **TensorFlow** - Machine learning framework
- **OpenCV** - Image processing
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation
- **Matplotlib** - Data visualization
- **Jupyter Notebook** (100%) - Development environment

---


---

## 📊 Dataset

The project uses a fruits image classification dataset containing multiple fruit categories. The dataset includes:
- High-quality fruit images
- Multiple varieties of each fruit
- Balanced class distribution
- Preprocessed and normalized images

---

## 🏗️ Model Architecture

The model uses a **Convolutional Neural Network (CNN)** with the following characteristics:

- **Input Layer**: Accepts image tensors of size 224×224×3 (RGB)
- **Convolutional Layers**: Extract features from images
- **Pooling Layers**: Reduce spatial dimensions
- **Dense Layers**: Classify features into fruit categories
- **Activation Functions**: ReLU and Softmax
- **Regularization**: Dropout to prevent overfitting

### Model Details:
- Total Parameters: Millions of trainable weights
- Training Epochs: Multiple epochs with early stopping
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy

---

## 📥 Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager
- Jupyter Notebook (optional)

### Setup Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/totoro-07/Fruits-Classification-Using-Keras.git
   cd Fruits-Classification-Using-Keras
