# Smartphone Price Range Classifier

This project predicts the **price range of smartphones** based on their specifications using the **Mobile Price Classification Dataset** from Kaggle.

## 📖 Project Overview

Smartphone prices vary greatly based on hardware features like RAM, battery power, and screen resolution. This project uses **Logistic Regression** to classify smartphones into one of four price ranges:

- **0:** Low cost  
- **1:** Medium cost  
- **2:** High cost  
- **3:** Very high cost  

The model is trained using standard machine learning techniques including **data preprocessing, feature scaling, train-test splitting**, and **evaluation metrics**.

## 🗂 Dataset

- Source: [Kaggle Mobile Price Classification](https://www.kaggle.com/iabhishekofficial/mobile-price-classification)  
- Contains **2000 rows** of smartphone features with the target column `price_range`.  
- Features include: battery power, RAM, screen resolution, camera megapixels, and more.

## 🛠 Tools & Libraries

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## 💻 Methodology

1. **Data Loading & Exploration**  
   - Inspect dataset shape, info, missing values, and class distribution.

2. **Data Preprocessing**  
   - Split data into features `X` and target `y`.  
   - Train-test split (80% train, 20% test).  
   - Standardize features using `StandardScaler`.

3. **Modeling**  
   - Logistic Regression is used to classify smartphones into price ranges.  
   - Trained on scaled training data.

4. **Evaluation**  
   - Accuracy score  
   - Classification report (precision, recall, F1-score)  
   - Confusion matrix visualization

## 📊 Results

- Accuracy on test set: ~**[add your result]%**  
- Confusion matrix shows model performance across all classes.

## 🔍 Key Insights

- Features such as **RAM, battery power, and screen resolution** have a strong impact on price prediction.  
- Logistic Regression provides a simple and interpretable model.  

## ⚡ Conclusion

This project demonstrates **basic machine learning classification** using Logistic Regression and proper data preprocessing techniques. It’s suitable for demonstrating ML skills in a resume or portfolio.