# ANN-Classification
## 🧠 Customer Churn Prediction using ANN
### 📌 Project Overview
This project is an end-to-end machine learning application that predicts whether a customer is likely to churn (exit) from a company based on their profile data. It uses an Artificial Neural Network (ANN) built with TensorFlow/Keras and provides an interactive interface via Streamlit for real-time predictions.

### 🚀 Features'
### Data Preprocessing:

Handled categorical variables using Label Encoding and One-Hot Encoding.
Applied StandardScaler for feature normalization.
Saved preprocessed data and models using Pickle for future use.

### Model Development:

Built an ANN model using Keras Sequential API with multiple Dense layers.
Used Adam optimizer and binary cross-entropy as the loss function.
Implemented EarlyStopping to prevent overfitting.
Integrated TensorBoard for logging and visualizing training metrics.
### Model Evaluation:

Split the dataset into training and testing sets.
Evaluated model performance and displayed whether a customer is likely to churn.
### User Interface:

Developed a Streamlit-based front end for user-friendly interaction and testing.
### 🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
TensorFlow / Keras
Pickle
TensorBoard
Streamlit
### 📈 How It Works
1. Upload or load the customer dataset (CSV).
2. Preprocess the data and save the model pipeline.
3. Train the ANN model and monitor training via TensorBoard.
4. Use the Streamlit app to input customer details and get churn predictions
