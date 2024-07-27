# Bank of America Consumer Complaint Analysis (2017-2023)

## Project Overview

This project analyzes consumer complaints filed against Bank of America from 2017 to 2023. The analysis focuses on identifying seasonal patterns, most problematic products and their common issues, typical resolution methods, and insights from untimely responses. This information is crucial for improving customer service, product offerings, and complaint handling processes.

## Business Objectives

1. Identify seasonal patterns in consumer complaints
2. Determine which products generate the most complaints and their common issues
3. Analyze how complaints are typically resolved
4. Investigate complaints with untimely responses

## Data Source

The data for this analysis was sourced from Maven Analytics. It includes details such as complaint submission dates, products and issues mentioned, and the company's responses.

## Tools Used

- Python 3.x
- Libraries: pandas, matplotlib, seaborn

## Project Structure
bank-of-america-complaint-analysis/
│
├── data/
│   └── Consumer_Complaints.csv
│
├── notebooks/
│   └── complaint_analysis.ipynb
│
├── README.md

## Key Insights

- Temporal and Product Trends: Complaints increased significantly from 2019 to 2022, with a sharp decline after 2022. Q3 consistently showed the highest number of complaints. Checking/savings accounts (24,814 complaints) and credit cards (16,197 complaints) were the most complained-about products.

- Issue and Resolution Patterns: The most common issues were managing accounts (15,109 complaints) and incorrect information on reports (4,931 complaints). Most complaints (41,044) were closed with explanation, while 14,697 were closed with monetary relief.

- Response Timeliness: 3.84% of responses were untimely, with checking/savings accounts and credit cards being the top products with untimely responses. Notably, 28% of untimely responses were closed with monetary relief.

## Key Recommendations

- Enhance Account Management Services: Develop more user-friendly interfaces and provide clearer account information to reduce management-related complaints, particularly for checking/savings accounts and credit cards.

- Implement Seasonal Staffing Strategy: Allocate additional resources to customer service during Q3 to handle the increased volume of complaints, focusing on the most common issues identified in the analysis.

- Improve Response Timeliness: Analyze the root causes of untimely responses, particularly in checking/savings accounts and credit card departments, and implement a fast-track system for potentially high-impact complaints to ensure timely resolution.

## Future Work

- Conduct sentiment analysis on complaint narratives
- Analyze geographical patterns in complaints
- Develop predictive models for complaint volume forecasting

## Contact

[Daipayan Maitra] - [dmaitra14@gmail.com]

Project Link: (https://github.com/DaipayanMaitra/Financial_Consumer_Complaint_analysis)
