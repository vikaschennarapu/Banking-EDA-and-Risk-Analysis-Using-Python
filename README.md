# Banking-EDA-and-Risk-Analysis-Using-Python
## Project overview
- Performed end‑to‑end EDA and risk analysis on a synthetic banking dataset with 3,000 customers and 25 variables (age, income, deposits, loans, risk weighting, loyalty, properties owned, etc.).
​
- Built visual analytics in Power BI to track deposits, loans, income bands, customer segments and portfolio risk metrics.
​
- Generated an executive portfolio risk summary including risk distribution, loan‑to‑deposit ratio and key portfolio health indicators
 
## oroject Objectives
- Understand customer banking behavior across deposits, savings, checking, loans and business lending.
​
- Segment customers by income band, loyalty tier and risk weighting to identify medium/high‑risk segments.
​
- Provide an executive‑level dashboard summarizing portfolio risk, key KPIs and actionable recommendations.
 
## Dataset Used
- <a href="https://github.com/vikaschennarapu/Banking-EDA-and-Risk-Analysis-Using-Python/blob/main/Banking.csv">Dataset</a>

## Methodology (Python EDA)
- Data loading and inspection with pandas, including shape, dtypes and info to validate data quality.
 ​
####  Feature engineering:
- Converted Joined Bank to proper datetime.​
- Binned Estimated Income into Income Band (Low, Mid, High).
 ​
####  Categorical profiling:
- value counts for Risk Weighting, Nationality, Occupation, Fee Structure, Loyalty Classification, Properties Owned, and Income Band.
 ​
- Descriptive statistics and distribution analysis for all numerical features (age, income, balances, loans, deposits, business lending, etc.).
 ​
####  Correlation analysis:
- Full correlation matrix and heatmap for numerical variables.​
- Pairwise regression plots for key relationships (e.g., Bank Deposits vs Saving Accounts, Bank Loans vs Credit Card Balance, business lending vs loans).
  
## Key insights
#### Deposits & savings
- Strong positive correlation between bank deposits and saving accounts, indicating customers who deposit more also maintain higher savings balances.
​
#### Income & lifecycle
- Older and higher‑income customers tend to accumulate higher superannuation savings, deposit and account balances, and may carry larger loans or credit card balances.
​
#### Properties & collateral
- Most customers own 1–3 properties, providing solid collateral backing; property ownership is more weakly correlated with individual balance metrics, suggesting external drivers (location, real estate market, etc.).
​

#### Portfolio risk
- Risk Weighting level 2 is the dominant segment in the portfolio, contributing the largest share of customers.​
- Overall portfolio is categorized as Medium Risk, with average risk score around 2.25.​
- Loan‑to‑deposit ratio lies in a healthy 0.70–0.95 range at portfolio level.​
- 50–51% of customers are mid‑income; 75%+ own at least one property, indicating moderate risk with good collateral.​
- Business lending exposure is high relative to income and should be monitored closely.
  
## Power BI dashboard 
- Pages / sections:
- Summary / Executive Dashboard: total clients (3,000), total loans (~4.38B), total deposits (~3.77B), breakdown of checking, savings and business lending.
- Loan Analysis: loans by BR, Income Band, Nationality, Occupation, and gender filters.
- Deposit Analysis: deposits by BR, Income Band, Nationality, Occupation; checking and savings balances.
- Risk & Income: risk weighting vs estimated income and loyalty classification; distribution of risk scores.
 
<a href="https://github.com/vikaschennarapu/Banking-EDA-and-Risk-Analysis-Using-Python/blob/main/BANKING%20RISK%20ANALYSIS%20EDA.pbix">Power BI Dashboard</a> 

## Project Python Code
<a href="https://github.com/vikaschennarapu/Banking-EDA-and-Risk-Analysis-Using-Python/blob/main/BANKING%20EDA%20AND%20RISK%20ANALYSIS%20USING%20PYTHON%20(1).ipynb"> Jupyter Notes</a>
## Fianl Conclusion
- This project delivers a clear, end‑to‑end risk analytics view of a 3,000‑customer banking portfolio by combining Python‑based EDA with an executive‑level Power BI dashboard. The analysis validates clean data, engineers meaningful segments (such as income bands and risk levels), and quantifies relationships between deposits, loans, income and collateral, resulting in a portfolio classified as medium risk with a healthy loan‑to‑deposit profile.
- The final outcome is a practical decision‑support tool that highlights key risk drivers, surfaces high‑attention customer segments and provides data‑backed recommendations for portfolio optimization and customer retention strategies
