# 🎥 ML Video Transcoding Time Analysis

## 🎯 Objectives

* Analyze the relationship between video features and transcoding time
* Build a baseline machine learning model (Linear Regression)
* Improve prediction using Random Forest Regressor
* Explain model predictions using SHAP (Explainable AI)
* Create an interactive dashboard using Tableau

---

## 📂 Dataset

* Dataset: YouTube Video Transcoding Dataset
* Features include:

  * Duration
  * Bitrate
  * Resolution (Width & Height)
  * Frames
  * Codec
  * Frame Rate
* Target Variable:

  * Transcoding Time

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* SHAP (Explainable AI)
* Tableau (Dashboard Visualization)

---

## 🧠 Machine Learning Models

### 🔹 Baseline Model

* Linear Regression

### 🔹 Advanced Model

* Random Forest Regressor

---

## 📊 Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## 📈 Dashboard

The Tableau dashboard provides insights into:

* Duration vs Transcoding Time
* Bitrate vs Transcoding Time
* Frames vs Transcoding Time
* Resolution vs Transcoding Time
* Codec vs Average Transcoding Time

📌 Interactive filters are included for better analysis.

---

## 🔍 Key Insights

* Transcoding time increases with video duration
* Higher bitrate leads to higher processing time
* Resolution significantly impacts performance
* Codec type affects computational complexity

---

## 🔬 Explainable AI (SHAP)

SHAP (SHapley Additive Explanations) is used to understand the contribution of each feature to the model predictions. It helps in identifying the most influential factors affecting transcoding time.

---

## 🚀 Future Scope

* Apply deep learning models for better prediction
* Extend to digital forensics for detecting edited or manipulated videos
* Implement real-time prediction systems
* Improve dashboard with advanced analytics
