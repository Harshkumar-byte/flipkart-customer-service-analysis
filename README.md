# flipkart-customer-service-analysis
📌 Project Overview
This project focuses on analyzing Flipkart’s customer service operations to understand factors affecting customer satisfaction and retention. Using customer call center data, the analysis identifies patterns in response time, sentiment, CSAT scores, and call handling performance.

The goal of the project is to transform raw customer interaction data into actionable insights that can help improve customer experience and increase customer retention.

📑 Table of Contents
Project Overview

Objective / Problem Statement

About the Data

Tech Stack

Business Metrics & KPIs

Hypotheses

EDA & Analysis

Dashboard Features

Key Insights

Recommendations

Project Structure

🎯 Objective / Problem Statement
Flipkart observed a decline in customer retention despite having a large customer base and strong platform traffic.

This project focuses on answering:

Does response time impact customer satisfaction?

Do negative customer sentiments lead to lower CSAT scores?

Which call centers perform better in handling customer issues?

Does longer call duration indicate inefficient support processes?

Which factors are most related to customer satisfaction and retention?

The analysis helps identify areas where customer service operations can be improved to enhance customer experience.

📂 About the Data
The dataset contains customer call center interaction data, including:

Call Timestamp

Call Center Location

Response Time

Call Duration

Customer Sentiment

CSAT Score

Channel Information

Customer Interaction Details

Data Preparation Performed
The raw dataset was cleaned and prepared by:

Removing duplicates

Handling missing values

Standardizing date and time formats

Creating calculated fields

Extracting date-based insights

Organizing sentiment categories

Preparing KPI-ready metrics

🛠 Tech Stack
Tool	Purpose
Excel	Data Cleaning & EDA
Pivot Tables	Data Aggregation
Excel Charts	Data Visualization
Dashboarding	Interactive Reporting
GitHub	Documentation & Version Control
📊 Business Metrics & KPIs
🔹 Customer Service Performance
Average Response Time

Average Call Duration

Total Calls Handled

Average CSAT Score

Resolution Efficiency

🔹 Customer Experience Metrics
Positive vs Negative Sentiment %

CSAT by Call Center

CSAT by Response Time

CSAT by Call Duration

🔹 Operational Metrics
Call Volume by Location

Peak Support Hours

Call Handling Trends

Agent/Center Performance Comparison

🌳 Metric Tree
Business Goal
Improve Customer Retention

↓ Customer Satisfaction (CSAT)
Response Time

Call Resolution Quality

Customer Sentiment

Support Experience

↓ Operational Efficiency
Average Call Duration

Call Handling Capacity

Support Center Performance

Process Efficiency

↓ Customer Experience
Faster Support

Better Communication

Positive Interaction Quality

Consistent Resolution

🧠 Hypotheses
Hypothesis 1
Reducing average response time improves customer satisfaction scores.

Relevant Columns
Response Time

CSAT Score

Hypothesis 2
Negative customer sentiment is associated with lower CSAT scores.

Relevant Columns
Sentiment

CSAT Score

Hypothesis 3
Longer call duration may indicate inefficient issue resolution and lower satisfaction.

Relevant Columns
Call Duration

CSAT Score

Hypothesis 4
Customer satisfaction varies across different call center locations.

Relevant Columns
Call Center

CSAT Score

Response Time

📈 Exploratory Data Analysis (EDA)
The EDA process included:

🔹 Descriptive Statistics
Mean CSAT Score

Average Response Time

Average Call Duration

Distribution of Sentiment Categories

🔹 Correlation Analysis
Relationships analyzed between:

Response Time vs CSAT

Call Duration vs CSAT

Sentiment vs Satisfaction

🔹 Pivot Table Analysis
Created pivot tables for:

CSAT by Location

Sentiment Distribution

Call Volume Trends

Response Time Comparison

🔹 Visualizations
Charts used in the dashboard:

KPI Cards

Bar Charts

Pie Charts

Trend Analysis

Sentiment Breakdown

Location-wise Comparison

📊 Dashboard Features
The interactive Excel dashboard includes:

KPI Cards for key metrics

CSAT score tracking

Sentiment analysis visuals

Response time analysis

Call center comparison

Customer interaction trends

Dynamic filtering and slicers

🔍 Key Insights
Higher response times were associated with lower CSAT scores.

Negative sentiment customers consistently reported lower satisfaction.

Certain call centers handled higher call volumes but maintained better CSAT performance.

Longer call durations often indicated inefficient issue handling.

Faster and more efficient customer support improved overall customer experience.

✅ Recommendations
Reduce customer response time through better ticket prioritization.

Improve support training for handling negative customer interactions.

Standardize support processes across all call centers.

Monitor low-performing centers using KPI dashboards.

Optimize call handling workflows to reduce unnecessary call duration.

📁 Project Structure
Flipkart-Customer-Service-Analysis/
│
├── data/
│   └── customer_service_data.csv
│
├── dashboard/
│   └── Flipkart_Customer_Service_Dashboard.xlsx
│
├── analysis/
│   └── EDA_and_Pivot_Analysis.xlsx
│
├── presentation/
│   └── Final_Presentation.pptx
│
└── README.md
📊 Dashboard Preview
The dashboard presents:

Customer Satisfaction KPIs

Response Time Analysis

Sentiment Distribution

Call Center Performance

Call Handling Trends

Interactive Filters & Slicers
