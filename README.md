# Unified_Mentor_projects_dataAnalysis

#Data Analytics, Finance Analytics & Cybersecurity (Sept 2025 – Dec 2025)

#This repository contains all three major projects completed during my internship at Unified Mentor. It includes Jupyter notebooks, dashboards, and analysis files.

#Reference: “Unified Mentor Project File” 
Email: hrithikac65@gmail.com
LinkedIn: www.linkedin.com/in/hrithika-c-417197251

#Repository Contents
File	Description
-Stock analysis dashboard.pbix	Power BI dashboard for Stock Market Analysis
-colorado.ipynb	Jupyter notebook for Colorado Vehicle Sales Analysis
-cyber.ipynb	Jupyter notebook for Cybersecurity Anomaly Detection

#PROJECT 1 — Stock Market Performance Analysis

-Tools Used: Excel, MySQL, Power BI, SQL Window Functions, DAX
-Data: 82 stocks · 10+ sectors · Jan–Jul 2025

#Objective
-Analyze multi-sector stock performance, volatility trends, outliers, and investment opportunities.

#Key Insights

-Technology sector leads with 40% market capitalization
-Healthcare shows the highest volatility (2.35%)
-Energy appears undervalued (PE ≈ 15)
-Wednesday recorded the highest trading volume
-Identified 105 outlier data points

#Workflow
-Excel: Cleaning, type formatting, date conversion
-SQL: Time-series analysis, moving averages, CTEs, volatility, outliers
-Power BI:
  Sector performance dashboard
  Ticker-level dashboard
  Summary dashboard

#Recommendations
-Cap exposure to any one sector at 40%
-Stop-loss thresholds: 15% (stocks), 10% (sectors)
-Suggested portfolios: Growth / Balanced / Conservative

#PROJECT 2 — Colorado Motor Vehicle Sales Analysis

-Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn
-Techniques: Time Series · YOY Growth · Random Forest Regression

#Objective
-Analyze 8 years (2008–2015) of motor vehicle sales to identify seasonal patterns, county performance, and build a forecasting model.

#Key Insights
-Total sales analyzed: $88.04B
-Q4 = strongest quarter (27%)
-Denver, Arapahoe & Jefferson counties = 45%+ market share
-Post-recession CAGR = 8.7%

#ML Model Performance
-Random Forest Regression: R² = 0.94, MAPE = 8.7%
-Key predictors: lag trends, county, previous sales

#Recommendations
-Strengthen Q3–Q4 promotions
-Increase inventory for Q4
-Allocate resources to top-performing counties

#PROJECT 3 — Cybersecurity: Suspicious Web Threat Interactions

-Tools Used: Python, Jupyter Notebook, Excel
-Models: Isolation Forest, Neural Network Classifier

#Objective

-Analyze inbound/outbound traffic patterns to detect anomalies, suspicious IPs, and WAF-trigger triggers.

#Key Findings

-High outgoing bytes indicate possible data exfiltration attempts
-Certain country/IP clusters frequently appear in malicious traffic
-Isolation Forest flagged ~5% anomalies
-Clear distinction between normal vs attack-like behavior

#Security Recommendations

-Block or rate-limit high-risk IP ranges
-Enhance WAF rules focusing on outgoing byte spikes
-Implement automated anomaly alerts (Isolation Forest/NN)
-Introduce geo-IP throttling

#How to Run the Project Files
#Open Jupyter Notebooks
jupyter notebook colorado.ipynb
jupyter notebook cyber.ipynb

#View Power BI Dashboard
Open the file: Stock analysis dashboard.pbix

#Acknowledgement
Thanks to Unified Mentor for providing high-quality datasets and guidance across finance, analytics, and cybersecurity domains.
