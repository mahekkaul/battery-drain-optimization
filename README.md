# 🔋 Battery Drain Optimization Advisor using Machine Learning

A machine learning-based predictive and advisory system for estimating battery drain and offering actionable optimization tips based on user behavior.

---

## 📌 Project Overview

This project builds a predictive model that estimates daily **battery drain (mAh)** and advises users on how to reduce it based on usage patterns. The model identifies key drivers like screen time and app usage, and provides personalized recommendations using machine learning thresholds.

---

## 🧰 Tools & Technologies

- **Python**
- **Scikit-learn**
- **Random Forest Regressor**
- **Matplotlib, Seaborn**

---

## 🧠 Key Features

✅ Trained a **Random Forest Regressor** with 100 estimators achieving **R² > 0.75**  
✅ Identified **screen time (38%)** and **app usage (29%)** as major contributors using feature importance analysis  
✅ Generated **personalized optimization tips**, like:  
> “Reduce app usage below 5h/day to save 200mAh daily.”  
✅ Validated predictions using **residual plots and error distribution analysis** showing accuracy within ±100–200mAh

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/mahekkaul/battery-drain-optimization.git

2. Open the notebook in Jupyter or Google Colab.

3. . Install required libraries:

pip install scikit-learn matplotlib seaborn pandas

4. Run all cells to train, predict, and view recommendations.

📈 Results
R² Score: > 0.75

Top Features:
Screen Time – 38%
App Usage – 29%
Background Sync – 12%
Device Temperature – 9%

🚀 Future Enhancements
Integrate with a mobile app dashboard

Real-time energy usage tracking

Add deep learning models for improved prediction

📩 Contact
Mahek Kaul | LinkedIn
Email: kaul.mahek@gmail.com
