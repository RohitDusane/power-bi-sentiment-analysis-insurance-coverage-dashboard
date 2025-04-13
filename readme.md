# 🛡️ Prism Insurance Performance & Sentiment Analysis Dashboard in Power BI | Word Cloud, Decomposition Tree, Sentiment Scoring

This project uses **Power BI** to analyze and visualize insurance data, providing insights into **policy performance**, **claims trends**, and **customer demographics**. The interactive dashboard helps stakeholders identify patterns, assess risks, and make informed decisions for optimizing business strategies and improving customer engagement. 📊

## Dataset

The dataset includes insurance policy records with the following fields:
- **PolicyNumber**  
- **CustomerID**  
- **Gender**  
- **Age**  
- **PolicyType**  
- **PremiumAmount**  
- **CoverageAmount**  
- **Claims Details**  

This dataset allows for in-depth analysis of trends, customer demographics, claim behaviors, and policy performance. 🧑‍💼

## Objectives

The primary objectives of this project are:
- **Identify trends in claims** over time to spot emerging patterns and areas for improvement. 📉
- **Analyze premium distributions** across different demographics to understand revenue generation. 💰
- **Evaluate policy performance** by assessing trends based on policy types and customer demographics.  
- **Assess claims behavior** to identify areas where the business can enhance support and adjust coverage. 🔍
- **Evaluate Sentiment** by assessing trends based on customers feedback.  

## Overview

The **Prism Insurance Performance Dashboard** focuses on analyzing insurance sales and customer engagement data. By importing the dataset into **SQL Server** and profiling it with **Power BI**, the dashboard provides valuable insights into key areas like premium distribution, claim status, and policy performance. Additionally, the dashboard integrates **sentiment analysis** of customer feedback to offer deeper insights into client satisfaction and inform sales strategies. 📈

## Project Components

### 🧳 Data Import & Setup
- **Imported data** from the insurance policy dataset into **SQL Server** for streamlined storage and easy access.
- **Data cleaning** and normalization were performed to ensure data integrity across all fields. ✅

### 🔍 Data Profiling in Power BI
- Conducted comprehensive data profiling to identify trends, outliers, and key performance metrics across **policy types**, **premium amounts**, and **customer demographics**.
- Generated summary statistics to evaluate policy performance, claims trends, and premium distributions. 📊

### Dashboard Link
- [Report](https://app.powerbi.com/links/iRu-1qg7iN?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare&bookmarkGuid=d1eca92c-a5a6-4ebe-ae8f-63cd79a2c5b6)

### 📊 Key Visualizations

Created a range of interactive visuals in Power BI, including:

- **Policy Information**: Overview of **policy numbers**, **premium amounts**, **claim amounts**, and **coverage amounts** to assess policy performance.
- **Policy Type and Gender**: Breakdown of **policy types** and gender-based analysis of active/inactive policies to understand customer preferences. 👩‍💼👨‍💼
- **Claim Analysis**: Distribution of claims by **status** and **age group** to identify trends in claim frequency and settlement rates. 💼
- **Coverage Analysis**: Analysis of **coverage amounts** by **policy type** and **claim status** to assess coverage adequacy and identify high-risk policies. 🛠️

### 📈 Key Insights & Analysis

- **Premium Distribution by Demographics**:  
  - **Adults (31-40)** contribute the highest premium revenue, making up **52%** of total premium collections. 🏆  
  - **Seniors (65+)** follow closely with **38%**, while younger groups (18-24) contribute **10%** approximately. 👵
  
- **Trends in Claims Status **:  
  - **Claims by Status**: **60%** of claims are **approved**, **30%** are **pending**, and **10%** are **denied**. 🔴

- **Policy Performance by Type**:  
  - **Travel Insurance** accounts for **41%** of total policies, with a **high approval rate** for claims. 💊  

- **Coverage Amount by Policy Type**:  
  - **Auto policies** generally have the highest **coverage amounts** for **Females Settesled claims** . 🏥🚗

### 🧠 Sentiment Analysis
 
** Creating the Sentiment Score** 
The dataset underwent a meticulous cleansing process through the utilization of the built-in "Clean" function applied to the "Custom column", rendering 
the data primed for analysis. Subsequent to this preparation, the Text Analytics function from Azure Cognitive Service was harnessed to generate sentiment
 scores for each entry within the customized "Text" column. This approach facilitated the quantification of sentiment nuances, culminating in a comprehensive
 evaluation of the dataset's emotional undercurrents. After calculating the sentiment scores using the Text Analytics tool, we organized the scores into
 clear categories using a conditional column. Sentiment scores above 0.8 were labeled as 'Excellent', scores of 0.6 were marked as 'Good', and scores
 below 0.6 were categorized as 'Needs Improvement'. 
 
This straightforward approach added meaningful labels to the sentiment data, making it easier to grasp the emotional context behind each entry.

** Sentiment Analysis **
- Analyzed customer feedback through **sentiment analysis** to gauge customer satisfaction and areas for improvement.
- Developed visual representations of sentiment scores to correlate feedback with sales outcomes.. 👍  

## Tools & Technologies

- **Power BI**: Used to create interactive dashboards and visualizations to display key performance metrics. 📊  
- **SQL Server**: Served as the database for organizing and storing raw insurance data. 💾  
- **DAX**: Employed for advanced calculations and insights generation. 🔢  

## Key Recommendations 🚀

- **Promote Policy Types Based on Gender Preferences**: Adjust marketing strategies to target **men** with **Car Insurance** and **women** with **Health Insurance**. 🚙💊
- **Address Negative Sentiment**: Focus on improving customer support for younger customers and enhancing policy features to increase satisfaction. 💬

Thank you for exploring the **Prism Insurance Performance Dashboard**! This project demonstrates how **Power BI** can transform raw data into actionable insights for better business decisions and improved customer engagement. ✨