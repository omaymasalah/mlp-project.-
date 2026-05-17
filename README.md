# Medical Diagnosis using Neural Network (MLP)

# Project Overview

This project uses a Neural Network (MLP - Multi Layer Perceptron) to predict whether a patient has diabetes based on medical attributes.

The model was implemented using PyTorch and trained on the Pima Indians Diabetes Dataset.

# Dataset

Dataset: Pima Indians Diabetes Dataset

The dataset contains medical information about patients such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target:
- 1 → Diabetes
- 0 → No Diabetes

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PyTorch

# Neural Network Architecture

The model consists of:

1. Input Layer
2. Hidden Layer (32 neurons, ReLU)
3. Batch Normalization
4. Dropout Layer (0.3)
5. Hidden Layer (16 neurons, ReLU)
6. Batch Normalization
7. Dropout Layer (0.3)
8. Hidden Layer (8 neurons, ReLU)
9. Output Layer (1 neuron, Sigmoid)

# Data Preprocessing

The following preprocessing steps were applied:

- Loading the dataset
- Replacing missing values (zeros) with mean values
- Handling features and target
- Train/Test split
- Feature Scaling using StandardScaler
- Converting data into PyTorch tensors

# Training Configuration

- Optimizer: Adam
- Loss Function: Binary CrossEntropy (BCELoss)
- Epochs: 50
- Learning Rate: 0.001

# Evaluation Metrics

The model was evaluated using:

- Accuracy Score
- Loss Function
- Training Accuracy
- Testing Accuracy

# Experiments

## Experiment 1
Added Batch Normalization to improve training stability.

## Experiment 2
Added Dropout layers to reduce overfitting.

# Visualization

The project includes:

- Training vs Testing Loss Curve
- Training vs Testing Accuracy Curve

# How to Run the Project

## 1. Install required libraries

pip install numpy pandas matplotlib scikit-learn torch

## 2. Run all notebook cells in order

1. Import libraries
2. Load dataset
3. Data preprocessing
4. Build MLP model
5. Train model
6. Evaluate model
7. Display graphs

# Results

The Neural Network achieved good accuracy in predicting diabetes.

The experiments showed that Batch Normalization and Dropout layers improved the model performance and helped reduce overfitting.

# Author

Omayma Salah Mohamed Mohamed

# Future Improvements

- Hyperparameter Tuning
- Using Deep Neural Networks
- Trying different activation functions
- Testing different optimizers
- Deploying the model as a web application
- 
