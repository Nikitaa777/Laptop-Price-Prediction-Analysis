# 💻 Laptop Price Prediction & Analysis

## 📌 Project Overview
This project analyzes laptop specifications and builds a machine learning model to **predict laptop prices**.  
The notebook includes **data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling**.

---

## 📂 Dataset
- **File:** `laptopData.csv`  
- **Features include:**  
  - Company / Brand  
  - Type of laptop  
  - RAM, Storage, GPU, CPU  
  - Display size & resolution  
  - Operating System  
  - Weight  
  - Touchscreen, IPS Panel  
  - Price (target variable)  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handle missing or inconsistent values  
- Encode categorical variables (Brand, CPU, GPU, OS, etc.)  
- Feature engineering (e.g., combining specs, extracting resolution info)  
- Scale numerical features  

### 2. Exploratory Data Analysis (EDA)
- Price distribution  
- Price vs. **Brand, RAM, GPU, CPU**  
- Impact of screen size and resolution  
- Correlation heatmap  

### 3. Feature Engineering
- Derived new features (e.g., Pixels per inch (PPI))  
- Handled categorical encoding  
- Prepared dataset for ML models  

### 4. Machine Learning Models
Models tested:
- Linear Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting / XGBoost  

### 5. Model Evaluation
- Metrics: RMSE, R² Score  
- Comparison of models to identify the best predictor  

---

## 📊 Results
- **RAM and CPU type** are the strongest predictors of laptop price  
- **Brand value** plays a significant role in pricing  
- Among tested models, **Random Forest / XGBoost** achieved the best performance with lowest RMSE  

---

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone <your-repo-link>
   cd laptop-price
pip install -r requirements.txt
jupyter notebook laptopData.ipynb
