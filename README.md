# Alfido Tech - Data Analytics Internship

Work submitted by Kishu Agarwal for the Data Analytics Internship at Alfido Tech. Each task has its own folder with the notebook, report and a short README.

## Tasks
| Task | Topic | Folder |
|------|-------|--------|
| Task 1 | Customer Behaviour Analysis | [Task1_Customer_Behaviour_Analysis](Task1_Customer_Behaviour_Analysis) |
| Task 2 | Superstore Sales Performance Analysis | [Task2_Superstore_Sales_Performance_Analysis](Task2_Superstore_Sales_Performance_Analysis) |
| Task 3 | Website Traffic & User Engagement Analysis | [Task3_Website_Traffic_Analysis](Task3_Website_Traffic_Analysis) |

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

# Alfido Tech - Task 1: Customer Behaviour Analysis

Data Analytics Internship project at Alfido Tech, submitted by Kishu Agarwal.

## About the project
Analysis of e-commerce customer transactions (250,000 transactions, 49,673 unique customers, Jan 2020 - Sep 2023) to understand buying behaviour, segment customers and look at retention.

## What I did
- Data cleaning and quality checks
- EDA across product categories, payment methods, age groups and gender
- RFM customer segmentation
- Cohort retention analysis
- Looked at the churn and returns indicators given in the dataset
- Business recommendations

## Key findings
- Around 40% of customers fall in the At Risk and Hibernating RFM segments
- 96.61% of customers made more than one purchase
- The dataset's churn indicator marks 20.01% of customers as churned

Full details are in the report (PDF).

## Files
- `Alfido_Task1_Customer_Behaviour_Analysis.ipynb` - notebook with code, analysis and visualizations
- `Alfido_Task1_Report.pdf` - report with executive summary and insights

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## How to run
The notebook was made in Google Colab and asks for the dataset CSV through a file upload prompt. Open it in Colab, run the cells and upload the CSV when asked. The dataset is not included in this repo.

# Alfido Tech - Task 2: Superstore Sales Performance Analysis

Data Analytics Internship project at Alfido Tech, submitted by Kishu Agarwal.

## About the project
Analysis of the Superstore Sales dataset (Kaggle): 9,800 transaction records, 4,922 unique orders and 793 unique customers, to understand sales across categories, regions, customer segments and shipping modes.

## Key findings
- Total sales of 2,261,536.78 with an average order value of 459.48
- Technology was the top category and the West region gave the largest share of sales (31.40%)
- Phones was the top sub-category by sales
- Top 30 customers contributed 15.64% of total sales
- Average shipping duration was 3.96 days; Standard Class was the slowest at 5.01 days

## Files
- `Alfido_Task2_Sales_Performance_Analysis.ipynb` - notebook with code, analysis and visualizations
- `Alfido_Task2_Report.docx` - project report

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## How to run
Made in Google Colab. Open the notebook in Colab, run the cells and upload the dataset CSV when asked. The dataset is not included in this repo.


# Alfido Tech - Task 3: Website Traffic & User Engagement Analysis

Data Analytics Internship project at Alfido Tech, submitted by Kishu Agarwal.

## About the project
Analysis of website traffic event data (Kaggle): 226,278 events from 19 to 25 August 2021, covering 211 countries and 11,993 cities, to understand engagement, geography, content performance and daily trends.

## Key findings
- Pageviews were 62.76% of events, clicks 24.63% and previews 12.61%
- Saudi Arabia and India were the top countries; Jeddah and Riyadh the top cities
- Tesher and the track Jalebi Baby led content activity (40,841 events each)
- Thursday was the busiest day in the week observed
- No user or session IDs, so all results are event counts, not unique visitors

## Files
- `Alfido_Task3_Website_Traffic_Analysis.ipynb` - notebook with code, analysis and visualizations
- `Alfido_Task3_Report.docx` - short project report

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## How to run
Made in Google Colab. Open the notebook in Colab, run the cells and upload `traffic.csv` when asked. The dataset is not included in this repo.
