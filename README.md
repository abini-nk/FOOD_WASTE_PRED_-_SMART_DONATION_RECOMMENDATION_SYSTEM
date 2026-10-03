# 🍲 Food Waste Prediction & Smart Donation Recommendation System

An end-to-end Machine Learning web application designed to forecast food demand in the hospitality sector, minimize food wastage, and automate surplus food redistribution alerts to nearby charities and NGOs using real-time geocoding APIs.

## 🚀 Key Features

- **Demand Forecasting:** Predicts precise food order demand (`num_orders`) using historical operational data.
- **Machine Learning Pipeline:** Implements **Random Forest Regressor** with hyperparameter tuning via **RandomizedSearchCV** (achieving an $R^2$ Score of **~0.75**).
- **Exploratory Data Analysis (EDA):** Uses **Seaborn** and **Matplotlib** to visualize weekly demand trends, price impacts, promotion distributions, and feature importance.
- **Geocoding API Integration:** Integrates OpenStreetMap's Nominatim API to capture precise geographical coordinates (latitude & longitude) for targeted location alerts.
- **Interactive Dashboard:** Built using **Streamlit** to provide a real-time web interface for evaluating waste thresholds and dispatching NGO alerts.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Machine Learning & Data Science:** Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib, Joblib
- **Web Framework:** Streamlit
- **APIs:** OpenStreetMap Nominatim API (Geocoding)

## 📊 Model Performance

- **Algorithm:** Random Forest Regressor
- **Tuned Parameters:** `n_estimators: 50`, `min_samples_split: 5`, `max_depth: 20`
- **Performance Metric ($R^2$ Score):** 0.757

## 💻 How to Run Locally

Follow these steps to set up and run the project on your local machine:

### 1. Clone the repository
```bash
git clone [https://github.com/abini-nk/FOOD_WASTE_PRED_-_SMART_DONATION_RECOMMENDATION_SYSTEM.git](https://github.com/abini-nk/FOOD_WASTE_PRED_-_SMART_DONATION_RECOMMENDATION_SYSTEM.git)
cd FOOD_WASTE_PRED_-_SMART_DONATION_RECOMMENDATION_SYSTEM
pip install -r requirements.txt
streamlit run app.py
