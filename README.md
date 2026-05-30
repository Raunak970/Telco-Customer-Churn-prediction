# Telco Customer Churn Prediction

## 📖 Project Overview
Customer churn is a critical challenge for subscription-based businesses.  
This project builds a machine learning model to predict churn and uncover the key drivers, enabling targeted retention strategies.

## 🗂 Dataset
- Source: Telco Customer Churn dataset (Kaggle)  
- Rows: ~7,043 customers  
- Features: Demographics, services, billing, contract type, tenure, etc.  
- Target: Churn (Yes/No)

## ⚙️ Workflow
1. **Data Cleaning** – handled missing values, converted `TotalCharges` to numeric.  
2. **Preprocessing** – encoded categorical variables, scaled numeric features.  
3. **Train/Test Split** – stratified sampling to balance churn classes.  
4. **Model Training** – Logistic Regression, Random Forest, XGBoost.  
5. **Evaluation** – accuracy, recall, confusion matrix, ROC/AUC.  
6. **Feature Importance** – identified top churn drivers.  

## 📊 Key Results
- Accuracy: ~75%  
- Recall (Churners): ~75%   

### Top Features Driving Churn
- Contract type (short contracts increase churn risk)  
- Internet service (fiber optic users show higher churn tendency)  
- Tenure (new customers are more likely to churn)  
- Payment method (electronic check users churn more often)  
- Add‑on services (streaming, security) reduce churn likelihood  

## 💡 Insights & Recommendations
- Encourage longer contracts with loyalty perks.  
- Focus retention campaigns on new customers.  
- Monitor fiber optic customers closely.  
- Promote auto-payment methods.  
- Bundle add-on services to increase stickiness.  

## 🛠️ Tech Stack
- Python, Pandas, NumPy  
- Scikit-learn, XGBoost  
- Matplotlib, SHAP  
- Jupyter Notebook  

## 📂 Repository Contents
- `Customer_Churn_dataset.ipynb` – full notebook with code and analysis  
- `README.md` – project overview and insights  
- (Optional) `requirements.txt` – Python libraries used  

## 🚀 How to Run
1. Clone the repo  
2. Install requirements (`pip install -r requirements.txt`)  
3. Run `Customer_Churn_dataset.ipynb` in Jupyter Notebook  

## 👤 Author
- **Raunak Verma**  
- Data Science in Business Analytics  
- [LinkedIn Profile Link] - www.linkedin.com/in/raunak-verma-data 
- [GitHub Profile Link] (https://github.com/Raunak970)
[Project Repository](https://github.com/Raunak970/Telco-Customer-Churn-prediction)

