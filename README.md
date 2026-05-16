## Neural Network Fundamentals and Training Behavior Analysis

# Approach

The project follows a structured machine learning workflow to build a neural network model for customer churn prediction. The dataset was first explored and preprocessed using encoding and feature scaling techniques. A feed-forward neural network was then built using TensorFlow/Keras, trained on the processed data, and evaluated using accuracy, loss, and confusion matrix metrics. Multiple hyperparameter experiments were conducted to analyze how different configurations affect model performance.


# Problem Statement

The objective of this project is to build a feed-forward neural network model to predict customer churn using supervised learning techniques.

This is a binary classification problem where:

- "1" = Customer churned
- "0" = Customer retained

The project also analyzes how neural networks learn through training behavior, loss optimization, and hyperparameter tuning.


# Dataset Description

- Dataset: Customer Churn Neural Network Dataset
- Dataset Link: https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJIV-wBvUYs?usp=sharing


# Steps Followed

1. Data Preprocessing

- Loaded dataset using Pandas
- Checked missing values
- Encoded categorical features using one-hot encoding
- Scaled numerical features using "StandardScaler"
- Split dataset into training and testing sets


2. Model Building

A feed-forward neural network was built using TensorFlow/Keras with:

- Input layer
- Hidden layers using ReLU activation
- Output layer using Sigmoid activation

Loss Function

- Binary Crossentropy

Optimizer

- Adam


3. Model Training

- Trained the neural network on training data
- Used validation split during training
- Monitored training and validation loss across epochs


# Results

Evaluation Metrics

- Training Accuracy
- Training Loss
- Testing Accuracy
- Testing Loss
- Confusion Matrix

Hyperparameter Experiments

Experiments were conducted by changing:

- Number of hidden layers
- Number of neurons
- Learning rate
- Batch size
- Number of epochs
- Activation function

Result Outputs

- Training vs Validation Loss Graph
- Confusion Matrix
- Hyperparameter Comparison Table


# Observations & Insights

- Feature scaling improved model stability and performance.
- Increasing neurons improved learning capacity.
- Higher learning rates caused unstable convergence.
- More epochs improved learning but increased overfitting risk.
- Validation loss helped monitor model generalization.



# Conclusion

This project demonstrates how neural networks can effectively solve customer churn prediction problems.

The experiments showed that:

- Proper preprocessing is important for neural networks.
- Hyperparameter tuning significantly affects performance.
- Monitoring training behavior helps avoid overfitting and underfitting.

Overall, the neural network achieved good predictive performance on unseen data.