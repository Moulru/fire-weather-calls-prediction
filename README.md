# Fire & Weather Emergency Call Prediction

Predicting 119 emergency call volumes by integrating fire incident data with weather big data.  
(기상청 2025 날씨 빅데이터 콘테스트 주제2)

## 📌 Project Description

This project forecasts emergency 119 call volumes by analyzing patterns from fire incident records and comprehensive weather data. We leverage temperature, humidity, wind, and categorical fire-related features to enhance prediction accuracy. The final prediction model is an ensemble of three powerful gradient boosting models, aiming to improve emergency preparedness and resource allocation.

## 📊 Data Sources

- Fire incident data from fire departments or open public data portals  
- Weather data from national meteorological services (e.g., KMA, NOAA)

## 🔍 Key Features

- Data preprocessing and integration of multiple datasets  
- Handling of missing values and categorical encoding tailored for each model  
- Feature engineering from temporal and weather variables  
- Ensemble modeling using CatBoost, XGBoost, and LightGBM to boost prediction performance  
- Weighted average ensemble with weights: CatBoost (40%), XGBoost (30%), LightGBM (30%)  
- Log-transformation of target variable for better regression fit  
- Prediction output post-processing including grouping and averaging

## 🛠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn, CatBoost, XGBoost, LightGBM)  
- Jupyter Notebook  
- Matplotlib / Seaborn for visualization

## 📁 Project Structure

/code  
/data  
/검증기록  

## 🗓 Project Duration

June 2, 2025 – June 22, 2025

## 👥 Team Members

- Junho Park  
- Sangho Byun  
- Jihun Han  
- Seongwan Cho  
- Jinui Jeong
