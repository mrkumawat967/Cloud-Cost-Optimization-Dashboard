# 📘 SETUP.md -- Cloud Cost Optimization Dashboard

## 📌 Step-by-Step Implementation

This document describes the complete process followed to build the Cloud
Cost Optimization Dashboard using Azure and Power BI.

## 🔹 Step 1: Azure Account Setup

-   Logged into Microsoft Azure Portal
-   Activated Azure Free / Student Subscription
-   Verified access to Cost Management + Billing

## 🔹 Step 2: Access Cost Management

-   Navigated to Home → Cost Management + Billing
-   Opened Cost Analysis
-   Selected subscription scope

## 🔹 Step 3: Export Cost Data

-   Selected filters (Date, Services, Resource groups)
-   Clicked Export → Download as CSV
-   Saved file as azure_cloud_cost_data.csv

## 🔹 Step 4: Data Preparation

-   Opened CSV in Excel
-   Cleaned dataset and formatted columns

## 🔹 Step 5: Install Power BI

-   Installed Power BI Desktop

## 🔹 Step 6: Import Data

-   Get Data → CSV → Load dataset

## 🔹 Step 7: Data Transformation

-   Used Power Query Editor
-   Cleaned and formatted data

## 🔹 Step 8: Create DAX Measures

Total Cost = SUM(Cost) Total Budget = MAX(Budget) Total Usage Hours =
SUM(UsageHours)

## 🔹 Step 9: Build Dashboard

-   Added KPI cards and charts
-   Created cost analysis visuals

## 🔹 Step 10: Create Detailed Page

-   Added filters and interactive visuals

## 🔹 Step 11: Configure Budget Alerts

-   Set alerts at 50%, 80%, 100%

## 🔹 Step 12: Add Optimization Tips

-   Stop unused VMs
-   Optimize storage
-   Enable autoscaling

## 🔹 Step 13: Save Project

-   Saved as .pbix file

## 🔹 Step 14: Upload to GitHub

-   Uploaded all files with screenshots

## ✅ Final Output

-   Interactive dashboard
-   Cost insights
-   Alerts configured
