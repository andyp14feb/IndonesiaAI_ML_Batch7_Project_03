# IndonesiaAI_ML_Batch7_Project_03
This project using data with house pricing information. The analysis will focus on applying prediction technique using Linear Regression, Random Forest and XGBoost
---
Slide / Presentation :
- [pdf](https://github.com/andyp14feb/IndonesiaAI_ML_Batch7_Project_03/blob/main/Project%203%20-%20House%20Predection%20v1.pdf)
- [pptx](https://github.com/andyp14feb/IndonesiaAI_ML_Batch7_Project_03/blob/main/Project%203%20-%20House%20Predection%20v1.pptx)
- [Online Google Slide](https://docs.google.com/presentation/d/e/2PACX-1vRSiPFffjBtV_Yq3uloJ4IAHmPe6Z478uNjAc3ADxD8TjRyKI4lb8MyD3IZtO9bKQ/pub?start=true&loop=true&delayms=3000)
  

# 🏡 AI Generated Summary of the Project File :

## 🎯 Goal
Build an accurate house price prediction model using machine learning, focusing on real-world applicability and reliability.

## ✅ Completed Steps

### 1. 🧹 Data Preprocessing
- Removed potential data leak features
- Handled missing values (mode for categorical, median for numerical)
- Encoded selected categorical columns using `TargetEncoder` and `One Hot Encoding`

### 2. ⚙️ Feature Engineering
- Applied target encoding and one hot encoding to categorical features
- Feature Engineering ( create new features, removing weak correlation features, handling multicolinearity)

### 3. 🤖 Model Training & Evaluation
- Trained baseline models: Linear Regression, Random Forest, XGBoost
- Trained models with Feature Enginered dataset
- Trained models with Hyperparameter Tuned
- Trained a model with ensemble of 2 best of previous models
- Evaluated using RMSE, MAE, MAPE and R2

### 4. 🛠️ Hyperparameter Tuning
- Applied `RandomizedSearchCV` on XGBoost and Random Forest

### 5. 🛠️ Supporting Documents

- [dataDefinision.md](https://github.com/andyp14feb/IndonesiaAI_ML_Batch7_Project_03/blob/main/dataDefinision.md)
- [data_description.txt](https://github.com/andyp14feb/IndonesiaAI_ML_Batch7_Project_03/blob/main/data_description.txt)
- [CategoricalEncodingnyaPakaiApa.xlsx](https://github.com/andyp14feb/IndonesiaAI_ML_Batch7_Project_03/blob/main/CategoricalEncodingnyaPakaiApa.xlsx)
