# Fraud-detection-v1
This project is a **Fraud Detection System** designed to identify fraudulent transactions using a machine learning model. The system includes a trained model, a scaler for preprocessing data, and a prediction pipeline that processes real-world data for fraud classification.


# Fraud Detection System

This project is a **Fraud Detection System** designed to identify fraudulent transactions using a machine learning model. The system includes a trained model, a scaler for preprocessing data, and a prediction pipeline that processes real-world data for fraud classification.

---

## Features

- **Machine Learning Model**: Uses a pre-trained Random Forest model for fraud detection.
- **Scalable Preprocessing**: StandardScaler ensures consistent data preprocessing.
- **Real-Time Predictions**: Predicts fraud probability for new transaction data.
- **Feature Alignment**: Automatically aligns test data with the required feature order.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/farruhpy/fraud-detection-system.git
   cd fraud-detection-system

2. Install required Python libraries:


pip install -r requirements.txt




3. Place the trained model, scaler, and feature metadata in the appropriate directory:

fraud_models/random_forest/
model.joblib
scaler.joblib
feature_names.joblib

**File Structure**

fraud-detection-system/
│
├── fraud_models/
│   └── random_forest/
│       ├── model.joblib
│       ├── scaler.joblib
│       ├── feature_names.joblib
│
├── your_test_data.csv   # Example test dataset
├── main.py              # Main script for testing
├── requirements.txt     # List of dependencies
└── README.md            # Project documentation


XGBoost Confusion Matrix:
![0f1d349f-6fc8-4a0c-817c-ea24bdc2f2c7](https://github.com/user-attachments/assets/a3d987c4-509d-46d8-94f8-1045972ab933)





