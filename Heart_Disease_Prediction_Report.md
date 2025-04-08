
# 🫀 Heart Disease Prediction using Machine Learning

## 📘 Project Overview
This project aims to predict the presence of heart disease using multiple machine learning algorithms. The dataset was preprocessed, cleaned, and analyzed using five different models. Each model was evaluated based on training accuracy, test accuracy, and cross-validation accuracy to understand its generalization ability and potential overfitting.

---

## 📊 Dataset Overview
The dataset includes several features related to heart health such as:

- Age, Sex
- Chest Pain Type
- Resting Blood Pressure, Cholesterol
- Fasting Blood Sugar
- Rest ECG, Max Heart Rate
- Exercise Induced Angina, ST Depression (Oldpeak), Slope
- Number of Major Vessels, Thalassemia
- Target: 0 = No Disease, 1 = Disease

Categorical features were encoded using one-hot encoding and the numerical features were standardized using `StandardScaler`. Feature selection was applied to retain the top 10 most relevant features using `SelectKBest`.

---

## 🧠 Machine Learning Models Used

| Model                   | Train Accuracy | Test Accuracy | Cross-Validation Accuracy |
|------------------------|----------------|----------------|----------------------------|
| Support Vector Machine | 91.95%         | 85.85%         | 90.43%                     |
| Random Forest          | 92.93%         | 85.37%         | 90.04%                     |
| Decision Tree          | 91.46%         | 84.39%         | 88.48%                     |
| K-Nearest Neighbors    | 95.49%         | 82.93%         | 88.10%                     |
| Logistic Regression    | 87.07%         | 82.93%         | 86.04%                     |

---

## 📌 Model Performance Analysis

### 📍 Logistic Regression
- **Train Accuracy:** 87.07%
- **Test Accuracy:** 82.93%
- **Cross-Validation Accuracy:** 86.04%
- Performs well with linear decision boundaries.
- Slightly underperforms compared to others in terms of generalization.

### 📍 Decision Tree
- **Train Accuracy:** 91.46%
- **Test Accuracy:** 84.39%
- **Cross-Validation Accuracy:** 88.48%
- Can model complex patterns, but may slightly overfit depending on depth.

### 📍 Random Forest
- **Train Accuracy:** 92.93%
- **Test Accuracy:** 85.37%
- **Cross-Validation Accuracy:** 90.04%
- Excellent balance between bias and variance.
- Feature importance and ensemble nature improve robustness.

### 📍 Support Vector Machine
- **Train Accuracy:** 91.95%
- **Test Accuracy:** 85.85%
- **Cross-Validation Accuracy:** 90.43%
- Consistently high accuracy and strong generalization performance.
- Best performer based on test and CV accuracy.

### 📍 K-Nearest Neighbors
- **Train Accuracy:** 95.49%
- **Test Accuracy:** 82.93%
- **Cross-Validation Accuracy:** 88.10%
- Shows signs of overfitting with high training but lower test accuracy.

---

## ✅ Final Conclusion

- **Best Model Overall:** Support Vector Machine (SVM)
- **Reason:** High test accuracy and the highest cross-validation accuracy, indicating strong generalization with low overfitting.
- **Recommendation:** Use SVM for production-level deployment with further hyperparameter tuning and possibly using grid search or advanced ensemble models for optimization.

---

## 📚 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Try boosting algorithms like XGBoost or LightGBM
- Deploy model using Flask, FastAPI, or Streamlit
- Build interactive dashboards for medical professionals

---

*Project by Suvathi Mariyappan* 
