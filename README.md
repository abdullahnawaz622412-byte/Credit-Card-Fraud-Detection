# 💳 Credit Card Fraud Detection using Isolation Forest

## 📌 Overview

This project uses the **Isolation Forest** algorithm to detect fraudulent credit card transactions through anomaly detection.

Unlike traditional supervised learning models, Isolation Forest identifies unusual observations by learning the patterns of normal data and isolating anomalies.

This project demonstrates how anomaly detection can be applied to real-world financial fraud detection.

---

## 📂 Dataset

**Credit Card Fraud Detection Dataset**

The dataset contains anonymized credit card transactions made by European cardholders.

Features include:

- Time
- Transaction Amount
- 28 anonymized numerical features (V1–V28)
- Class (used only for evaluation)

Target Values:

- **0 → Normal Transaction**
- **1 → Fraudulent Transaction**

---

## 🎯 Objective

The objective of this project is to detect fraudulent credit card transactions using the Isolation Forest algorithm and evaluate how effectively it identifies anomalies.

---

## 🛠️ Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- jupyter

---

## 📚 Concepts Practiced

- Unsupervised Learning
- Anomaly Detection
- Isolation Forest
- Data Exploration
- Feature Scaling
- Model Evaluation
- Visualization
- Fraud Detection

---

## 🔄 Project Workflow

### 1. Import Libraries

Import all required libraries for data processing, visualization, and anomaly detection.

---

### 2. Load the Dataset

Load the credit card transaction dataset into a pandas DataFrame.

---

### 3. Explore the Dataset

Perform basic exploratory data analysis by:

- Viewing the first few rows
- Checking data types
- Inspecting dataset dimensions
- Generating summary statistics
- Checking for missing values

---

### 4. Data Preparation

- Separate input features from the target column
- Prepare the data for anomaly detection

---

### 5. Train the Isolation Forest Model

Train an Isolation Forest model to identify unusual observations within the dataset.

Important parameters include:

- Contamination
- Random State

---

### 6. Detect Anomalies

Use the trained model to classify transactions as either:

- Normal
- Anomaly

---

### 7. Evaluate the Results

Compare predicted anomalies with the actual fraud labels to evaluate model performance.

---

### 8. Visualize the Results

Create visualizations to better understand:

- Distribution of normal and fraudulent transactions
- Detected anomalies
- Model predictions

---

## 📈 Results

The Isolation Forest model successfully identified unusual transactions within the dataset.

This project demonstrates how anomaly detection techniques can be used when fraudulent examples are rare compared to normal transactions.

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

- Compare Isolation Forest with Local Outlier Factor (LOF)
- Compare with One-Class SVM
- Tune the contamination parameter
- Perform dimensionality reduction using PCA for visualization
- Build an interactive fraud detection dashboard
- Deploy the trained model using Streamlit

---

## 👨‍💻 Author

**Abdullah Nawaz**

This project is part of my Machine Learning & Deep Learning learning roadmap, where I build practical projects to strengthen my understanding of machine learning concepts through hands-on implementation.
