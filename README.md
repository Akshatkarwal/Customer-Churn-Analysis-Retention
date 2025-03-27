# Customer Churn Analysis & Retention

## 📌 Project Overview
Customer churn is a critical issue for subscription-based businesses. This project analyzes customer churn patterns and provides actionable insights to improve retention strategies. Using **Python, Pandas, Plotly, and Power BI**, we process and visualize customer churn data to help businesses make data-driven decisions.

## 🔧 Tech Stack & Tools
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Plotly, Seaborn
- **Visualization:** Power BI

## 📊 Key Features
- **Data Ingestion:** Load customer churn dataset from CSV.
- **Data Cleaning & Preprocessing:** Handle missing values, encode categorical data, and process dates.
- **Exploratory Data Analysis (EDA):** Identify churn trends using statistical analysis and visualization.
- **Customer Segmentation:** Classify customers based on engagement and risk of churn.
- **Churn Rate Analysis:** Evaluate churn trends over time and factors contributing to churn.
- **Power BI Dashboard:** Create interactive reports with KPIs, retention insights, and customer behavior trends.

## 📂 Dataset
The dataset contains information about customer subscriptions, tenure, monthly charges, contract type, payment method, and churn status. Ensure the dataset file **Customer Churn.csv** is in the working directory.

## 📊 Power BI Dashboard
### Key Visuals
✅ **Churn Rate Over Time** – Track monthly churn trends.
✅ **Top Reasons for Churn** – Identify major factors contributing to churn.
✅ **Customer Lifetime Value Segmentation** – Analyze customer value and retention potential.
✅ **Contract Type & Payment Method Analysis** – Compare churn rates across different plans.

### DAX Measures
```DAX
Churn Rate =
DIVIDE(
    CALCULATE(COUNT('Customer Churn'[Customer ID]), 'Customer Churn'[Churn] = "Yes"),
    COUNT('Customer Churn'[Customer ID])
)
```

## 🎯 Business Impact
- Helps businesses identify at-risk customers and apply targeted retention strategies.
- Provides insights into customer behavior, improving marketing efforts.
- Enhances customer experience by addressing common churn reasons.

## 🚀 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas plotly seaborn
   ```
3. Run the Python script to generate insights.
4. Load the **Customer Churn.csv** dataset into Power BI and build the dashboard.

## 🏆 Acknowledgment
Dataset Source: Telco Customer Churn Dataset

📩 **For queries, reach out at:** akshatkarwal1@gmail.com

