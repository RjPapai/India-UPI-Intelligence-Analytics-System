# India UPI Intelligence & Analytics System

## Project Overview
The **India UPI Intelligence & Analytics System** is an end-to-end data analytics project focused on analyzing India's Unified Payments Interface (UPI) ecosystem. It uses Python, SQL, and Power BI to explore transaction trends, app-level performance, data quality, and future transaction patterns.

The project transforms raw UPI data into structured datasets, performs statistical and time-series analysis, and presents key insights through an interactive Power BI dashboard.

## Project Objectives
- Analyze historical UPI transaction trends.
- Evaluate UPI application-level performance.
- Perform data cleaning, normalization, and quality assessment.
- Use SQL for structured data analysis.
- Apply statistical techniques and time-series forecasting.
- Build an interactive Power BI dashboard for business insights.

## Tools & Technologies
- **Python:** Data cleaning, preprocessing, statistical analysis, and forecasting.
- **Pandas & NumPy:** Data manipulation and numerical analysis.
- **Statsmodels:** ARIMA time-series modeling.
- **Scikit-learn:** Model evaluation metrics.
- **SQLite:** Database management and SQL analysis.
- **Power BI:** Interactive dashboards and data visualization.
- **Google Colab:** Python notebook development.

## Project Workflow
1. Raw Data Collection
2. Data Cleaning and Normalization
3. Data Quality Assessment
4. Exploratory Data Analysis (EDA)
5. SQL-Based Analysis
6. Statistical Analysis
7. Time-Series Model Comparison
8. UPI Transaction Forecasting
9. Power BI Dashboard Development
10. Documentation and Reporting

## Key Analytical Areas
- Monthly UPI transaction value and volume trends
- UPI application performance comparison
- Transaction growth analysis
- Data completeness and quality assessment
- Statistical analysis and correlation
- ARIMA model comparison and evaluation
- 12-month transaction forecasting

## Forecasting
The project evaluates multiple ARIMA configurations using a chronological train-test split.

The selected ARIMA model with drift achieved the following holdout performance:

| Metric | Transaction Value | Transaction Count |
|---|---:|---:|
| MAPE | 3.85% | 5.12% |
| MAE | 1.0928 | 1.1215 |
| RMSE | 1.3069 | 1.2367 |

*Note: These evaluation results are based on the project's matched-app aggregate dataset. They should not be interpreted as official national UPI forecasts.*

## Dataset Scope & Limitations
- Historical coverage: December 2020 – August 2026.
- Total normalized records: 111,435.
- Unique raw application names: 221.
- The dataset contains aggregate application-level information, not individual customer or transaction records.
- Missing values are retained and assessed rather than automatically replaced with zero.
- Application-level aggregates may not represent the official national UPI totals.

## Repository Structure
```text
Upi/
├── 01_Raw_Data/
├── 02_Cleaned_Data/
├── 03_Python_Analysis/
│   ├── 01_Notebooks/
│   └── 02_Final_Outputs/
├── 04_SQL_Database/
├── 05_PowerBI_Dashboard/
└── 07_Reports/
    └── 01_Project_Documentation/
```

## Expected Outcomes
- A structured and quality-checked UPI dataset.
- Reproducible Python-based analytical workflows.
- SQL-based business analysis.
- Comparative evaluation of forecasting models.
- A 12-month forecast output.
- Interactive Power BI dashboards.
- Technical project documentation.

## Disclaimer
This project is developed for academic and portfolio purposes. The findings and forecasts are based on the available dataset and its aggregation methodology. They should not be treated as official financial statistics or investment advice.

## Author
**Papai Ghosh**

Data Analytics | Business Analytics | Python | SQL | Power BI
