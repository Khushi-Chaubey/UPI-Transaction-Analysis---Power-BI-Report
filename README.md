
# UPI Transaction Analysis - Power BI Report

## Project Overview
This repository contains a comprehensive Power BI dashboard designed to analyze UPI transactions for the year 2024. The report provides deep insights into transaction amounts and remaining balances, allowing users to filter data across multiple dimensions such as geography, demographics, banking institutions, and technical platforms. 

## Key Features
* **Comprehensive Slicers:** Fully formatted and synced slicers allow users to filter by `BankNameSent`, `BankNameReceived`, `City`, `DeviceType`, `Gender`, `Age Groups`, `MerchantName`, `PaymentMethod`, `Purpose`, and `TransactionType`.
* **Bookmark Toggles:** Interactive buttons created using Power BI bookmarks let users seamlessly switch between different chart types (Line Chart vs. Column Chart) for both "Amounts" and "Balances" without leaving the page.
* **Matrix Reporting:** A detailed matrix visual breaks down the financial data (Amount and Remaining Balance) month-by-month, cross-referenced by specific Cities (Bangalore, Delhi, Hyderabad, Mumbai) and their respective Currencies (EUR, USD, GBP, INR).
* **Custom Demographics:** Features a custom calculated `Age Group` column to segment transaction behaviors across different user demographics.

## Development Steps Followed
This project was developed through the following step-by-step workflow:

1. **Loading Data:** Imported the raw transaction data into Power BI Desktop.
2. **Data Profiling:** Conducted thorough data profiling in Power Query to ensure data quality, handle nulls, and check column distributions.
3. **Slicer Configuration:** Standardized the size, position, and layout of all primary slicers to create a cohesive navigation bar.
4. **Slicer Formatting:** Formatted slicers (dropdowns, styling) for an optimized user experience.
5. **Data Modeling:** Added a new report page and created a calculated `Age Group` column to enhance demographic analysis.
6. **Trend Analysis:** Added a Line Chart to visualize transaction and balance trends over the months of 2024.
7. **Matrix Visual Setup:** Configured a Matrix Visual to display multi-dimensional cross-sections of the data (Cities and Currencies).
8. **Advanced Interactivity:** Synced slicers across multiple pages so filters persist during navigation, and applied Conditional Formatting for better readability.
9. **Transaction Bookmarks:** Configured specific bookmarks to toggle between visual representations of transaction "Amounts".
10. **Balance Bookmarks:** Configured secondary bookmarks to toggle between visual representations of "Remaining Balance".
11. **Deployment:** Published the finalized, interactive report to the Power BI Service workspace.

## Data Structure Snapshot
* **Metrics Tracked:** Transaction Amount, Remaining Balance.
* **Geographies:** Bangalore, Delhi, Hyderabad, Mumbai.
* **Currencies:** INR, USD, EUR, GBP.
* **Timeframe:** January 2024 - December 2024.

---
*Developed using Power BI Desktop & Published to Power BI Service.*

```
