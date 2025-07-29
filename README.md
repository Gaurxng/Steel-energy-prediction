# Steel-energy-prediction

This project focuses on predicting energy usage in the steel manufacturing industry using regression-based machine learning techniques. The dataset contains detailed process parameters collected from an industrial steel production line.

The aim is to develop an interpretable and accurate model that forecasts energy consumption, helping industries monitor and optimize their operations.

---

## 🔍 Problem Statement

Energy efficiency is a major concern in industrial manufacturing. The steel industry, being highly energy-intensive, can greatly benefit from predictive insights. This project addresses:

- What process variables most influence energy consumption?
- Can we predict energy usage using machine learning models?
- How accurate can our predictions be?

---

## 🧠 Machine Learning Techniques Used

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **ElasticNet Regression**
- **Support Vector Regression (SVR)**
- **Decision Tree Regression**
- **Random Forest Regression**

Models were evaluated using R² scores and cross-validation.

---

## 📊 Dataset

- **Source**: Public dataset containing operational data from steel production lines
- **Size**: 500+ observations with 10+ numerical features
- **Target Variable**: Energy consumption (in MJ or kWh)

Key features include:
- Furnace temperature
- Load, cooling efficiency
- Non-linear interactions between control systems

---

## 🛠 Workflow

1. **Data Loading & Preprocessing**
   - Missing value treatment
   - Feature scaling using `StandardScaler`
   - Exploratory Data Analysis (EDA)

2. **Model Training & Evaluation**
   - Multiple regression models trained
   - Cross-validation for stability
   - Feature importance analysis

3. **Visualization**
   - Heatmaps for correlation
   - Actual vs. Predicted plots
   - Coefficients comparison across models

---

## ✅ Results

- Random Forest and Ridge Regression yielded the best results
- Identified top features impacting energy usage
- Demonstrated practical potential for real-time industrial monitoring

---

## 📌 Key Tools & Libraries

- Python 3.x
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`

---

## 👨‍💻 Author

**Gaurang Palekar**  

---

