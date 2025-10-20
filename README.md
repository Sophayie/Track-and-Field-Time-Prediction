# Athlete Performance Prediction — Track & Field 1500m

## Overview
This project was developed as part of a data science competition focused on predicting an athlete’s personal best on the **1500-meter event** using their past performances at other distances and demographic data.

The objective is to explore and evaluate different **supervised regression models** to identify the one that provides the most accurate and stable predictions in a real-world sports analytics context.

---

## Methodology
An experimental, comparative approach was adopted to evaluate several supervised learning algorithms, including:

- **Linear Regression**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Regression (SVR – RBF kernel)**  
- **Neural Networks**

Model performance was assessed using standard regression metrics such as **RMSE**, **MAE**, and **cross-validation RMSE (CV RMSE)** to evaluate both accuracy and generalization capability.

---

## Results
While **Gradient Boosting** achieved the lowest RMSE on the test set (~2999), **Random Forest** demonstrated superior stability and generalization with a cross-validated RMSE variance of only **63%**, compared to **114%** for Gradient Boosting.

These results suggest that **Random Forest** offers a more reliable balance between predictive accuracy and robustness, making it the optimal choice for predicting 1500m times.

---

## Key Learnings
- Importance of balancing accuracy and model generalization  
- Impact of feature engineering and scaling on regression models  
- Comparative analysis of ensemble methods in sports performance prediction

---

## Technologies
- **Python**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn** (model training and evaluation)  
- **Jupyter Notebook**

---
## Open in Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hM8jqgeYr4qNzStI76BrCJhZ5q1DFqGl?usp=sharing)  
It is recommended to run the notebook in Google Colab for better visualization of performance results.

---
## Author
**Sophie Mercier**  
AEC in Internet of Things and Artificial Intelligence  
