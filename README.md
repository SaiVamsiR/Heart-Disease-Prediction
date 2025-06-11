# ❤️ Heart Disease Prediction Using KNN & Random Forest

## 🏥 Overview
This repository contains a machine learning project that predicts **heart disease** using **K-Nearest Neighbors (KNN)** and **Random Forest Classifier**. Early detection can help doctors and patients take preventive action and improve health outcomes. 💡

## 📊 Dataset
The dataset includes important patient information:

| Feature | Description |
|---------|------------|
| 🕰 **Age** | Patient's age |
| 🚻 **Sex** | Gender (0 = female, 1 = male) |
| ❤️ **CP** | Chest pain type (categorical) |
| 🩸 **Trestbps** | Resting blood pressure (mm Hg) |
| 🍽 **Chol** | Serum cholesterol level (mg/dl) |
| 🍬 **FBS** | Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false) |
| 📈 **Restecg** | Resting electrocardiographic results |
| 💓 **Thalach** | Maximum heart rate achieved |
| 🏃 **Exang** | Exercise-induced angina (1 = yes, 0 = no) |
| ⛰ **Oldpeak** | ST depression induced by exercise relative to rest |
| 📉 **Slope** | Slope of peak exercise ST segment |
| 🔢 **CA** | Number of major vessels colored by fluoroscopy |
| 🔍 **Thal** | Thalassemia diagnosis (categorical) |
| 🎯 **Target** | Heart disease presence (1 = disease, 0 = no disease) |

## 🛠 Dependencies
Install the required packages before running the project:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🏗 Model Training
The prediction model follows these key steps:
1. 🧹 **Data Preprocessing** – Handling missing values, encoding categorical variables, and scaling numerical features.
2. 🔍 **Feature Selection** – Identifying the most relevant variables.
3. 🤖 **Model Training** – Using KNN and Random Forest Classifier for prediction.
4. 📏 **Evaluation Metrics** – Accuracy, precision, recall, F1-score, and ROC curve.

## 📈 Results
The model provides predictions with insights into heart disease risk, including:
- ✅ **Confusion Matrix**
- 📊 **ROC Curve**
- 📌 **Feature Importance Analysis**

## 🔮 Future Improvements
Enhancements to explore:
- 🛠 **Hyperparameter tuning** for better accuracy
- 🏆 **Alternative classification models**
- 📡 **Integration with real-time patient data**

## 💡 Contributing
Feel free to fork the repository and submit pull requests with improvements. 🚀
