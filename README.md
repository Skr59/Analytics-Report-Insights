# Retail Revenue & Customer Performance Analytics

## Project Overview
This project analyzes historical retail transaction data to understand sales performance, customer purchasing behavior, product contribution, and geographic sales distribution.

The project was developed as part of the YuvaIntern AI/ML Research Specialist Internship.

## Objectives
- Analyze retail sales trends over time.
- Identify top-performing products and countries.
- Understand customer purchasing behavior.
- Calculate important business KPIs.
- Investigate missing values, duplicate records, returns, and cancellations.
- Develop evidence-based business recommendations.

## Dataset
**Source:** [UCI Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

The dataset contains historical online retail transactions from December 2009 to December 2011.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure
```text
Analytics-Report-Insights/
├── data/
│   └── online_retail_II.xlsx
├── notebooks/
│   └── retail_business_analysis.ipynb
├── README.md
└── requirements.txt
```

## Analysis Performed
1. Data loading and exploration
2. Data quality assessment
3. Duplicate transaction investigation
4. Cancellation and return analysis
5. Sales trend analysis
6. Product performance analysis
7. Customer purchasing behavior
8. Country-wise sales analysis
9. KPI calculation and visualization
10. Business insights and recommendations

## Key Performance Indicators
- Positive transaction sales
- Unique invoices
- Identified customers
- Average order value
- Repeat purchase rate
- Country-wise sales contribution
- Product-wise sales contribution

## Important Data Considerations
The project preserves the original dataset and creates separate working datasets for analysis.

Exact duplicates, missing customer IDs, negative quantities, and cancellation invoices are investigated separately.

Positive transaction sales should not be interpreted as audited net revenue or profit.

## Results
Validated numerical findings, visualizations, and business recommendations will be documented after final KPI verification.

## Author
Shivam Kumar

## License and Attribution
Dataset: UCI Online Retail II, DOI: 10.24432/C5CG6D.

Dataset license: CC BY 4.0. Please refer to the original UCI dataset page for attribution and usage details.