# Car Insurance Claim Prediction 🚗📊

## Project Overview
This project predicts whether a car insurance policyholder will make a claim, using classification models and SMOTE for handling imbalance.

## Steps Followed
1. Data loading & cleaning
2. Exploratory Data Analysis (EDA)
3. Feature engineering & preprocessing
4. Handling class imbalance (SMOTE)
5. Model training (Logistic Regression, Random Forest, XGBoost)
6. Model evaluation & threshold tuning
7. Model saving and submission file creation
8. Report with results and plots

## Repository Structure
- `eda.py` → Exploratory Data Analysis 
- `preprocess.py` → Preprocessing pipeline 
- `train_model.py` → Model training 
- `models.py` → Model definitions 
- `utils.py` → Evaluation & helper functions 
- `main.py` → Main script (runs entire pipeline) 
- `submission.csv` → Final predictions 
- `final_model.joblib` → Trained model 
- `eda_plots/` → Saved EDA plots 
- `report.pdf` → Final project report 
- `requirements.txt` → Libraries used 

## How to Run
```bash
git clone <repo-link>
cd car_insurance_claim_project
pip install -r requirements.txt
python main.py
