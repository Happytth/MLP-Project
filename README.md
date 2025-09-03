# Engage2Value: Purchase Value Prediction from Multi-Session Digital Behavior

This repository contains the code and analysis for the **Engage2Value: From Clicks to Conversions** machine learning competition project, completed as part of the *Machine Learning Practice Theory* course.

---

## 📌 Project Overview
The objective of this project is to **predict customer purchase value** during user sessions on a digital commerce platform.  

The dataset includes multi-session behavioral data, device information, marketing sources, and geographic indicators. By modeling these complex user patterns, this project aims to accurately forecast purchase amounts to support:
- Marketing optimization
- Customer value forecasting

---

## 📊 Dataset Description
The dataset consists of anonymized session-level records with features such as:

- **User engagement metrics**: `totalHits`, `pageViews`, `bounces`, `new_visits`
- **Session sequencing & timings**: `sessionNumber`, `sessionStart`
- **Device & browser attributes**: `deviceType`, `os`, `browser`, `screenSize`
- **Marketing & traffic source details**: `userChannel`, `trafficSource`, `adwordsClickInfo`
- **Geographical context**: `geoNetwork.city`, `locationCountry`, `geoNetwork.continent`
- **Unique identifiers**: `userId`, `sessionId`

**Target variable:**  
`purchaseValue` — the amount spent by the customer in a session.

---

## ⚙️ Model and Approach
1. **Exploratory Data Analysis (EDA)**  
   - Studied distributions, correlations, and anomalies  
   - Derived insights to guide feature creation  

2. **Feature Engineering**  
   - Extracted behavioral, temporal, and categorical interaction features  

3. **Preprocessing Pipelines**  
   - Missing value imputation  
   - Encoding (OHE & target encoding)  
   - Feature scaling  

4. **Models Used**  
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor  

5. **Model Tuning & Evaluation**  
   - Hyperparameter tuning with `RandomizedSearchCV`  
   - Evaluated with `r2_score` (as per competition guidelines)  

**Best Result:**  
Achieved **R² = 0.82**, ranking **#1** on the leaderboard 🏆  
Received an **S grade** for the course project.

---

## 📈 Results
- Robust preprocessing pipeline  
- Strong performance on both baseline and advanced models  
- Insights into multi-session digital behavior and purchase prediction  

---

## 🙏 Acknowledgements
- Dataset & competition hosted on **Kaggle**  
- Thanks to instructors and peers from the *Machine Learning Practice Theory* course for their guidance  

---

## 📬 Contact
For questions, suggestions, or collaboration:  
🔗 [LinkedIn – Soubhagya Nayak](https://www.linkedin.com/in/soubhagya-nayak-27b9b72a7/))

---

✨ *Happy Creating!* ✨
