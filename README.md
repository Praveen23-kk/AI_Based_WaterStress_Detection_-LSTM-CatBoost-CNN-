# Groundwater Level Prediction using LSTM, CNN, and CatBoost

A comparative machine learning study for forecasting post-monsoon groundwater levels.  
This project evaluates three models (LSTM, CNN, and CatBoost) on real groundwater data and analyzes how accurately each predicts observed values.

The goal is to support early detection of groundwater stress, improve resource planning, and assist in water-management decisions.

---

## Key Objectives

- Predict groundwater levels for different regions post-monsoon  
- Compare deep learning models (LSTM, CNN) with CatBoost  
- Identify which model is most accurate and stable across all ranges  

---

## Models Used

| Model   | Type                        | Strength                                      |
|--------|-----------------------------|-----------------------------------------------|
| LSTM   | Deep Learning (Sequential)  | Captures long-term temporal dependencies      |
| CNN    | Deep Learning (1D patterns) | Fast training, robust trend detection         |
| CatBoost | Gradient Boosting        | Handles non-linear data, minimal preprocessing|

---

## Project Structure

```text
📁 groundwater-level-prediction
 ├── data/
 │   └── UPVillageSchedule.csv                   # Input dataset
 ├── notebooks/
 │   └── AI_Based_WaterStress_Detection_(LSTM,CatBoost,CNN).ipynb
 ├── results/
 │   ├── LSTM.png
 │   ├── CNN.png
 │   ├── CatBoost.png
 │   └── All_Models.png
 ├── README.md
 └── requirements.txt

```

#### Observed vs Predicted Results

### Figure 5: LSTM Model (★)
<p align="center">
  <img src="images/LSTM.png" alt="LSTM Model Groundwater Prediction" width="500">
</p>

### Figure 6: CNN Model (●)
<p align="center">
  <img src="images/CNN.png" alt="CNN Model Groundwater Prediction" width="500">
</p>

### Figure 7: CatBoost Model (▲)
<p align="center">
  <img src="images/CatBoost.png" alt="CatBoost Model Groundwater Prediction" width="500">
</p>

### Figure 8: Comparative Observed vs Predicted (All Models)
<p align="center">
  <img src="images/All_Models.png" alt="Comparison of All Models: LSTM, CNN, CatBoost" width="500">
</p>
