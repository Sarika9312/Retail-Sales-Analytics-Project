🛒 Retail Sales Analytics – End-to-End Data Analytics & ML Project

A complete real-world analytics project with data cleaning, feature engineering, machine learning forecasting, and an interactive Tableau dashboard.

This project analyzes Walmart Retail Sales using Python & Tableau and builds a Random Forest ML model to forecast future sales.

📌 Project Overview

This project answers real-world business questions like:

Which stores sell the most?

Which months give higher revenue?

Do holidays decrease sales?

Which departments generate the most profit?

Can we forecast future sales using ML?

Using Python, Pandas, ML models, visual analytics, and Tableau, this project gives insights from raw data → dashboard → future prediction.

📁 Folder Structure
Retail-Sales-Analytics-Project/

│

├── data/

│   ├── train.csv

│   ├── features.csv

│   ├── stores.csv

│   ├── future_predictions.csv

│

├── notebooks/

│   └── 01_data_loading_and_cleaning.ipynb

│

├── models/

│   └── sales_forecast_model.pkl

│

├── dashboard/

│   └── Retail_Sales_Dashboard.twb

│

└── README.md



⚙️ Tech Stack Used

Python (Pandas, NumPy, Scikit-learn)

Tableau

Matplotlib / Seaborn

Machine Learning (Random Forest)

Git & GitHub



🧹 Data Preprocessing & Cleaning

Performed in: notebooks/01_data_loading_and_cleaning.ipynb

Steps:

Removed missing values

Merged train + features + stores

Converted dates to usable format

Encoded categorical variables

Filled or handled MarkDown missing values

Scaled / prepared dataset

Feature selection

Train-test split

📊 Exploratory Data Analysis (Tableau)

1️⃣ Store-wise Weekly Sales

Compare performance of all stores.

2️⃣ Monthly Sales Trend

Seasonality + revenue fluctuations.

3️⃣ Holiday Impact Analysis

Holiday weeks show significantly lower sales.

4️⃣ Top Selling Departments (Treemap)

Departments 92, 90, 40, 95 dominate.

5️⃣ Future Sales Forecast (ML)

Forecast generated using Random Forest Model.

🤖 Machine Learning Model

Algorithm: RandomForestRegressor

📈 Model Performance:

R² Score: 0.744

RMSE: 11,537

Model saved at:
models/sales_forecast_model.pkl

ML predictions saved at:
data/future_predictions.csv

📊 Tableau Dashboard

File:
dashboard/Retail_Sales_Dashboard.twb

Contains:

Total Sales KPI

Store-wise Sales

Monthly Trend

Holiday Impact

Top Departments

ML Forecast Chart

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install pandas numpy scikit-learn matplotlib seaborn

2️⃣ Run Notebook

Open:

notebooks/01_data_loading_and_cleaning.ipynb

3️⃣ Open Tableau Dashboard
dashboard/Retail_Sales_Dashboard.twb

💡 Key Insights (TL;DR)

Holiday weeks have lower sales

Store performance varies strongly

Departments 92, 90, 40, 95 drive highest revenue

Sales show seasonal patterns

ML model predicts future trends effectively

👩‍💻 Author

Sarika Panchalwar
Engineering Student | Data Analytics & ML Enthusiast
🌐 GitHub: https://github.com/Sarika9312

📍 India

⭐ Like This Project?

Give it a ⭐ on GitHub — it helps a lot! 😊
🌐 GitHub: https://github.com/Sarika9312
