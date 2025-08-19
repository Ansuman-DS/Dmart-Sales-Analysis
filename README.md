🛒 D-Mart Sales Analysis Project
🚀 Overview
Welcome to the D-Mart Sales Analysis repository!
This project delivers an end-to-end solution for predicting sales at D-Mart outlets using historical data, powerful machine learning, and insightful analytics. The models forecast sales, reveal key business drivers, and empower D-Mart to maximize its operational and marketing strategies.

🎯 Problem Statement
Build a predictive model using 2013 sales data from 1,559 products across 10 stores.

Main Goals:

📊 Understand impact of product & store features on sales

🏪 Optimize D-Mart strategies to boost revenue

🔍 Identify critical factors driving performance

📦 Dataset
Samples: 8,523 rows × 12 columns

Key Attributes:

🏷️ Item_Identifier, Outlet_Identifier

⚖️ Item_Weight

🧈 Item_Fat_Content

👀 Item_Visibility

🍱 Item_Type

💸 Item_MRP

🗓️ Outlet_Establishment_Year

📏 Outlet_Size

📍 Outlet_Location_Type

🏢 Outlet_Type

📈 Item_Outlet_Sales (Target variable)

🛠️ Data Preparation
🧹 Handle missing data (e.g., mean imputation for Outlet_Size)

⚖️ Normalize numerical features (Item_Weight, Item_Visibility, Item_MRP)

🔢 Encode categorical features (label encoding)

✂️ Split data: 80% training, 20% testing for robust validation

🤖 Modeling Approach
Linear Regression 📐 – Baseline model, interprets linear relations

Random Forest Regressor 🌳 – Captures non-linear interactions, analyzes importance

XGBoost Regressor (XGBRegressor) 🚀 – Hyperparameter-tuned for maximum accuracy

📊 Model Evaluation
Metrics:

✅ R-squared (Higher = Better fit)

📉 Mean Absolute Error (MAE) (Lower = Better predictions)

Visuals:

📈 Accuracy Bar Chart – Quick model comparison

📊 Yearly Sales Graph – Spot sales peaks/troughs

🔦 Product Visibility Graph – See the effect of visibility on sales

🏆 Key Results
🥇 XGBRegressor achieved the highest accuracy and was chosen for final predictions

🎯 Final model performed best on unseen test data, offering strong real-world impact

🔬 Feature importance analysis unlocked actionable insights for the business

📝 Conclusion
This project provides a practical framework for retail sales forecasting using best-in-class machine learning.
Findings drive smarter decisions, unlock growth, and help D-Mart stay ahead!

⚙️ Tech Stack
🐍 Python

📚 scikit-learn

🚀 XGBoost

🧮 Pandas, NumPy

📊 Matplotlib

🏁 Getting Started
⭐ Clone the repo.

🛠️ Install dependencies (requirements.txt).

📓 Run code/notebooks for data processing, modeling, and evaluation.

🔍 Check out the visualizations and insights for D-Mart sales optimization.

📧 Contact
Project by Ansuman Mishra
✉️ mishransuman@gmail.com
