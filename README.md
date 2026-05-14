Credit Card Fraud Detection using Deep Learning

This project focuses on detecting fraudulent credit card transactions using a deep learning approach. The dataset is highly imbalanced, making fraud detection a challenging classification problem.

🎯 Objective

To build a neural network model capable of accurately identifying fraudulent transactions while handling severe class imbalance.

🧠 Approach

Data preprocessing and feature scaling using StandardScaler
Train/Validation/Test split with stratification to preserve class distribution
Class imbalance handled using SMOTE (Synthetic Minority Oversampling Technique)
Deep Neural Network built using TensorFlow / Keras
Regularization techniques (Dropout) applied to reduce overfitting
Model evaluated using Precision, Recall, and AUC metrics
⚙️ Model Architecture
Input layer with normalized features
Multiple Dense layers with ReLU activation
Dropout layers for regularization
Output layer with Sigmoid activation for binary classification
📊 Evaluation

The model was evaluated using precision and recall metrics, with a focus on improving fraud detection performance in highly imbalanced data.

🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
TensorFlow / Keras
Imbalanced-learn (SMOTE)

🚀 Goal

To simulate a real-world fraud detection system using deep learning techniques and imbalanced data handling strategies.
