# 🛒 Super Store Sales Prediction

## 📌 Project Overview

**Super Store Sales Prediction** is a Machine Learning project that predicts sales based on different features of a superstore dataset.

The project uses **Data Analysis, Data Preprocessing, Visualization, and Machine Learning** techniques to build a model that can predict future sales.

---

## 🎯 Objectives

* Analyze Super Store sales data.
* Perform data preprocessing and cleaning.
* Identify important factors affecting sales.
* Visualize sales patterns and trends.
* Train Machine Learning regression models.
* Predict sales for new data.
* Evaluate the performance of the trained model.

---

## 📊 Dataset

The dataset contains information about different orders and sales transactions.

### Important Features

* **Ship Mode** – Shipping method
* **Segment** – Customer segment
* **Category** – Product category
* **Sub-Category** – Product sub-category
* **Sales** – Sales amount
* **Quantity** – Number of products sold
* **Discount** – Discount given
* **Profit** – Profit generated
* **Region** – Sales region
* **State** – Customer state
* **City** – Customer city

> **Target Variable:** Sales

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Streamlit**
* **Flask**
* **Jupyter Notebook**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Collection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Sales Prediction
   ↓
Web Application
```

---

## 🤖 Machine Learning Models

Different regression algorithms can be used for sales prediction, such as:

1. Linear Regression
2. K-Nearest Neighbors Regressor
3. Decision Tree Regressor
4. Random Forest Regressor

The best-performing model can be selected based on evaluation metrics.

---

## 📏 Evaluation Metrics

The models are evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**

A higher **R² score** and lower error values indicate better model performance.

---

## 📈 Exploratory Data Analysis

EDA is performed to understand:

* Sales distribution
* Sales by category
* Sales by region
* Sales and profit relationship
* Impact of discount on sales
* Most profitable products
* Customer segment performance

---

## 🌐 Web Application

A web application is created using **Streamlit** to make the prediction model easy to use.

The user can enter the required input values, and the application predicts the expected sales.

### Application Features

* Simple user interface
* Input fields for prediction
* Machine Learning model integration
* Real-time sales prediction
* Easy-to-understand results

---

## 📁 Project Structure

```text
Super_store/
│
├── app.py
├── Super_Store_Sales.csv
├── model.pkl
├── columns.pkl
├── requirements.txt
├── README.md
│
└── notebooks/
    └── Super_Store_Sales_Prediction.ipynb
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Super-Store-Sales-Prediction.git
```

### 2. Open the Project Folder

```bash
cd Super-Store-Sales-Prediction
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

## 🔮 Future Scope

* Use larger and more recent datasets.
* Improve model accuracy using hyperparameter tuning.
* Add advanced Machine Learning algorithms.
* Add interactive dashboards.
* Deploy the application on cloud platforms.
* Add sales forecasting for future dates.
* Integrate real-time sales data.

---

## ✅ Conclusion

The **Super Store Sales Prediction** project demonstrates how Machine Learning can be used to predict sales from historical business data.

The project combines **Python, Data Analysis, Visualization, Machine Learning, and Streamlit** to create a complete end-to-end sales prediction system.

---

## 👩‍💻 Author

**Harsh Fulawade**

AI & Data Science Student

---

## ⭐ Support

If you find this project useful, please give the repository a **⭐ Star** on GitHub.
