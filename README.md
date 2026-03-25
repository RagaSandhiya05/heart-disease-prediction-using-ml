# 🫀 Heart Disease Prediction using Machine Learning 

## 📌 Overview

This project focuses on predicting the presence of heart disease using various Machine Learning and Deep Learning algorithms. The system analyzes medical attributes such as age, cholesterol level, blood pressure, and other clinical features to determine whether a patient is at risk.

The goal is to build an accurate and reliable predictive model that can assist in early diagnosis and healthcare decision-making.



## 🎯 Objectives

* To predict heart disease using patient health data
* To compare multiple Machine Learning models
* To evaluate model performance using different metrics
* To identify the best-performing algorithm



## 📊 Dataset

* Total Records: **1025**
* Features: **13 input features + 1 target**
* Target:

  * **1 → Heart Disease Present**
  * **0 → No Heart Disease**

### 🧾 Features Used

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thal



## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Matplotlib



## 🧠 Algorithms Used

### 🔹 Machine Learning Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

### 🔹 Deep Learning Model

* Artificial Neural Network (ANN)



## 📈 Evaluation Metrics Used

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics help measure not only correctness but also how well the model handles false positives and false negatives.



## 🏆 Model Performance Comparison

| Model               | Test Accuracy           |
| ------------------- | ----------------------- |
| Logistic Regression | 80.48%                  |
| KNN                 | 72.19%                  |
| Decision Tree       | 85.85%                  |
| Random Forest       | 91.70%                  |
| SVM                 | 70.73%                  |
| XGBoost             | **95.61% 🔥 (Highest)** |
| ANN                 | 95.12%                  |



## 🥇 Best Model

* ✅ **XGBoost achieved the highest accuracy: 95.61%**
* It also performed well in:

  * Precision
  * Recall
  * F1 Score

👉 Hence, XGBoost is selected as the best model for heart disease prediction in this project.



## 🔍 Key Observations

* Ensemble models like Random Forest and XGBoost performed better than basic models
* KNN and SVM showed lower performance due to lack of feature scaling/tuning
* ANN achieved high accuracy but showed poor confusion matrix results (class imbalance issue)
* Logistic Regression performed reasonably well as a baseline model



## ⚠️ Challenges Faced

* Convergence warning in Logistic Regression
* ANN model overfitting / prediction imbalance
* Need for feature scaling in some models



## 🔮 Future Improvements

* Hyperparameter tuning for better performance
* Feature scaling for all models
* Deploy using Streamlit or Flask
* Use larger real-world datasets
* Improve ANN architecture



## 💡 Conclusion

This project demonstrates how different Machine Learning and Deep Learning algorithms can be applied to healthcare data. Among all models, **XGBoost provided the best performance**, making it the most suitable choice for heart disease prediction.

---

## 👩‍💻 Author

**Your Name**
