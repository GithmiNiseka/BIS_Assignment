# Heart Disease Prediction using Machine Learning  

## Overview  
This project aims to predict heart disease based on medical features such as **age, cholesterol levels, and blood pressure**. The dataset is sourced from the **UCI Machine Learning Repository**, and a **Logistic Regression model** is used to classify the presence of heart disease.  

## Dataset  
- **Source:** [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)  
- **Features:** Age, cholesterol, blood pressure, and other medical attributes  
- **Target Variable:** Presence (1) or absence (0) of heart disease  

## Methodology  
### 1. Data Preprocessing  
- Checked for missing values and removed incomplete rows  
- Handled data inconsistencies for better model performance  

### 2. Exploratory Data Analysis (EDA)  
- **Correlation heatmap:** To identify feature relationships  
- **Boxplots:** To analyze age and cholesterol levels against heart disease  
- **Distribution plots:** To understand the dataset's balance  

### 3. Model Training  
- Selected **Logistic Regression** for classification  
- Split data into **80% training** and **20% testing** sets  
- Trained the model and evaluated its performance  

### 4. Model Evaluation  
- **Accuracy:** 84% on the test set  
- **Confusion Matrix:** Visualized performance of true vs. predicted values  
- **Classification Report:** Precision, Recall, and F1-score for each class  
- **ROC Curve:** Assessed the model’s ability to distinguish between classes  

## Key Findings  
- **Age and cholesterol levels** significantly impact heart disease prediction  
- The **Logistic Regression model performed well**, achieving an accuracy of 84%  
- The **ROC curve analysis** showed a strong model performance with an **AUC above 0.8**  

## Future Improvements  
- Exploring **advanced models** such as **Random Forest or SVM**  
- **Hyperparameter tuning** for better performance  
- Including additional features such as **lifestyle habits and family history**  

## Conclusion  
This project demonstrates the potential of **machine learning in predicting heart disease**. While the Logistic Regression model performed well, further improvements could be made by testing other models and incorporating more features.  
