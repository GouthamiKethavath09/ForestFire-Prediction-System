# 🔥 Forest Fire AI Early Warning System

An advanced **Artificial Intelligence-based Forest Fire Prediction and Monitoring System** that uses **Ensemble Machine Learning, Environmental Data, Terrain Features, and Remote Sensing Indicators** to predict forest fire risk in real time.

This project provides an **interactive Streamlit dashboard** with fire probability prediction, heatmap visualization, and risk severity monitoring.

---

# 🌍 Live Application

🔗 Live Link:  
[https://your-streamlit-link.streamlit.app](https://forestfire-prediction-system-hcwvj2bzuxkjcsgmcihdcw.streamlit.app/)


---

# 📌 Project Objective

Forest fires cause severe damage to:

- Environment
- Wildlife
- Human life
- Natural resources

Early prediction helps:

- Prevent disasters
- Enable early response
- Support forest departments
- Improve environmental protection

This system predicts forest fire probability using Machine Learning.

---

# 🧠 Machine Learning Approach

This project uses **Ensemble Learning**, combining multiple powerful models:

### Models Used

- Random Forest Classifier
- XGBoost Classifier
- LightGBM Classifier
- Ensemble Model (Final prediction)

---

# 🎯 Why Ensemble Learning?

Ensemble improves:

- Accuracy
- Stability
- Reliability
- Prediction performance

Final prediction formula:

```
Ensemble Probability = (RandomForest + XGBoost + LightGBM) / 3
```

---

# 📊 Input Features

The model uses environmental and terrain features.

## Environmental Features

- NDVI (Vegetation index)
- Temperature (°C)
- Humidity (%)
- Wind Speed
- Rainfall

## Terrain Features

- Elevation
- Slope
- Aspect

## Engineered Features

- Vegetation Dryness
- Temperature Risk
- Humidity Risk
- Wind Risk
- Rain Risk
- Terrain Risk
- Fire Risk Score

---

# 🖥️ Dashboard Features

The Streamlit dashboard provides:

### 🔥 Fire Probability Prediction

- Real-time prediction
- Probability score
- Risk classification

---

### 🎯 Fire Risk Meter

Visual gauge showing severity level:

- Green → Low
- Yellow → Moderate
- Orange → High
- Red → Extreme

---

### 📍 Live Fire Heatmap

Displays fire risk based on location using map visualization.

---

### 📊 Ensemble Model Comparison Table

Shows prediction from each model:

- Random Forest
- XGBoost
- LightGBM
- Final Ensemble

---

### 🛰️ Satellite Detection Simulation

Displays hotspot detection status.

---

### 📈 Risk Severity Progress Bar

Visual indicator of fire severity percentage.

---

# 🏗️ Project Structure

```
forest-fire-prediction-system/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   ├── scaler.pkl
│   ├── rf_model.pkl
│   ├── xgb_model.pkl
│   ├── lgb_model.pkl
│
└── Notebook/
    └── fire_prediction.ipynb
```



# 📦 Requirements

Main libraries used:

```
streamlit
numpy
pandas
scikit-learn
xgboost
lightgbm
plotly
```

---

# 📈 Machine Learning Workflow

The project follows standard ML pipeline:

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Feature Scaling
5. Model Training
6. Ensemble Creation
7. Model Saving
8. Dashboard Deployment

---


---



---

# 🧪 Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- XGBoost
- LightGBM

### Dashboard

- Streamlit

### Visualization

- Plotly
- Mapbox

---

# 🛰️ Remote Sensing Concept Used

NDVI helps identify:

- Vegetation health
- Dry vegetation
- Fire-prone areas

Lower NDVI = Higher fire risk

---

# 🎯 Risk Classification System

| Probability | Risk Level |
|------------|-------------|
| 0.00 – 0.30 | Low |
| 0.30 – 0.60 | Moderate |
| 0.60 – 0.80 | High |
| 0.80 – 1.00 | Extreme |

---

# 📊 Example Output

The system provides:

- Fire Probability
- Risk Level
- Confidence Score
- Risk Meter
- Heatmap
- Model Comparison Table

---

