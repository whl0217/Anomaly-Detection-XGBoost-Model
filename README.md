# Loan-Fraud-Detection-for-PPP-Loans

## Tabel of Contents
 * The Dataset
 * Problem Statement
 * Approach to Analysis
 * Presentation

## Dataset
 The dataset is sourced from the official SBA website which can be accessed using the following URL:
 ![alt text](https://data.sba.gov/dataset/ppp-foia/resource/aab8e9f9-36d1-42e1-b3ba-e59c79f1d7f0?inner_span=True)

## Problem Statement
![alt text](https://gray-wafb-prod.cdn.arcpublishing.com/resizer/ELLb-0F79fu-eD2nA4_46JmkiJs=/1200x675/smart/filters:quality(85)/cloudfront-us-east-1.images.arcpublishing.com/gray/YT67CCYJY5FDNJDURKRAGZYETY.jpg)

### PPP Loan Fraud Detection

The Paycheck Protection Program (PPP) is a loan program created by the U.S. government in 2020 to help certain businesses, self-employed workers, sole proprietors, nonprofit organizations, and tribal businesses keep paying their workers during the COVID-19 pandemic. PPP loans are private loans with low-interest rates that can be used to cover payroll costs, rent, interest, and utilities. The loan amount is based on the average monthly payroll costs of the applicant and can be forgiven if the business keeps its employee count and wages stable. The program is run by the U.S. Small Business Administration and the deadline to apply for a PPP loan was March 31, 2021.

The project explores loan data from the Paycheck Protection Program (PPP), which provided relief to small and medium-sized businesses during the COVID-19 pandemic. The primary objective is to create graphical visualizations of the data and apply anomaly detection methods to identify potentially fraudulent loans. The project outline suggests a few starting points, including reviewing news stories on fraud in the PPP loan program, downloading the full PPP loan dataset and data dictionary, summarizing the data through tabular summaries and graphical visualizations, investigating loans that have a high potential for fraud by grouping together loans in common categories and identifying outlier loans, and exploring the use of traditional unsupervised learning techniques such as anomaly detection.

## Approach to Analysis

To gain a deeper understanding of the PPP Loan dataset, we conducted an initial exploratory data analysis and created data visualizations.

The first steps involved importing and cleaning the dataset, which included handling missing values and correcting inconsistent formatting through transformations. Next, we normalized selected features of the dataset to ensure meaningful variability, enhancing the support for our analysis.

To further our insights, we employed various visualization techniques, such as line charts, histograms, correlation matrices, and heatmaps.

### Fraud Detection Techniques

We applied the supervised machine-learning algorithm, XGBoost Model, to find out characteristics of the most anomalous loans, which could be signs of PPP loan fraud.

In the cases above, we recognize top five most important variables are amount, borrower's latitude and longtitude, and lender's latitude and longtitude.

Finally, we also conducted exploratory studies on the resulting fraud-identified data to find additional patterns, connections, and trends.

The way this study is designed, we approached it with the intention to aid analysts at SBA and other relevant agencies to help investigate fraud and gain insight into the PPP Loan dataset with the identification of probable PPP loan frauds.

* XGBoost Model: [code](https://github.com/whl0217/UMD_Info_Challenge_2022/blob/main/IC22004_Predicting%20Removed%20Loan.ipynb)

## Presentation
* [Slides](https://github.com/whl0217/Anomaly-Detection-XGBoost-Model/blob/main/IC22004_Predicting%20Removed%20Loan%20-%20PPT.pdf)

### *Authors: Wang-Han Li, Chung-Hao Lee, Chia-Lin Tsai*
