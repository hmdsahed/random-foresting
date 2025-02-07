**Performance Evaluation of Machine Learning and Deep Learning Models for Extreme Climate Event Forecasting**

**📌 Overview**
This repository contains the complete implementation and analysis for my research on predicting extreme weather events using Machine Learning and Deep Learning models. The study explores multiple datasets, including large-scale weather data, extreme weather events, and tornado path datasets, to evaluate the performance of Random Forest, XGBoost, and LSTM in forecasting severe climate conditions.

**📂 Datasets Used**
The research is based on three primary datasets:

1️⃣ Large-Scale Weather Dataset

Covers 6.3 million weather events across 49 U.S. states (2016–2020).
Captures extreme weather conditions like storms, hail, fog, snow, and severe cold.
Data collected from 2,071 airport-based weather stations.

2️⃣ NOAA Tornado Path Dataset

Contains 16,000 tornado records with path details, severity, and property damage.
Includes geospatial attributes tracking storm start & end locations.

3️⃣ Extreme Weather Dataset

Focuses on high-impact storms, extreme temperature shifts, and severe weather conditions.
Provides attributes such as wind speed, precipitation, temperature deviations, and storm severity.

**⚙️ Methodology**
**📌 Data Preprocessing & Feature Engineering**
Handled missing values by applying median imputation.
Converted timestamps into event duration to quantify storm intensity.
Encoded categorical variables using Label Encoding.
Standardized numerical features for better model performance.
**📌 Models Implemented**
This study evaluates three models for extreme weather event classification and regression:

**✅ Random Forest – An ensemble learning model using multiple decision trees.**

**✅ XGBoost – An optimized gradient boosting model for structured data.**

**✅ LSTM (Long Short-Term Memory) – A deep learning model designed for time-series prediction.**

Each model was trained and evaluated on multiple datasets to assess accuracy, MAE, RMSE, and R² Score.

**Citation & Acknowledgments:**

If you use this research or code, please cite it as follows:

Haris Md Sahed, "Performance Evaluation of Machine Learning and Deep Learning Models for Extreme Climate Event Forecasting", 2025.
