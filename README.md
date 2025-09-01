# 🏨 Hotel Booking Demand Prediction  

A machine learning project focused on analyzing hotel booking data to uncover patterns, engineer meaningful features, and build predictive models that provide actionable business insights.  

---

## 📌 Project Overview  

This project explores a real-world hotel booking dataset with the goal of **predicting booking demand** and understanding **customer behavior**.  
The workflow covers the complete machine learning pipeline — from **data cleaning and preprocessing** to **feature engineering** and **dataset preparation**.  

Key questions addressed:  
- What factors influence booking cancellations?  
- How do guest demographics affect demand?  
- Which features are most valuable for predicting customer behavior?  

---

## ⚙️ Methodology  

### **Phase 1 – Data Cleaning**  
- Handled missing values, duplicates, and anomalies.  
- Standardized column names and ensured consistent data types.  
- Prepared a reliable dataset for downstream analysis.  

### **Phase 2 – Exploratory Data Analysis (EDA)**  
- Visualized booking trends over time, hotel types, and guest segments.  
- Explored correlations between variables and booking outcomes.  
- Identified seasonal effects and market segment dynamics.  

### **Phase 3 – Feature Engineering & Preprocessing**  
- Engineered new features:  
  - `total_guests = adults + children + babies`  
  - `total_nights = stays_in_weekend_nights + stays_in_week_nights`  
  - `is_family` flag for bookings with children or babies  
- Applied **One-Hot Encoding** for categorical variables (e.g., meal, market segment).  
- Applied **Frequency Encoding** for high-cardinality variables (e.g., country).  
- Removed data leakage sources (e.g., `reservation_status`, `reservation_status_date`).  
- Finalized dataset with a **train-test split** for model development.  

---

## 📊 Results  

- **Training set:** 69,901 samples × 252 features  
- **Test set:** 17,476 samples × 252 features  

The dataset is now fully prepared for predictive modeling, allowing the next phase: experimenting with machine learning algorithms to forecast booking demand.  

