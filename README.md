# Data-Science-Portfolio
# Project 1
# 🌾 Crop Yield Prediction using ANN

A machine learning model that predicts crop yield based on agricultural features using an Artificial Neural Network (ANN). This model helps improve decision-making for farmers and policymakers by providing accurate yield predictions.

---

## 🔍 Overview

This project aims to forecast crop yield using key agricultural factors such as:
- Annual Rainfall
- Area under cultivation
- Fertilizer usage
- And other relevant features

An Artificial Neural Network (ANN) was trained to map these features to the expected yield. The model achieves an **R² score of 88%**, indicating strong predictive performance.

---

## 🧠 Model Architecture
The model was built using Keras (TensorFlow backend) and consists of 2 hidden layers and 1 output layer


# Project 2
# Heart Disease prediction using neural networks
A simple neural network model to predict the presence of heart disease using patient medical data.

## 🔧 Model Details

- **Architecture:**
  - Input: 12 features
  - Hidden Layers: 32 → 16 units (ReLU activation)
  - Output Layer: 2 units (Sigmoid activation)

- **Accuracy:** ~97%

## 📊 Features Used

- `age`, `sex`, `cp` (chest pain type), `trestbps` (resting BP), `chol` (cholesterol)
- `fbs` (fasting blood sugar), `restecg` (ECG), `thalach` (max heart rate)
- `exang` (exercise-induced angina), `oldpeak`, `slope`, `ca` (major vessels), `thal`

## 🧠 Tech Stack

- Python
- TensorFlow / Keras
- pandas, numpy, scikit-learn

# Project 3
# 🔤 Next Word Prediction using LSTM

This project is about predicting the next sequence of words in a sentence using a simple LSTM-based language model. It was trained on a custom text dataset, where the model learns word patterns and suggests what could come next.

## 🧠 Model Overview

The model uses an Embedding layer to understand word relationships, followed by an LSTM layer to capture sequence patterns, and ends with a Dense layer to predict the most likely next word. It was built using the Sequential API in Keras.

## 📚 Dataset

Trained on a text corpus with ~1 lakh characters where the data is processed into sequences. Each sequence helps the model learn how words follow each other. The model achieved ~94% accuracy.

## 💡 Example

- Input: *"I am happy"*
- Prediction: *"to give the house"*

## ⚙️ Tech Stack

- Python  
- TensorFlow / Keras  
- NLTK  
- NumPy, Pandas

---


