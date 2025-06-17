![banner](assets/banner.png)

Banner [source](https://banner.godori.dev/)

![Python version](https://img.shields.io/badge/Python%20version-3.10%2B-lightgrey)
![GitHub last commit](https://img.shields.io/github/last-commit/adin11/finalscore-insight)
![Type of ML](https://img.shields.io/badge/Type%20of%20ML-Regression-blue)
![License](https://img.shields.io/badge/License-MIT-green)
[![Streamlit App](https://img.shields.io/badge/Deployed%20with-Streamlit-ff4b4b)](https://finalscore-insight.streamlit.app)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# 🏏 FinalScore Insight – IPL First Innings Score Predictor

#### 🔗 App Link: [Live App on Streamlit](https://finalscore-insight.streamlit.app)

---

## 🧠 Overview

A real-time IPL first-innings score predictor that leverages machine learning and advanced data analysis to estimate match scores dynamically. The app considers current match context—runs, wickets, overs, recent 5-over performance—and provides accurate score forecasts with a user-friendly interface. Designed to assist analysts, fans, and strategists during live IPL matches.

---

## ⚙️ Tech Stack

- Python (3.10+)
- Pandas, Numpy, Matplotlib, Seaborn
- Streamlit (for interactive UI)
- Scikit-learn (for modeling and evaluation)
- RandomForestRegressor (final model)

---

## 📊 Key Features

🔹 **Data Preparation & EDA**  
Cleaned and pre-processed historical IPL match data. Conducted exploratory data analysis to detect trends and distributions.  

🔹 **Feature Engineering & Encoding**  
Handled multicollinearity using Variance Inflation Factor (VIF). Encoded categorical features like teams, venues using One-Hot Encoding.  

🔹 **Model Training & Optimization**  
Implemented a modular training function. Tuned RandomForestRegressor using cross-validation and hyperparameter tuning to enhance predictive accuracy.  

🔹 **Evaluation & Error Analysis**  
Used metrics like R², MAE, and RMSE. Visualized prediction errors and assessed margin of error across match types.  

🔹 **Performance Summary**  
Achieved R² score of **0.92**. Identified that **5.56%** of matches had an average error margin of **>10%**, informing further model improvements.  

---

## 📈 Sample Predictions

- Input: 92 Runs, 10.3 Overs, 3 Wickets, 5-over runs = 38  
- **Predicted Score:** 181 Runs  

- Input: 56 Runs, 7.2 Overs, 2 Wickets, 5-over runs = 24  
- **Predicted Score:** 146 Runs  

---

## 🚀 Future Improvements

- Include live API for real-time match integration  
- Add second innings chase projections  
- Improve predictions for extreme match scenarios (e.g., rain-affected innings)

---

> 🎯 **FinalScore Insight combines smart data science and real-time cricket action, giving fans and analysts a tactical edge during live IPL matches.**
