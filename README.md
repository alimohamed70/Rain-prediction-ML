# 🌦️ Rain Prediction using Machine Learning

This project predicts **whether it will rain tomorrow** based on historical weather data.  
It was built using **Python, Scikit-learn, and Jupyter Notebook** as part of a Machine Learning project.

---

## 📌 Project Overview
- Preprocessed weather data (numeric + categorical features).  
- Built ML pipelines with **ColumnTransformer** and **GridSearchCV**.  
- Trained and compared two models:
  - **Random Forest Classifier**
  - **Logistic Regression**
- Evaluated performance with **classification reports**, **confusion matrices**, and **feature importance plots**.

---

## ⚙️ Technologies Used
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## 📊 Results
### Random Forest Classifier:
- **Accuracy**: ~84%  
- **True Positive Rate (Rain=Yes)**: ~50%  
- **Most important feature**: `Humidity3pm`

### Logistic Regression:
- **Accuracy**: ~83%  
- **True Positive Rate (Rain=Yes)**: ~51%  

✅ **Conclusion**:  
Random Forest achieved slightly higher accuracy, but Logistic Regression had a comparable true positive rate.  
Random Forest is the **better overall predictor** for rainfall in this dataset.

---

## 📈 Visualizations
- Confusion Matrix  
- Feature Importance (Top 20 features)  



