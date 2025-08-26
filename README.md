# Predicting-concrete-compressive-strength
# Predicting Concrete Compressive Strength

This project applies machine learning to predict concrete compressive strength (MPa) based on mix components and curing age.

## 📊 Dataset
- **Source:** UCI Concrete Compressive Strength dataset  
- **Size:** 1,030 samples, 9 variables  
- **Features:** Cement, Slag, Fly Ash, Water, Superplasticizer, Coarse Aggregate, Fine Aggregate, Age (days)  
- **Target:** Concrete compressive strength (MPa)  

## 🚀 Approach
1. Exploratory Data Analysis (EDA)  
   - Data cleaning and column renaming  
   - Basic statistics and histograms  
2. Preprocessing  
   - Train/test split  
   - StandardScaler normalization  
3. Models trained  
   - Linear Regression  
   - Polynomial Regression (Quadratic)  
   - RidgeCV  
   - LassoCV  
4. Evaluation  
   - R², MAE, RMSE  
   - k-fold cross-validation  

## 📦 Installation
Clone the repository and install requirements:

```bash
git clone https://github.com/cvsangita/Predicting-concrete-compressive-strength.git
cd Predicting-concrete-compressive-strength
pip install -r requirements.txt
