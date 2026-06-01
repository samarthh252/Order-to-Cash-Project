# Order-to-Cash (O2C): Accounts Receivable Aging Dashboard

## 📌 Project Overview
This project simulates an end-to-end Accounts Receivable (AR) aging analysis, a core component of the Order-to-Cash (O2C) and Record-to-Report (R2R) lifecycle. I engineered a commercial-grade dashboard to track, categorize, and visualize outstanding invoice balances, enabling management to instantly identify critical bottlenecks in cash flow. 

## 📊 The Dataset
To ensure commercial realism, I designed a simulated dataset of 700+ B2B trading invoices modeled after the raw material packaging and corrugation industries. 
* **Volume:** 711 individual invoices.
* **Variables:** Customer Name, Invoice Date, Invoice Amount, Payment Terms (30/45/60 days), and Payment Status.

## 🛠️ Technical Stack & Excel Functions Used
* **Data Structuring:** Built foundational data logic to calculate dynamic Due Dates and exact Days Overdue using `=TODAY()` and nested `IF` statements.
* **Aging Categorization:** Engineered logical formulas to route delinquent accounts into standard corporate aging buckets (1-30, 31-60, 61-90, and 90+ Days).
* **Data Visualization:** Developed an interactive PivotChart (Stacked Bar) to isolate the Top 10 critical debtor accounts.
* **Interactivity:** Integrated PivotTable Slicers to allow live filtering of outstanding cash by aging bucket.

## 💡 Business Impact (The "Why")
In a live corporate finance environment, delayed cash application impacts working capital. This dashboard automates the visualization of delinquent B2B accounts, allowing Collections and Credit Management teams to prioritize dunning efforts on the highest-value, longest-overdue accounts.

## 📸 Dashboard Preview
![AR Dashboard Preview](Dashboard_Screenshot.png)
*(Note: Ensure your screenshot file is named Dashboard_Screenshot.png for this image to load)*
