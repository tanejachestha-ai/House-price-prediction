House Price Prediction (Machine Learning Project)

Project Overview
This project focuses on predicting house prices using different regression algorithms in Python.  
The dataset contains various housing features, and the goal is to determine the **selling price** of a house.  
Four regression models were implemented and compared — **Linear Regression**, **KNN**, **Decision Tree**, and **Random Forest**.

---

Goal
To build a machine learning model that accurately predicts house prices and identify which regression algorithm performs the best.

---

Machine Learning Models Used
- **Linear Regression**
- **K-Nearest Neighbors (KNN) Regressor**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Best Model:** Linear Regression  
Best R² Score:** 92%

---

Technologies & Libraries
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **IDE:** Jupyter Notebook / VS Code  

---

Steps Performed
1. **Data Loading & Exploration:**  
   Imported the dataset and examined key features.
2. **Data Preprocessing:**  
   Handled missing values, encoded categorical variables, and normalized data where required.
3. **Train-Test Split:**  
   Split dataset into training and testing sets using `train_test_split()`.
4. **Model Training:**  
   Trained multiple regression models using Scikit-learn.
5. **Model Evaluation:**  
   Compared models based on **R² score** and selected the best one.

---

 Model Performance

| Algorithm | R² Score | Remarks |
|------------|-----------|---------|
| Linear Regression | **0.92** | Best performance |
| KNN Regressor | 0.85 | Sensitive to data scaling |
| Decision Tree | 0.88 | Good but slightly overfits |
| Random Forest | 0.90 | Strong but more complex |

---

 Key Learnings
- Data preprocessing and feature selection are crucial for model performance.  
- Linear Regression can outperform complex models when relationships are linear.  
- Model evaluation using R² score helps measure predictive accuracy.  
- Understanding bias-variance tradeoff across models.
