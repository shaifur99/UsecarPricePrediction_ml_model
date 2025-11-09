# 🚗 Used Car Price Prediction - Machine Learning Project

## 📌 Project Overview
This project uses **Machine Learning** to predict the price of a used car based on features such as mileage, engine, power, years used, seats, and kilometers driven.  
It helps **car dealerships, buyers, and businesses** in the used car market make informed decisions.

---

## 📍 Problem Statement
The goal is to build a predictive model that estimates the **price of a used car** given its features, enabling better pricing, buying, and selling decisions.

---

## 🧠 Solution Approach
- Preprocess the dataset by handling missing values, encoding categorical features, and scaling numeric features.  
- Train and evaluate multiple Machine Learning models:
  - **Linear Regression**  
  - **Lasso Regression**  
  - **Ridge Regression**  
  - **Decision Tree Regressor**  
  - **Random Forest Regressor**  
  - **Extra Trees Regressor**  
- Compare model performance to select the best-performing model.

---

## 📊 Observations
- **Manufacturer Location** has the highest influence on car price.  
- **Years Used** negatively affects the price (older cars are cheaper).  
- **Mileage, Engine, and Power** significantly impact the price.  
- **Number of Seats** slightly affects the price.  
- **Kilometers Driven** has relatively low impact on price.

---

## 💡 Business Insights
- **Car dealerships** can set competitive prices for used cars.  
- **Buyers** can estimate fair car value before purchase.  
- **Businesses** can optimize operations using predictive insights.

---

# Developed by

Md. Shaifur Rahman
📧 Email: shaifur22103199@gmail.com

## ⚙️ Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn  
- **Models Used:** Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, Extra Trees  

---

## 📈 Model Performance

| Model                  | Training Score | Testing Score |
|------------------------|----------------|---------------|
| Linear Regression       | ~0.68          | ~0.65         |
| Lasso Regression        | ~0.56          | ~0.56         |
| Ridge Regression        | ~0.70          | ~0.72         |
| Decision Tree Regressor | ~0.99          | ~0.81         |
| Random Forest Regressor | ~0.98          | ~0.91         |
| Extra Trees Regressor   | Used for Feature Importance |

👉 **Random Forest Regressor performed the best** with ~91% accuracy on test data.

---

## 🚀 How to Run the Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Price-Prediction-for-Used-Cars.git
   cd Price-Prediction-for-Used-Cars

# Install dependencies:

pip install -r requirements.txt


# Run the Jupyter Notebook or Python script:

python car_price_prediction.py

# 📂 Project Structure
    ├── data/                       # Dataset (CSV file)
├── notebooks/                  # Jupyter notebooks
├── models/                     # Saved models
├── car_price_prediction.py     # Main script
├── requirements.txt            # Dependencies
└── README.md                   # Project documentation
