# 📚 Fitness Dropout Predictor

Predicting user dropout in fitness programs using machine learning to understand engagement patterns and improve retention.

---

## 🧩 Project Overview

This project is divided into two main phases:

* **Phase 1:** Data Cleaning, Preprocessing, and Exploratory Data Analysis (EDA)
* **Phase 2:** Model Building, Training, and Evaluation using a Neural Network (MLP)

The goal is to transform raw user data into meaningful insights and build a predictive model to identify potential dropouts.

---

## 🔍 Phase 1: Data Cleaning & Exploratory Data Analysis

Phase 1 focuses on preparing the dataset and extracting insights.

### 📌 1. Data Loading

* Imported dataset and inspected its structure
* Identified feature types (numerical, categorical)

### 🧹 2. Data Cleaning

* Handled missing values using appropriate strategies (mean/mode/drop)
* Removed duplicate records
* Fixed inconsistent or incorrect data entries
* Converted data types where necessary

### 🏗️ 3. Feature Engineering

* Created meaningful features from raw data
* Encoded categorical variables
* Normalized / scaled numerical features

### 📊 4. Exploratory Data Analysis (EDA)

* Visualized distributions of key features
* Identified patterns related to user dropout
* Checked correlations between variables
* Detected outliers and anomalies

### 💡 Key Insights

* Identified factors influencing user dropout
* Observed behavioral trends in retained vs dropped users

---

## 🤖 Phase 2: Model Building & Training

Phase 2 focuses on building a predictive model using machine learning.

### 🧠 1. Model Selection

* Implemented a **Multi-Layer Perceptron (MLP)** using PyTorch
* Designed architecture with input, hidden, and output layers

### ⚙️ 2. Data Preparation for Training

* Split dataset into training and testing sets
* Converted data into tensors
* Ensured proper feature scaling

### 🏋️ 3. Model Training

* Defined loss function (e.g., Binary Cross-Entropy)
* Used optimizer (e.g., Adam)
* Trained model over multiple epochs
* Monitored loss and learning progress

### 📉 4. Evaluation

* Measured performance using accuracy and other metrics
* Compared predictions with actual outcomes
* Analyzed model behavior

### 📈 5. Results

* Evaluated how well the model predicts dropout
* Identified strengths and limitations of the model

---

## 🚀 Key Highlights

* End-to-end ML workflow from raw data → predictions
* Custom neural network implementation using PyTorch
* Strong focus on data understanding and preprocessing
* Practical application of ML for user retention problems

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib / Seaborn
* PyTorch

---

## ▶️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/fitness-dropout-predictor.git
cd fitness-dropout-predictor
pip install -r requirements.txt
```

Run notebooks:

* Open `Phase1.ipynb` for data analysis
* Open `Phase2.ipynb` for model training

---

## 📌 Future Improvements

* Hyperparameter tuning
* Trying alternative models (Random Forest, XGBoost)
* Model deployment (web app / API)
* Improved feature engineering

---
