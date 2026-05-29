# 💳 Credit Card Fraud Detection using Machine Learning

A Machine Learning project to detect fraudulent credit card transactions using Logistic Regression.

---

## 📌 Project Overview

Credit card fraud is one of the biggest financial security problems worldwide.

This project builds a machine learning model that can classify transactions as:

- Legit Transaction → `0`
- Fraudulent Transaction → `1`

The model is trained on transaction data and predicts whether a transaction is fraudulent or not.

---

# 🚀 Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

# 📂 Dataset

Dataset used:

**Credit Card Fraud Detection Dataset**

Contains anonymized transaction records with:

- Time
- Amount
- V1 → V28 features
- Class label

Where:

- `0 = Normal`
- `1 = Fraud`

---

# ⚙️ Workflow

## 1. Data Collection
Loaded dataset using Pandas.

## 2. Data Preprocessing
- Checked null values
- Checked class imbalance

## 3. Exploratory Data Analysis
- Fraud vs normal transaction distribution
- Statistical summary

## 4. Data Balancing
Used random sampling because dataset was highly imbalanced.

## 5. Train Test Split
Split dataset into:

- Training Data
- Testing Data

## 6. Model Training
Used:

- Logistic Regression

## 7. Model Evaluation
Evaluated using:

- Accuracy Score

---

# 📈 Results

Model performance:

- Training Accuracy: XX%
- Testing Accuracy: XX%

> Replace XX with your output from notebook.

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/YOUR_USERNAME/credit-card-fraud-detection.git
```

Move inside folder:

```bash
cd credit-card-fraud-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

---

# 📷 Project Preview

You can add screenshots here.

Example:

![Project Preview](images/fraud-vs-normal.png)

---

# 📚 Learning Outcomes

Through this project I learned:

- Data preprocessing
- Handling imbalanced datasets
- Logistic Regression
- Model training
- Model evaluation
- Fraud detection workflow

---

# 👨‍💻 Author

Muhammad Ahsan

Machine Learning Student | AI Enthusiast

GitHub: https://github.com/YOUR_USERNAME
