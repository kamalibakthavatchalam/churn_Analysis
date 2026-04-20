# Customer Churn Analysis & Prediction 
Telecom Industry | Machine Learning | Python | Google Colab


## About This Project

This project analyses 7,043 real telecom customer records to identify 
why customers cancel their service and to build a machine learning 
model that can predict churn before it happens — giving businesses 
the chance to act early and retain customers.


## Key Results

| Metric | Result |
|---|---|
| Dataset Size | 7,043 customers |
| Overall Churn Rate | 26.6% |
| Best Model | Logistic Regression |
| Best AUC Score | 0.84 |
| Model Accuracy | ~80% |
| Business Recommendations | 4 |


## Key Findings

- Month-to-month customers churn at **42%** vs only **3%** 
  for two-year contract holders
- Churned customers leave early — median tenure of just 10 months
- Customers paying above £70/month are at highest price-sensitive risk
- Tenure, MonthlyCharges, and TotalCharges are the top 3 predictors


## Models Built

| Model | Accuracy | AUC Score |

| Logistic Regression | ~80% | 0.84 |
| Random Forest | ~79% | 0.81 |

Both models significantly outperform random chance (AUC = 0.50).

## Business Recommendations

1. **Convert month-to-month customers** — offer discounts to 
   switch to annual contracts
2. **Prioritise the first 18 months** — proactive outreach at 
   months 1, 3, 6, 12, and 18
3. **Bundle tech support for new customers** — reduces early 
   frustration and churn
4. **Review pricing for high-bill customers** — loyalty pricing 
   for customers paying above £70/month


## Tools & Technologies

- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Project Files
customer-churn-analysis/
│
├── churn_analysis.ipynb          # Main analysis notebook
├── Customer_Churn_Report.docx    # Full professional report
├── train.csv                     # Dataset
└── README.md                     # Project overview

## Author

- Email: kamaliblrkvhd789@gmail.com
