# 🏠 House Price Prediction using Linear Regression with Batch Gradient Descent

## 📌 Project Overview
This project implements **Linear Regression** from scratch using **Batch Gradient Descent** to predict house prices. The dataset is taken from Kaggle and contains house features with their corresponding prices.

## 📂 Dataset
- Dataset used: [Simple House Price Prediction](https://www.kaggle.com/datasets/snehasishdhar/simple-house-price-prediction)  
- For this assignment, only the **Area** feature was considered as input, and **Price** was used as the target output.  

## ⚙️ Methodology
1. **Data Preprocessing**
   - Loaded dataset from Kaggle.
   - Selected **Area** as the feature and **Price** as the target.
   - Standardized the feature values using:
     ```python
     X = (X - X.mean()) / X.std()
     ```

2. **Model Implementation**
   - Implemented **Batch Gradient Descent** manually.
   - Initialized weights (`w`) and bias (`b`).
   - Updated parameters iteratively using gradient descent formula.
   - Used **Mean Squared Error (MSE)** as the cost function.

3. **Training**
   - The model was trained for multiple epochs.
   - Training loss curve was plotted to show cost reduction over epochs.
   - Final regression line was plotted against training data to visualize the fit.

## 📊 Results
- The **Training Loss Curve** showed a rapid decrease in error initially and then flattened, indicating convergence.
- The **Regression Line** on training data fit the overall trend well, showing a positive correlation between area and price.

## 📈 Visualizations
- **Training Loss Curve (MSE vs Epochs)**
- **Regression Line on Training Data (Predicted vs Actual)**

## 🛠️ Technologies Used
- Python  
- NumPy  
- Matplotlib  
