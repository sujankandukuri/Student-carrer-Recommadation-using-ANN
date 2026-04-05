# Student Career Recommendation using ANN
# Project Overview
This project focuses on building an Artificial Neural Network (ANN) model to recommend suitable career paths for students based on their academic performance and skill-related features.
The model analyzes student data and predicts the most appropriate career option using supervised learning techniques.
# Dataset
The dataset used: cs_students.csv
Contains:
 1.Academic scores
 2.Skill-based attributes
 3.Target variable (Career path)
 4.Data set link:https://www.kaggle.com/datasets/reddy88/cs-student-dataset
# Model Architecture
1.Model Type: Artificial Neural Network (ANN)
2.Framework: TensorFlow / Keras
Key Components:
1.Input layer (student features)
2.Hidden dense layers (ReLU activation)
3.Output layer (Softmax for multi-class classification)
# Training Details
1.Epochs: 50
2.Training Accuracy: ~96%
3.Validation Accuracy: ~75%
The model shows strong learning capability with increasing accuracy over epochs.
# Model Performance
 Accuracy
1.Test Accuracy: 75%
# Evaluation Metrics
1.Precision, Recall, and F1-score were used.
2.Weighted average performance:
  Precision: 0.78
  Recall: 0.75
  F1-score: 0.74
# Sample Predictions
Predicted Career
Actual Career
Mobile App Developer
Mobile App Developer
Software Engineer
Mobile App Developer
Database Administrator
Mobile App Developer
Database Administrator
Database Administrator
AI Researcher
AI Researcher
# Conclusion
The ANN model successfully recommends careers based on student data with 75% accuracy. 
