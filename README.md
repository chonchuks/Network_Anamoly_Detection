# 🚀 Network Anomaly Detection Using Machine Learning

Welcome to my **Network Anomaly Detection** project! This repository showcases the application of cutting-edge machine learning algorithms to enhance the accuracy and efficiency of detecting anomalies in network traffic. Whether you're a cybersecurity enthusiast or a machine learning aficionado, this project is designed to provide insights into the power of AI in safeguarding digital infrastructures.


## 🧠 Introduction

Network anomaly detection is crucial for identifying and responding to potential threats that could compromise the integrity of computer networks. This project explores various machine learning models to detect these anomalies effectively. By leveraging data from real-world network environments, we aim to build robust models that not only detect but also predict potential threats.

## ✨ Features
- **Multi-Algorithm Implementation**: Explore Logistic Regression, Random Forest, SVM, ANN, and LSTM models.
- **Real-time Anomaly Detection**: Deploy the best-performing model as a REST API for real-time predictions.
- **Comprehensive Evaluation**: Models are evaluated using precision, recall, F1-score, and more to ensure reliability.

## 🛠️ Installation

1. Clone the repository
2. Navigate to the project directory
3. Install the required packages:

## 🚀 Usage

To run the project and start detecting network anomalies:

1. **Data Preparation**: Ensure you have your network traffic data in the required format.
2. **Model Training**: Train your desired model using the prepared data.
3. **API Deployment**: Deploy the model using FastAPI to enable real-time predictions.
4. **Make Predictions**: Send network data to the API endpoint to receive anomaly predictions.

## 🧑‍💻 Models Implemented

- **Logistic Regression**: Simple and interpretable, ideal for binary classification.
- **Random Forest**: Ensemble model for handling non-linear data relationships.
- **Support Vector Machine (SVM)**: Effective for high-dimensional spaces.
- **Artificial Neural Networks (ANN)**: Captures complex patterns in data.
- **Long Short-Term Memory (LSTM)**: Excels in processing sequential data, making it ideal for temporal anomalies.

## 📊 Results

The LSTM model demonstrated superior performance with:
- **Accuracy**: 0.872
- **F1-Score**: 0.867
- **Precision**: 0.781
- **Recall**: 0.964

This model was integrated into a FastAPI application, providing a robust tool for real-time anomaly detection.

## ✨ Contributors

- **Chukwuka Godwin Onwubolu** - Research and Implementation
