# End-to-End Regression Project: California Housing Prices

## 🧠 Project Overview
This project implements a complete **end-to-end Machine Learning pipeline for a regression problem**, using the well-known **California housing dataset**. The goal is to predict median house prices in California districts based on multiple features (location, population, income, etc.).

The notebook follows and extends the classic end-to-end example from the book  
*"Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow"* by Aurélien Géron,  
and has been **adapted, executed, documented, and analyzed** by me for portfolio and job application purposes.

---

## 📁 Repository Structure

├── End_to_end_machine_learning_project.ipynb   # Main notebook with the full ML pipeline  
├── README.md                                   # Project documentation  

---

## 🔍 Problem Definition
- **Task type:** Regression  
- **Target variable:** Median house value  
- **Goal:** Build and evaluate regression models that can predict house prices as accurately and robustly as possible.

---

## 🏷️ Dataset
- **Dataset type:** Public dataset (California housing)  
- **Source:** Commonly distributed through ML libraries and tutorials (e.g. scikit-learn / public repositories)  
- **Granularity:** Each row represents a California district  

### Examples of features:
- Median income  
- Median house age  
- Total rooms / bedrooms  
- Population  
- House occupancy  
- Latitude / Longitude  

---

## 🧪 Pipeline Stages

The notebook walks through a full end-to-end ML workflow:

### 1️⃣ Data ingestion & initial exploration
- Loading the dataset  
- Quick checks on shape, types, missing values  

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of key variables  
- Correlation analysis  
- Geographical visualizations of the housing market  

### 3️⃣ Data preprocessing & feature engineering
- Handling missing values  
- Scaling / transforming numerical features  
- Encoding categorical features  
- Building scikit-learn Pipeline and ColumnTransformer  

### 4️⃣ Model training
- Baseline Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Support Vector Regressor (SVR)  

### 5️⃣ Model evaluation
- Train/validation split  
- Cross-validation  
- Evaluation using RMSE and other regression metrics  
- Comparison of model performance  

### 6️⃣ Model tuning & selection
- Hyperparameter tuning (e.g. RandomizedSearchCV / GridSearchCV)  
- Final model selection based on validation performance  

### 7️⃣ Final insights
- Interpretation of the most important features  
- Limitations and potential improvements  

---

## 🛠️ Technologies Used
- **Language:** Python  
- **Libraries:** pandas, NumPy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 📊 Summary of Results (High-Level)
- Several regression models were trained and compared using RMSE and cross-validation.  
- More complex models such as **Random Forest** significantly improved performance compared to a simple baseline (e.g. Linear Regression).  
- Feature engineering and proper preprocessing (scaling, encoding, handling missing values) had a strong positive impact on model quality.  
- Exact numerical metrics can be found directly in the notebook outputs.  

---

## How to Run the Project

1️⃣ Clone the repository:  
git clone https://gitlab.com/your-username/your-repository.git  
cd your-repository  

2️⃣ (Optional) Create and activate a virtual environment.  

3️⃣ Install dependencies:  
pip install -r requirements.txt  

4️⃣ Launch Jupyter and open the notebook:  
jupyter notebook End_to_end_machine_learning_project.ipynb  

---

This project is based on a well-known public tutorial/dataset and has been adapted, documented, and extended for educational, portfolio, and professional demonstration purposes.
