# UsecarPricePrediction_ml_model

# 🚗 Price Prediction for Used Cars - Machine Learning Project  

This project uses **Machine Learning** to predict the price of a used car based on various features such as mileage, engine, power, years used, seats, and kilometers driven.  

---

## 📍 Problem Statement
The goal of this project is to build a predictive model that estimates the price of a used car given its features. This helps car dealerships, buyers, and businesses in the used car market make more informed decisions.

---

## 🧠 Solution Approach
- The dataset of historical car sales data is preprocessed by handling missing values, feature encoding, and scaling.  
- Multiple Machine Learning models are trained and evaluated:
  - Linear Regression  
  - Lasso Regression  
  - Ridge Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - Extra Trees Regressor  

The performance of each model was compared to select the best-performing one.

---

## 📊 Observations
- **Manufacturer Location** has the highest influence on car price.  
- **Years Used** negatively affects the price (older cars are cheaper).  
- **Mileage, Engine, and Power** have a significant impact on the price.  
- **Number of Seats** slightly affects the price.  
- **Kilometers Driven** has relatively low impact on the price.  

---

## 💡 Insights
- **Car dealerships** can set more competitive prices for used cars.  
- **Buyers** can estimate a fair value for cars before purchasing.  
- **Businesses** in the automobile market can optimize operations based on predictive insights.  

---

## ⚙️ Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn  
- **Models Used:** Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, Extra Trees  

---

## 📈 Model Performance

| Model                  | Training Score | Testing Score |
|-------------------------|----------------|---------------|
| Linear Regression       | ~0.68          | ~0.65         |
| Lasso Regression        | ~0.56          | ~0.56         |
| Ridge Regression        | ~0.70          | ~0.72         |
| Decision Tree Regressor | ~0.99          | ~0.81         |
| Random Forest Regressor | ~0.98          | ~0.91         |
| Extra Trees Regressor   | Used for Feature Importance |

👉 **Random Forest Regressor performed the best** with ~91% accuracy on test data.

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/Price-Prediction-for-Used-Cars.git
   cd Price-Prediction-for-Used-Cars
Install the required libraries

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook / Python script


bash
Copy code
python car_price_prediction.py
📂 Project Structure
bash
Copy code
├── data/                       # Dataset (CSV file)
├── notebooks/                  # Jupyter notebooks
├── models/                     # Saved models
├── car_price_prediction.py     # Main script
├── requirements.txt            # Dependencies
└── README.md                   # Project documentation
📜 License
This project is open-source and free to use for learning and research purposes.

👨‍💻 Developed by Md. Shaifur Rahman
📧 Email: shaifur22103199@gmail.com
