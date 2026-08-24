# 📊 Customer Churn Prediction System

## 📌 Project Overview

**Customer Churn Prediction System** is a Machine Learning project that predicts whether a customer is likely to **leave a company or continue using its services**.

The system analyzes customer information such as tenure, monthly charges, contract type, payment method, and other features to predict customer churn.

This project helps businesses identify customers who are at risk of leaving and take suitable actions to retain them.

---

## 🎯 Objectives

* Analyze customer data.
* Clean and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA).
* Identify important factors affecting customer churn.
* Train Machine Learning classification models.
* Predict whether a customer will churn or not.
* Evaluate model performance.
* Create a simple prediction application.

---

## 📊 Dataset

The dataset contains customer information and their service usage details.

### Important Features

* **Gender** – Customer gender
* **Senior Citizen** – Whether the customer is a senior citizen
* **Partner** – Whether the customer has a partner
* **Dependents** – Whether the customer has dependents
* **Tenure** – Number of months the customer has stayed
* **Phone Service** – Availability of phone service
* **Internet Service** – Type of internet service
* **Contract** – Customer contract type
* **Payment Method** – Customer payment method
* **Monthly Charges** – Monthly amount paid
* **Total Charges** – Total amount paid
* **Churn** – Whether the customer left the company

> **Target Variable:** Churn

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**
* **Streamlit**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Collection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Customer Churn Prediction
   ↓
Web Application
```

---

## 🤖 Machine Learning Models

The following classification algorithms can be used:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM)

The best model is selected based on its performance on the test data.

---

## 📏 Evaluation Metrics

The models are evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**
* **ROC-AUC Score**

These metrics help determine how accurately the system identifies customers who are likely to churn.

---

## 📈 Exploratory Data Analysis

EDA is performed to understand:

* Customer churn distribution
* Churn based on contract type
* Churn based on tenure
* Churn based on monthly charges
* Churn based on internet service
* Churn based on payment method
* Relationship between customer characteristics and churn

---

## 🌐 Web Application

A simple web application can be developed using **Streamlit**.

The user enters customer details, and the system predicts whether the customer is likely to:

```text
🟢 Stay with the company
        OR
🔴 Leave the company
```

### Application Features

* Simple and user-friendly interface
* Customer information input
* Machine Learning model integration
* Real-time churn prediction
* Easy-to-understand prediction result

---

## 📁 Project Structure

```text
Customer_Churn_Prediction/
│
├── app.py
├── customer_churn.csv
├── model.pkl
├── columns.pkl
├── requirements.txt
├── README.md
│
└── notebooks/
    └── Customer_Churn_Prediction.ipynb
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Harsh-11-06/Customer-Churn-Prediction.git
```

### 2. Open the Project Folder

```bash
cd Customer-Churn-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your web browser.

---

## 💡 Applications

Customer churn prediction can be used in:

* 🏦 Banking
* 📱 Telecommunication
* 🛒 E-commerce
* 🎬 Subscription services
* 🏨 Hospitality
* 💳 Financial services
* 📡 Internet service providers

---

## 🔮 Future Scope

* Improve prediction accuracy.
* Use advanced Machine Learning and Deep Learning models.
* Add customer retention recommendations.
* Predict the probability of customer churn.
* Add interactive dashboards.
* Deploy the system on cloud platforms.
* Integrate real-time customer data.
* Provide personalized offers to high-risk customers.

---

## ✅ Conclusion

The **Customer Churn Prediction System** uses Machine Learning to identify customers who are likely to leave a company.

By predicting churn in advance, businesses can take appropriate actions such as providing offers, improving services, and communicating with customers.

This project demonstrates the practical use of **Data Analysis, Machine Learning, Classification, and Streamlit** in solving a real-world business problem.

---

## 👩‍💻 Author

**Harsh Fulawade**

AI & Data Science Student

---

## ⭐ Support

If you find this project useful, please give the repository a **⭐ Star** on GitHub.
