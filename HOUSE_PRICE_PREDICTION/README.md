# 🏠 House Price Prediction

## 📌 Project Overview

House Price Prediction is a **Machine Learning project** that predicts the price of a house based on different features such as location, area, number of bedrooms, bathrooms, and other property details.

The project uses historical house data to train a machine learning model and predict the expected price of a new house.

## 🎯 Objectives

* Predict house prices accurately.
* Analyze important factors affecting house prices.
* Perform data preprocessing and data analysis.
* Train and evaluate a machine learning model.
* Provide price predictions for new house data.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data handling and analysis
* **NumPy** – Numerical calculations
* **Matplotlib** – Data visualization
* **Seaborn** – Data visualization
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook**

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── house_data.csv
├── README.md
└── requirements.txt
```

## 🔄 Project Workflow

1. **Collect the Dataset**
2. **Load the Dataset**
3. **Understand the Data**
4. **Data Cleaning**
5. **Handle Missing Values**
6. **Exploratory Data Analysis (EDA)**
7. **Feature Selection**
8. **Split Data into Training and Testing Sets**
9. **Train Machine Learning Model**
10. **Evaluate the Model**
11. **Predict House Prices**

## 🤖 Machine Learning Model

The project can use **Linear Regression** to predict house prices.

### Linear Regression

Linear Regression finds the relationship between input features and house prices.

For example:

```text
House Area + Bedrooms + Location + Bathrooms
                    ↓
            ML Model
                    ↓
            Predicted Price
```

## 📊 Model Evaluation

The model can be evaluated using:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics help measure how accurately the model predicts house prices.

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Harsh-11-06/House-Price-Prediction.git
```

### 2. Open the Project

```bash
cd House-Price-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the `house_price_prediction.ipynb` file and run the cells.

## 📈 Expected Output

The trained model predicts the estimated price of a house based on the given input features.

Example:

```text
Area: 1500 sq.ft
Bedrooms: 3
Bathrooms: 2

Predicted House Price: ₹75,00,000
```

*The actual prediction depends on the dataset and trained model.*

## 🌟 Applications

* Real estate price estimation
* Property investment analysis
* Buyer decision support
* Real estate market analysis
* Property valuation systems

## 🔮 Future Scope

* Use advanced models such as **Random Forest, XGBoost, and Gradient Boosting**.
* Add more location-based features.
* Develop a web application for house price prediction.
* Use real-time property data.
* Improve prediction accuracy using advanced feature engineering.

## 👩‍💻 Author

**Harsh Fulawade**

AI & Data Science Engineering Student

## 📄 License

This project is created for **educational and academic purposes**.
