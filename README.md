# Car Purchase Prediction Project

## Overview
This project predicts car purchase amounts using demographic and financial data to optimize marketing strategies.  
**Key Tasks**:  
- Data preprocessing & feature engineering.  
- Regression model training (Linear, Decision Tree, Random Forest, XGBoost).  
- Customer segmentation using K-means.  

## Dataset
- **Source**: `data/car_purchasing.csv`  
- **Features**:  
  - Demographic: `age`, `gender`, `country`  
  - Financial: `annual Salary`, `credit card debt`, `net worth`  
- **Target**: `car purchase amount`  

## Setup
1. **Clone Repository**:  
   ```bash
   git clone https://github.com/m-narayanan/sales-prediction.git
   cd sales-prediction
   pip install -r requirements.txt

2. **Usage**
  - Place raw data in data/ directory

  - Run notebooks in order:
```bash
   1_data_analysis.ipynb

   2_preprocessing.ipynb

   3_model_training.ipynb
```
  - Find saved models in models/
