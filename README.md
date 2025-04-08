
# 🫀 Heart Disease Prediction using Machine Learning

This project focuses on predicting the presence of heart disease using a variety of machine learning algorithms. The dataset is preprocessed, cleaned, and analyzed through multiple models to identify the most accurate and generalizable method for prediction.

---

## 📌 Project Highlights

- Multiple ML models compared:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Cross-validation to measure generalization performance
- Feature selection using `SelectKBest`
- Data scaling using `StandardScaler`
- Visual comparison of model performance
- Clean and structured Jupyter notebook

---

## 📁 Files Included

- `Heart_Disease_Model_Comparison.ipynb` – Main notebook with all code and visualizations
- *(Optional)* `HeartDiseaseTrain-Test.csv` – Dataset used for training and evaluation

---

## 🧠 Dataset

The dataset includes features such as:
- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- ECG Results
- Max Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Vessels Colored by Fluoroscopy
- Thalassemia
- Target (0 = No Disease, 1 = Disease)

---

## 🛠️ Tech Stack

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

---

## 🚀 How to Use

1. Clone the repository:
   ```
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```
   jupyter notebook Heart_Disease_Model_Comparison.ipynb
   ```

---

## 📊 Model Evaluation

Each model is evaluated using:
- Train Accuracy
- Test Accuracy
- Cross-Validation Score
- Classification Report

This helps in identifying overfitting and choosing the best-performing model.

---

## 📬 Contact

For questions or collaboration, feel free to reach out!

---

*Feel free to fork this project, use it in your portfolio, or contribute!*

---

## 📊 Summary of Model Comparison

| Model                   | Train Accuracy | Test Accuracy | Cross-Validation Accuracy |
|------------------------|----------------|----------------|----------------------------|
| Support Vector Machine | 91.95%         | 85.85%         | 90.43%                     |
| Random Forest          | 92.93%         | 85.37%         | 90.04%                     |
| Decision Tree          | 91.46%         | 84.39%         | 88.48%                     |
| K-Nearest Neighbors    | 95.49%         | 82.93%         | 88.10%                     |
| Logistic Regression    | 87.07%         | 82.93%         | 86.04%                     |

> 📌 **Conclusion**: Support Vector Machine performed best overall based on generalization (CV Accuracy) and test accuracy.

👉 [Read the Full Project Report](Heart_Disease_Prediction_Report.md)

---
