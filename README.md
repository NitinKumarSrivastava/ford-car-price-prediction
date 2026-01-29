# 🚗 Ford Car Price Prediction

A Machine Learning project that predicts the **selling price of Ford cars** based on vehicle specifications and historical data. The goal is to help buyers, sellers, and dealerships estimate fair market value using data-driven insights.

---

## 📌 Problem

Pricing used cars accurately is challenging because the value of a vehicle depends on multiple factors such as:

* Model type
* Year of manufacture
* Mileage
* Fuel type
* Transmission
* Engine size
* Tax and MPG

Manual pricing often leads to **overpricing or undervaluation**, which can result in:

* Loss of potential buyers
* Reduced profit margins
* Inconsistent pricing strategies

This project solves that problem by building a **predictive machine learning model** that estimates car prices based on historical Ford car data.

---

## ⚙️ Approach

The project follows a structured Data Science workflow:

### 1️⃣ Data Collection

Historical Ford car dataset containing vehicle attributes and their corresponding prices.

### 2️⃣ Data Preprocessing

* Handling missing values
* Encoding categorical features (fuel type, transmission, model, etc.)
* Feature scaling where required
* Outlier analysis and treatment

### 3️⃣ Exploratory Data Analysis (EDA)

* Distribution of car prices
* Impact of mileage, engine size, and age on price
* Correlation analysis between features

### 4️⃣ Feature Engineering

* Car age derived from manufacturing year
* Selection of important predictors influencing price

### 5️⃣ Model Building

Multiple regression-based models were trained and compared:

* Linear Regression
* Ridge / Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor

### 6️⃣ Model Evaluation

Models were evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**

The best-performing model was selected based on overall accuracy and error metrics.

---

## 📊 Results

* The model successfully learned pricing patterns from historical Ford car data.
* Tree-based ensemble models (like Random Forest) provided **strong predictive performance**.
* The system can estimate car prices with low error, making it useful for real-world valuation support.

**Key Outcome:**
A reliable regression model capable of predicting Ford car prices based on vehicle specifications.

---

## 🛠️ Tech Stack

| Category         | Tools & Technologies       |
| ---------------- | -------------------------- |
| Language         | Python                     |
| Data Handling    | Pandas, NumPy              |
| Visualization    | Matplotlib, Seaborn        |
| Machine Learning | Scikit-learn               |
| Model Evaluation | R², MAE, RMSE              |
| Environment      | Jupyter Notebook / VS Code |



