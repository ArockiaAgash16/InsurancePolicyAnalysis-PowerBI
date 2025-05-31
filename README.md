# 📊 Insurance Policy Analysis Dashboard | Power BI + MS SQL Server + Power Query Text Analytics

## 📌 Project Overview

This Power BI project delivers a comprehensive, interactive insurance analytics solution by integrating policy, claim, customer, and feedback data from MS SQL Server and Excel. The dashboard is designed for business users to monitor key insurance KPIs, track claim statuses, analyze premium distributions, and assess customer sentiment based on real feedback.

The solution leverages Power Query Text Analytics for sentiment scoring, enabling a unified operational and customer experience reporting system.

## 🛠️ Data Pipeline Workflow

* Imported insurance policy and claim data from CSV files into MS SQL Server

* Connected Power BI directly to MS SQL Server as a live data source

* Transformed the data in Power Query Editor by adding some custom columns for analysis

* Loaded additional customer feedback from an Excel file into Power BI

* Applied Power Query Text Analytics Sentiment Scoring to feedback comments, generating a sentiment score for each

* Created a custom column categorizing feedback as Excellent, Good, Needs Improvement based on sentiment scores

* Designed a multi-tabbed Power BI report with drill-through, word clouds, sentiment analysis, and detailed policy tables

## 📊 Dashboard Features

### 1️⃣ Major Metrics (Tab 1)

* KPIs: Premium Amount, Coverage Amount, Claim Amount

* Gender-wise customer counts

* Number of claims by claim status (Rejected, Settled, Pending)

* Premium Amount by Policy Type (Bar Chart)

* Premium Amount by Age Group (Line Chart)

* Active/Inactive Policies distribution (Donut Chart)

* Claim Amount by Policy Type in a detailed summary table

![image](https://github.com/user-attachments/assets/c9e4f0a0-a256-4576-b0de-54c88478bd75)

### 2️⃣ Drill-Through Filter (Tab 2)

Drill-through enabled on Policy Type

![image](https://github.com/user-attachments/assets/1af92381-1024-4fbd-9552-19f425917ca9)

### 3️⃣ Sentiment Analysis (Tab 3)

* Imported customer feedback from Excel (99 rows)

* Applied Power Query Text Analytics Sentiment Scoring

* Created a custom column for Excellent, Good, Needs Improvement categorization based on sentiment score

* Visualized:

  * Word Cloud of frequently occurring feedback terms
  
  * Sentiment distribution bar chart (count of customers per category)
  
  * Detailed feedback table displaying Customer Name, Sentiment Score, and Feedback

![image](https://github.com/user-attachments/assets/e9a02b4c-a3ff-4f7e-8814-f9f94b0c9468)

## 🔗 Live Report

https://app.powerbi.com/view?r=eyJrIjoiZTlkMzFjOTYtN2ZkMy00OTMyLTg3Y2UtMzFlZjYyNjVlMTQ0IiwidCI6IjE0YzAyY2YxLWE4ZjYtNGI3My1iMmNjLTQ0YTM0MjE5N2FiZiJ9

## 📦 Technologies Used

* Power BI Desktop

* MS SQL Server

* Excel (feedback data)

* Power Query Text Analytics

* Table Visuals, Bar Charts, Donut Charts, Drill-Through Filters, Word Cloud

## 🎯 Outcomes

* Delivered a cloud-connected, interactive, multi-tabbed insurance analytics dashboard

* Enabled policy managers to drill through individual policy and claim records for in-depth insights

* Incorporated customer sentiment insights using AI-driven sentiment scoring within Power BI

* Enhanced operational and customer experience visibility through a unified reporting platform

## ✅ How to Use

* Download the .pbix file

* Open with Power BI Desktop (2023 May or newer).

* Connect to your MS SQL Server instance (or replace with your own dataset)

* Explore the three dashboard tabs interactively
