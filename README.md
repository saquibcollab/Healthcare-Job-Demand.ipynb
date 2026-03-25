# 🏥 Healthcare Demand & Cost Analysis (ML + NLP + XGBoost)

## 📌 Overview

This project is an end-to-end healthcare analytics solution built using real-world **insurance data**. It combines **machine learning and NLP techniques** to analyze patient trends, predict healthcare demand, and uncover cost patterns.

The project simulates real-world healthcare industry scenarios by integrating structured data with **text-based clinical features**, making it a strong portfolio project for data science and analytics roles.

---

## 🎯 Objectives

* Analyze healthcare cost patterns and patient behavior
* Predict **Demand Score** using machine learning
* Apply **NLP (TF-IDF)** on clinical text data
* Combine structured + unstructured data for modeling
* Generate actionable insights for healthcare trends

---

## 📊 Dataset

* Source: `insurance.csv` (real dataset)
* Records: ~1,300+ entries
* Features:

  * Age
  * BMI
  * Gender
  * Smoking status
  * Region
  * Charges (medical cost)

---

## ⚙️ Feature Engineering

* Created **Demand Score** using domain-inspired logic
* Generated **synthetic clinical notes** for NLP analysis
* Encoded categorical variables using one-hot encoding
* Combined structured and text-based features

---

## 🧠 NLP Processing

* Applied **TF-IDF Vectorization** on clinical notes
* Extracted meaningful numerical features from text
* Integrated NLP features with structured dataset

---

## 🤖 Machine Learning Model

* Model Used: **XGBoost Regressor**
* Tasks:

  * Predict healthcare demand
  * Analyze feature importance
* Evaluation Metrics:

  * R² Score
  * Mean Absolute Error (MAE)

---

## 📈 Key Analysis & Insights

* Smoking and BMI significantly impact healthcare demand
* Higher medical charges correlate with increased demand
* Feature engineering improves predictive performance
* NLP features enhance model understanding of patient context

---

## 📊 Visualization

* Actual vs Predicted demand plots
* Feature importance analysis
* Correlation insights

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* TF-IDF (NLP)

---

## 📁 Project Structure

```bash
Healthcare-Demand-Analysis/
│── data/
│   └── insurance.csv
│── notebooks/
│   └── analysis.ipynb
│── src/
│   └── model.py
│── outputs/
│   ├── charts/
│   └── results/
│── README.md
```

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/healthcare-demand-analysis.git
cd healthcare-demand-analysis
pip install -r requirements.txt
python main.py
```

---

## 🚀 Future Improvements

* Use real clinical text datasets instead of synthetic notes
* Deploy as a **Streamlit web app**
* Implement advanced models (XGBoost tuning, deep learning)
* Add time-series forecasting for demand prediction

---

## 💡 Conclusion

This project demonstrates how combining **machine learning and NLP** can generate deeper insights from healthcare data. It highlights the importance of feature engineering and real-world problem-solving in data science.

---

## 👤 Author

**Your Name**

* GitHub: https://github.com/saquibali
* LinkedIn: https://linkedin.com/in/saquibali
