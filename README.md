# 🌧️ Rainfall Prediction Classifier (Final Project)

This project builds and optimizes a rainfall prediction classifier using machine learning. The dataset used comes from the **Australian Government's Bureau of Meteorology** and includes various weather-related features. The goal of the project is to predict whether it will rain tomorrow based on historical weather data.

---

## 📌 **Objective**
The goal of this project is to:
- Explore and perform feature engineering on real-world weather data.
- Build a classifier pipeline and optimize it using **Grid Search Cross-Validation**.
- Evaluate the model using key performance metrics and visualizations.
- Compare the performance of **RandomForestClassifier** and **LogisticRegression** models.
- Use an appropriate set of parameters to fine-tune both models.

---

## 📊 **Dataset**
- Source: [Australian Government Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/)  
- Additional data from Kaggle: [Weather Dataset](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/)  

### **Features include:**
- Temperature, humidity, wind speed, cloud cover, and atmospheric pressure at different times of the day.
- Binary target variable (`RainToday`) indicating whether it rained that day.

---

## 🚀 **Methodology**
### 1. **Data Preprocessing**
- Missing values handled with imputation.
- Categorical variables encoded using **One-Hot Encoding**.
- Numerical variables scaled using **Standard Scaler**.

### 2. **Model Training**
- Built a pipeline combining preprocessing and model training.
- Trained two models:
   - **RandomForestClassifier**
   - **LogisticRegression**
- Tuned hyperparameters using **Grid Search CV**.

### 3. **Model Evaluation**
- Performance measured using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
- Confusion matrix used to visualize performance.

---

## 🔎 **Results & Insights**
### **Random Forest Classifier**:
- **Accuracy:** 84%  
- **True Positive Rate:** 51%  
- Performed slightly better in overall accuracy and recall.

### **Logistic Regression**:
- **Accuracy:** 83%  
- **True Positive Rate:** 51%  
- Performed almost equally well but was slightly worse at identifying rain events.  

### **Key Takeaway:**
- The Random Forest model performed slightly better overall, but both models struggled with predicting rain events due to class imbalance.

---

## 🛠️ **Next Steps**
- Improve recall using:
  - **Class Weighting**  
  - **Oversampling (SMOTE)**  
  - **Threshold Adjustment**  
- Try other classification models like **Gradient Boosting** or **XGBoost**.  

---

## 💼 **Connect with Me**
Feel free to connect with me on LinkedIn and check out my other projects on GitHub:

- **[LinkedIn](https://www.linkedin.com/in/samherd)**  
- **[GitHub](https://github.com/SamHerd)**  

---

### ⭐ If you find this useful, consider giving the repo a star!
