# Dyanamic-Price-Prediction
Dynamic Pricing Optimization using Machine Learning | EDA, Feature Engineering, Regression Models, GridSearchCV &amp; Deep Learning to predict optimal ride pricing.

## Model Evaluation Results
Linear Regression remains the top-performing model for your Dynamic Pricing Dataset across all metrics.

*## Dynamic Pricing Optimization*
This project applies machine learning to predict optimal prices using the Dynamic Pricing Dataset from Kaggle. Multiple regression models were trained and evaluated to find the most accurate pricing strategy.  
------------------------------
## 📊 Performance Summary
The models are ranked from best to worst performance for each metric below:
## Mean Absolute Error (MAE)

* LinearReg: 51.9600 🏆
* Random Forest: 53.3960
* LGBM: 53.4592
* Gradient Boost: 53.6766
* XGBoost: 54.6461
* KNN: 55.2420
* AdaBoost: 56.7256

## Mean Squared Error (MSE)

* LinearReg: 4484.8243 🏆
* LGBM: 4871.4153
* Gradient Boost: 4925.9435
* Random Forest: 5041.7900
* XGBoost: 5087.9761
* AdaBoost: 5265.7565
* KNN: 5315.9396

## R-squared Score (R²)

* LinearReg: 0.8769 🏆
* LGBM: 0.8663
* Gradient Boost: 0.8648
* Random Forest: 0.8617
* XGBoost: 0.8604
* AdaBoost: 0.8555
* KNN: 0.8541

## Mean Absolute Percentage Error (MAPE)

* LinearReg: 0.1440 🏆
* Random Forest: 0.1473
* LGBM: 0.1581
* Gradient Boost: 0.1581
* XGBoost: 0.1806
* KNN: 0.1826
* AdaBoost: 0.1968

------------------------------
## 🏆 Final Conclusion
Linear Regression is selected as the production model for this dynamic pricing task.

* Accuracy: It yields the lowest average pricing error (MAE = 51.96).
* Fit: It explains 87.69% of the variance in the dynamic pricing data.
* Reliability: It achieves the lowest percentage error (MAPE = 14.4%).

------------------------------
## 🚀 Quick Start## 1. Clone the repository

git clone https://github.com
cd dynamic-pricing

## 2. Install dependencies

pip install -r requirements.txt

## 3. Run evaluation

python evaluate_models.py
