# Logistic Regression – Airline Customer Satisfaction Prediction

## 📊 Project Overview
This project applies **Logistic Regression** to passenger survey data to predict whether a customer is **Satisfied** or **Neutral/Unsatisfied**.  
We use Python and Scikit-learn to preprocess data, encode categorical variables, fit a binomial logistic regression model, and evaluate performance with precision and recall.

---

## 🎯 Goal
- Preprocess and encode features for classification.  
- Fit a Logistic Regression model with train/test validation.  
- Evaluate performance using Confusion Matrix, Precision, Recall.  
- Identify key drivers of satisfaction.  
- Provide actionable recommendations for improving customer retention.

---

## 🗂 Dataset
- **Source:** `Invistico_Airline.csv`  
- **Target Variable:** `satisfaction` (Satisfied vs. Neutral/Unsatisfied)  
- **Predictors:** Passenger demographics, flight service ratings, onboard experience, etc.

---

## 🔧 Workflow
1. Load and inspect dataset.  
2. Encode categorical variables using Label Encoding.  
3. Split data into training/testing sets.  
4. Scale features for logistic regression.  
5. Fit Logistic Regression model.  
6. Evaluate with Confusion Matrix, Precision, Recall.  
7. Interpret coefficients to identify satisfaction drivers.  
8. Provide business recommendations.

---

## 📈 Key Results (example placeholders – replace with your run outputs)
- **Confusion Matrix:**  
  - True Positives: 1200  
  - True Negatives: 950  
  - False Positives: 300  
  - False Negatives: 250  

- **Precision:** 0.79  
- **Recall:** 0.83  
- **F1-score:** 0.81  

- **Top Positive Drivers:** In-flight Wi-Fi, Seat Comfort, Onboard Service.  
- **Top Negative Drivers:** Flight Delay, Baggage Handling.

---

## ✅ Business Recommendation
- Invest in improving **Wi-Fi quality** and **seat comfort** to increase satisfaction probability.  
- Reduce **flight delays** and improve **baggage handling** to minimize dissatisfaction.  
- These actions can directly improve customer retention and loyalty.

---

## 📌 Environment Setup
Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
