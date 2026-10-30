# Healthcare-Data-Cleaning-Excel
Cleaned a messy clinic dataset using Excel, standardizing dates and currencies, and built a Pivot Table to analyze revenue.

Project Overview
I took a raw, messy dataset of 1,000 clinic appointments and transformed it into a clean, actionable dashboard to analyze revenue by department.

🛠️ Tools Used
Microsoft Excel

Data Cleaning (Find & Replace, Text to Columns)

Pivot Tables & Bar Charts

🧹 The Data Cleaning Process
The raw data had several real-world formatting issues that needed fixing before analysis:

Date Standardization: The appointment dates were in five different formats (e.g., 2026/02/26, 12-Jun-2024, August 05, 24). I used the "Text to Columns" feature to standardize all dates to a single format (DD-MMM-YYYY).

Categorical Cleaning: The "Gender" column contained inconsistent entries (F, female, M, male, 1, 0). I standardized them to "Male" and "Female". The "Follow-up" column was similarly cleaned to "Yes" and "No".

Currency Formatting: The "Billing Amount" column contained mixed currency symbols (£, €, $, Rs). I stripped the symbols to allow Excel to recognize the values as numerical data.

📊 The Analysis
After cleaning the data, I created a Pivot Table to calculate the Sum of Billing Amount per Department.

Key Insight:

Neurology generated the highest total billing revenue (71,267).

Cardiology generated the lowest (58,035).

<img width="819" height="319" alt="Capture 1" src="https://github.com/user-attachments/assets/cbf34ba6-1d50-416e-a2f1-0211ce9a2ebc" />
<img width="1134" height="581" alt="Capture" src="https://github.com/user-attachments/assets/586c8c00-6d41-4c54-9f60-5295bf1f5e5e" />

