# 📊 Teleco Customer Churn Analysis

This project explores patterns of customer churn in a telecommunications company using Python. TThe goal was to understand why customers leave the service and identify key patterns that contribute to churn, so the business can take steps to improve customer retention.

## 🧠 Objective

The dataset comes from Kaggle and contains information about customers, their subscriptions, and whether they churned or not. I focused on exploring the data visually and statistically to uncover insights that could help improve customer retention.

## 🧪 Tools & Libraries Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## 🔍 Key Steps Taken

- Cleaned the dataset (handled null values, converted data types)
- Explored target imbalance in the `Churn` column
- Visualized churn patterns by customer tenure, contract type, charges, and services used
- Investigated outliers in `TotalCharges` and tried identifying high-value customers who churned
- Interpreted churn drivers using basic statistics and plots

## 📈 Notable Insights

- The overall churn rate is around 26.5%, which is quite high.
- Most churned customers were on **month-to-month contracts**.
- Customers with **tech support and streaming services** seemed less likely to churn.
- A few **long-tenured or high-paying customers** also churned, which may represent missed retention opportunities.
- No statistical outliers in `TotalCharges` by IQR method, but manual thresholds helped analyze customer segments.

## 💡 Business Suggestions

- Provide incentives to customers on month-to-month plans to switch to longer contracts.
- Improve service bundling (tech support, streaming) as these appear linked to higher retention.
- Focus retention efforts on high-paying customers even if they’ve been around a long time.

## 🗂️ Files Included

- `Telco_Customer_Churn_Analysis.ipynb`: My full notebook with code, comments, and plots
- `Telco_Customer_Churn_Analysis.html`: Static version of the notebook (for easier viewing)

## ✅ What's Next

I'd like to eventually build a simple predictive model using logistic regression or decision trees, and maybe try visualizing this analysis in a dashboard tool like Power BI or Tableau.

---

Let me know if you'd like to update the business insights or recommendations as I continue learning.
