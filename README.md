<img width="1189" height="490" alt="download (1)" src="https://github.com/user-attachments/assets/20c8801d-e2e3-4989-9349-7d79d9b4d770" />
<img width="989" height="490" alt="download (2)" src="https://github.com/user-attachments/assets/2fe1dec8-7925-437c-9ed9-bbe2123f64ff" />
<img width="1389" height="989" alt="download" src="https://github.com/user-attachments/assets/0754ab67-615d-4c62-91ba-540ae5a995aa" />

![Uploading Screenshot 2026-10-03 231451.png…]()

# 🍲 Food Waste Prediction & Smart Donation Recommendation System

An end-to-end Machine Learning web application designed to forecast food demand in the hospitality sector, minimize food wastage, and automate surplus food redistribution alerts to nearby charities and NGOs using real-time geocoding APIs.

## 🚀 Key Features

- **Demand Forecasting:** Predicts precise food order demand (`num_orders`) using historical operational data.
- **Machine Learning Pipeline:** Implements **Random Forest Regressor** with hyperparameter tuning via **RandomizedSearchCV** (achieving an $R^2$ Score of **~0.741**).
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

### 2. Install dependencies
```bash
pip install -r requirements.txt
### 3. Run the Streamlit app
```bash
streamlit run app.py
🔮 Future Enhancements
Real-Time Notification Integration: Integrating automated alerts to notify nearby NGOs when surplus food exceeds safety thresholds.

Advanced Geospatial Mapping: Implementing interactive mapping libraries to visually plot charity and donation drop-off locations.

Model Deployment: Deploying the Streamlit web app to cloud platforms for public access.
