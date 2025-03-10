# **Kaggle Rainfall Prediction 🌧️**
### **Predicting Daily Rainfall Probabilities using Machine Learning**

## 📌 **Overview**
This repository contains a **machine learning pipeline** for predicting daily rainfall probabilities as part of the **Kaggle Playground Series - Season 5, Episode 3** competition. The model is trained using weather-related features such as **temperature, humidity, wind speed, and pressure** to classify the probability of rainfall.

## 🚀 **Dataset**
The dataset is provided by Kaggle and consists of:
- **train.csv** - Contains historical weather data with rainfall labels (1 = Rain, 0 = No Rain).
- **test.csv** - Contains weather data for which we need to predict rainfall probabilities.
- **sample_submission.csv** - A template for the expected output format.

## 📊 **Model & Approach**
- **Preprocessing:**
  - Missing values are handled using mean imputation.
  - Features are standardized using `StandardScaler` for better model performance.

- **Model:**
  - Uses a **Random Forest Classifier** for classification.
  - Evaluates performance using **ROC-AUC Score**.

- **Submission Format:**
  - The script generates a submission file `submission.csv` with `id` and `rainfall` probability.

## 🏆 **Results**
- The current model achieves a **validation AUC score of ~0.857**.
- Further improvements can be made using **feature engineering, hyperparameter tuning, and ensemble models**.


## 🏗 **Future Improvements**
- Try **Gradient Boosting (XGBoost, LightGBM)** for better performance.
- Feature selection and engineering for more robust predictions.
- Implement ensemble methods and stacking models.

## 💌 **Contributions**
Feel free to fork the repository and make improvements! If you have any questions or suggestions, open an issue or reach out. 🚀
