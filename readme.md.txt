# Crop Yield Prediction Using Machine Learning

Project Overview
This project focuses on building a machine learning model to predict **crop yield** based on environmental and agricultural factors such as rainfall, temperature, fertilizer usage, and cultivated area. Accurate crop yield prediction can help farmers, policymakers, and agricultural planners make informed decisions regarding resource allocation and food supply planning.

The project emphasizes **model reasoning and data handling** rather than accuracy alone.

---

Problem Statement
Given historical agricultural and environmental data, predict the **crop yield (tons/hectare)** using supervised machine learning techniques.

This is formulated as a **regression problem**, where multiple input features influence a continuous target variable.

---

Dataset
- **Source:** Kaggle (Public Dataset)
- **Type:** Real-world agricultural data
- **Target Variable:** Crop Yield
- **Features Include:**
  - Crop type
  - Area cultivated
  - Rainfall
  - Temperature
  - Fertilizer usage
  - Pesticide usage

---

Project Pipeline

1. Data Preprocessing
- Handled missing and inconsistent values
- Encoded categorical variables (crop type)
- Scaled numerical features where required
- Split data into training (80%) and testing (20%) sets

2. Model Selection & Training
Multiple models were evaluated:
- Linear Regression (baseline)
- Random Forest Regressor

**Final Model Chosen:** Random Forest Regressor  
**Reason:**  
- Captures non-linear relationships  
- Robust to outliers  
- Provides feature importance for explainability  

### 3. Model Evaluation
The model was evaluated using regression metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

Results
- The model achieved a strong R² score, indicating it explains a significant portion of the variance in crop yield.
- Random Forest performed better than the baseline Linear Regression model.

*(Exact metric values may vary depending on dataset split and parameters.)*

---

Inference & Insights
- Rainfall and fertilizer usage were the most influential features.
- Crop yield increases with optimal resource usage rather than land area alone.
- Model predictions align with real-world agricultural understanding, improving trust and interpretability.

---

Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook / Google Colab

---