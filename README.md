# 💧 Water Quality Prediction - RMS

This project aims to predict multiple water quality parameters using machine learning techniques, specifically `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month **AICTE Virtual Internship** sponsored by **Shell** in **June 2025**.

---

## 🌍 Overview

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can help in early detection of pollution and ensure timely intervention.

In this project, we:

- Collected and preprocessed real-world water quality datasets  
- Applied supervised machine learning for **multi-target regression**  
- Built a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`  
- Evaluated the model using standard regression metrics  

---

## 🔧 Technologies Used

- **Python 3.12**  
- **Pandas, NumPy** – Data handling  
- **Scikit-learn** – ML modeling and evaluation  
- **Matplotlib, Seaborn** – Data visualization  
- **Google Colab** – Cloud-based notebook for development and testing  

---

## 🔬 Predicted Water Quality Parameters

The model predicts the following physicochemical water quality indicators:

- NH₄ (Ammonium)  
- BOD₅ (BSK5 - Biochemical Oxygen Demand)  
- Colloids  
- O₂ (Dissolved Oxygen)  
- NO₃ (Nitrate)  
- NO₂ (Nitrite)  
- SO₄ (Sulfate)  
- PO₄ (Phosphate)  
- Cl (Chloride)  

---

## 📈 Model Performance

The model was evaluated using:

- **R² Score**  
- **Mean Squared Error (MSE)**  

Performance was found acceptable across all predicted parameters, showing the model’s effectiveness in environmental quality forecasting.

---

## 🏫 Internship Details

- **Internship Type**: AICTE Virtual Internship – Edunet Foundation  
- **Sponsor**: Shell  
- **Duration**: June 2025 (1 month)  
- **Focus Area**: Machine Learning in Environmental Monitoring  

---

## 🙋‍♀️ Author

**Divya Ramnani**  
B.Tech – Data Science, IPS Academy  
Aspiring AI/ML engineer passionate about building solutions for sustainability and public welfare.

---

## ✅ Note

This project was implemented using **Google Colab** for easy access, experimentation, and model deployment.  
