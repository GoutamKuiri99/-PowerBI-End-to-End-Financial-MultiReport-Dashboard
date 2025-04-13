# 📊 PowerBI-End-to-End-Financial-MultiReport-Dashboard


https://github.com/user-attachments/assets/85126a8a-162f-4544-b053-43225ecb1c3b



## 📘 Content Flow Table

| **Section** | **Content Title**                                      | **Purpose / Description**                                                                                 |
|-------------|--------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 1️⃣          | 📌 **Business Problem**                                | Explain the challenge the company faced with scattered financial data, lack of insights, and poor decision-making capability. |
| 2️⃣          | 🎯 **Project Overview**                                | Introduce the Power BI dashboard project and its purpose — a unified platform for financial monitoring. |
| 3️⃣          | 🎯 **Objectives**                                      | List clear, measurable goals like centralization, trend identification, and improved visibility. |
| 4️⃣          | 📚 **Table of Contents**                               | A structured index of report pages and what each one covers. Helps navigation. |
| 5️⃣          | 📁 **Data Sources**                                    | List Excel files used and their role in building the dashboard. |
| 6️⃣          | 🖼️ **Report Pages with Screenshots & Explanation**    | Visually showcase each report page (Overview, Revenue, Expenses, etc.) with explanations. |
| 7️⃣          | 🛠️ **Key Dashboard Features**                          | Highlight special functionalities: drillthrough, slicers, DAX time intelligence, responsive layout. |
| 8️⃣          | ⚙️ **Tech Stack**                                      | Technologies and tools involved (Power BI, Excel, Power Query, DAX). |
| 9️⃣          | 🔐 **Security**                                        | Describe implementation of Row-Level and Page-Level Security. |
| 🔟          | 🔁 **Scheduled Refresh**                               | Setup of Power BI Gateway and refresh schedule for real-time updates. |
| 1️⃣1️⃣        | 📌 **Dashboard Sharing**                               | Post-refresh, share the dashboard based on the specific requirements of the stakeholders. This section will outline how the dashboard can be shared with relevant teams or individuals. |
| 1️⃣2️⃣        | 📌 **Conclusion**                                      | Wrap-up with key benefits and how the dashboard impacts decision-making. |
| 1️⃣3️⃣        | 👨‍💻 **About the Author**                                     | Your details (name, contact, LinkedIn, Medium) for credit or reference. |

---

> ✅ Use this table to guide readers through your README step-by-step  
> 📎 Add anchor links to each section (optional) for better GitHub navigation  



## 🚨 Business Problem

The management was facing difficulties in tracking and managing their business operations across multiple departments. Financial data was stored in scattered Excel files, making it hard to monitor performance, spot trends, or take timely actions. Without a centralized system, they lacked visibility into overall business health, which affected strategic planning and profitability.

---
## 🎯 Project Overview

This Power BI dashboard is designed to streamline business monitoring by integrating multiple financial reports into one interactive and dynamic visualization solution. With separate report pages for each financial component — Revenue, Expenses, Purchases, Payments, and an Overview — the dashboard provides a 360-degree view of the company’s financial performance.

---

## 🎯 Objectives

- ✅ Centralize and visualize financial data from multiple Excel files
- ✅ Provide real-time insights to help management make data-driven decisions
- ✅ Enable department-wise, category-wise, and time-based analysis
- ✅ Identify trends, outliers, and patterns in revenue and expenses
- ✅ Reduce manual efforts and enhance financial transparency

---
## 📚 Table of Contents

| Report Page        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **📌 Overview**     | A summary of key business KPIs including total revenue, total expenses, profit margin, and financial highlights |
| **💰 Revenue**      | In-depth revenue trends by product, department, and time period             |
| **📉 Expenses**     | Tracks fixed and variable costs, highlights spikes, and shows monthly breakdowns |
| **🛒 Purchases**     | Vendor-wise purchase analysis, item/category breakdown, and cost comparisons |
| **💳 Payments**     | Monitors payment transactions, pending amounts, and preferred payment methods |

---
## 📁 Data Sources

The dashboard pulls data from the following Excel files:
- `RLS Bridge Table.xlsx`
- `RLS Main Table.xlsx`
- `Report Page Name.xlsx`
- `findata-m5KLx91yPatZlJqV.xlsx`

> ⚠️ **Note:** Make sure to update the data source credentials in Power BI Service and configure your **Personal Gateway** to enable scheduled refresh.

---
## 🖼️ Report Pages with Screenshots & Explanation  ✅

### 📌 Overview Page

![image](https://github.com/user-attachments/assets/0aca7d33-334c-4eb9-8d1c-7d69b603bb2c)

This page provides a snapshot of all critical business KPIs — total revenue, expenses, net profit, and overall financial health. It's designed for CXOs and top-level decision-makers to quickly grasp the company’s financial standing.

## 🔘 Details Button Functionality (Based on Overview Report)
The **Details Button** enhances interactivity within the Overview Report by allowing users to dive deeper into specific segments of the data.
![Screenshot 2025-04-13 105607](https://github.com/user-attachments/assets/e23288cf-8d7c-461d-8233-d05dd1e2fe64)

**📌 Next Steps**

![image](https://github.com/user-attachments/assets/34215ed9-0ea3-4986-afe5-b9e18a9d51c8)

![image](https://github.com/user-attachments/assets/9d2fe1c5-8449-4932-ab27-fcd90a44ac26)

### ✨ How It Works:
- The button is **initially disabled**.
- When you **click on any bar or pie chart** from the Overview Report (e.g., Revenue, Expenses, Payment), the **Details Button gets enabled and turns red**.
- Clicking the now-active button takes you to a **dedicated details page**, showing a **breakdown of the selected category**.

### 🎯 Purpose:
This feature allows users to:
- Explore data at a granular level
- Understand what contributes to each category
- Make better data-driven decisions based on detailed insights

> Example: Click on the "Expenses" section in the pie chart, then click the red Details button to view a detailed breakdown of all expense components.


## 📊 Overview Details Summary Report

The **Overview Details Summary Report** provides a concise and interactive snapshot of the business's financial data, segmented by key categories such as Revenue, Purchase, Expenses, Payment, and Others.

![Screenshot 2025-04-13 102805](https://github.com/user-attachments/assets/ea263cb4-a91e-4c64-888c-1eb693f1bb3a)

### 🧮 Matrix Visual (Category + Details)

This matrix visual breaks down each main financial category into detailed sub-categories, allowing stakeholders to quickly understand the structure and flow of transactions. It includes:

- **Revenue**:
  - Credit Sales
  - Cash Sales
  - Discounts
- **Purchase**:
  - Raw Material Purchase
  - Stock Refill
- **Expenses**:
  - Operational Expenses
  - Salary Payments
  - Utilities
- **Payment**:
  - Received Payments
  - Pending Payments
- **Other**:
  - Miscellaneous Entries
  - Adjustments

This visual helps in identifying patterns, anomalies, and areas of financial concern or growth at a granular level.

### 🌳 Treemap Visualization (Category-wise)

The treemap provides a proportional view of the total volume or amount by each major category (Revenue, Expenses, etc.). Larger blocks represent higher financial weights, making it easier to visually compare the impact of each category on overall finances.

This visual is useful for:
- Quickly grasping dominant cost or income areas
- Identifying categories that require more attention
- Presenting financial distribution in an engaging format

### 🔍 Purpose

The goal of this report is to enable data-driven decision-making by summarizing and visually representing the financial health of the business. It helps stakeholders to:
- Monitor performance
- Understand financial flow
- Plan budgets and strategies
  

## 📈 Overview Trends: Revenue vs Expenses Dashboard

This section of the dashboard provides a comprehensive visual analysis of **Revenue vs Expenses** across different **regions**, **years**, and **countries** to help uncover financial trends and regional performance variations over time.

![Screenshot 2025-04-13 103659](https://github.com/user-attachments/assets/7106e0d8-e7c2-47bf-8f1a-e86b82e2c9d3)

### 📊 Trend Line Chart (Region & Year-wise)

The **line chart** shows the trend of revenue and expenses **over the years**, segmented by **region**. This allows us to:

- Understand how revenue and expenses evolve year by year in each region.
- Identify high-performing regions or those with increasing costs.
- Detect trends like seasonal spikes, dips, or consistent growth.

### 📊 Stacked Bar Chart (Country-wise Comparison)

The **stacked bar chart** compares **Revenue vs Expenses** at a **country level**. It provides a side-by-side visual breakdown which helps in:

- Analyzing which countries contribute most to revenue or incur high expenses.
- Spotting imbalances between income and expenditure.
- Comparing financial performance across different countries in a single view.

### 🔍 Key Insights

- Track financial trends over time and geography.
- Make informed business decisions by identifying profitable or underperforming areas.
- Helps in planning, forecasting, and resource allocation with a regional and global lens.



### 💰 Revenue Page

![image](https://github.com/user-attachments/assets/e98c7a4c-f42c-439a-949e-286d360c4a15)
Displays trends in revenue generation across time periods, and product lines. Helps identify top-performing segments, revenue growth patterns, and seasonal variations.

## 💰 Revenue Details Summary Report

The **Revenue Details Summary Report** offers an in-depth breakdown of revenue streams through interactive visuals, making it easier to analyze income sources and regional contributions.

![image](https://github.com/user-attachments/assets/289e7466-6d05-4314-9753-a17a9ee95cd2)

### 📊 Matrix Visual (Category-wise Breakdown)

This matrix visual presents revenue segmented by **main categories** and their associated **subcategories**:

- **Main Categories:**
  - Revenue
  - Others

- **Subcategories/Details:**
  - Credit Sales  
  - Cash Sales  
  - Dividend Income  
  - Exchange Gain and Loss  
  - Interest Income  
  - Sales Return  

This helps in understanding:
- What components contribute to total revenue
- The balance between different revenue sources (e.g., cash vs credit)
- Adjustments or reductions in revenue (e.g., returns, losses)

### 🌍 Treemap Visual (Country-wise Distribution)

The treemap visual displays **country-wise revenue contribution**, where each block represents a country sized by its revenue share.

This visual helps:
- Identify top revenue-generating countries
- Compare regional performance at a glance
- Detect low-performing markets

### 🎯 Purpose

This report empowers stakeholders to:
- Monitor and analyze the composition of revenue
- Evaluate performance across sales channels and regions
- Make data-backed decisions to optimize financial outcomes


## 📈 Sales Overview Details (Financial Year-wise)

This visual presents a clear overview of **Net Sales across different financial years** using a dynamic and color-coded column chart. It helps users track performance growth and identify key trends year by year.

![image](https://github.com/user-attachments/assets/e1c1e97a-af8d-44ce-8aea-586982c9323c)

### 🔍 Chart Description:

- **Type**: Column Chart
- **Title**: FY Wise Net Sales Trends
- **Y-Axis**: Net Sales (in ₹)
- **X-Axis**: Financial Years (2017-18 to 2020-21)
- **Color Scale**:  
  - 🔴 Red = Low Sales  
  - 🟡 Yellow = Moderate Sales  
  - 🟢 Green = High Sales  

### 📈 Data Highlights:

| Financial Year | Net Sales (₹) | Sales Level   |
|----------------|----------------|----------------|
| 2017-18        | 1,070,386      | 🔴 Low         |
| 2018-19        | 7,791,278      | 🟡 Moderate    |
| 2019-20        | 12,087,838     | 🟢 High        |
| 2020-21        | 13,267,782     | 🟢 Highest     |

### 🎯 Key Insights:

- Sales increased **consistently** over the years.
- The **highest growth** was seen in **FY 2020-21**.
- A dynamic legend (color scale) visually shows sales strength from **1.07M to 13.27M**.
- Provides a quick snapshot of business growth over time.

### ✅ Business Use Case:

This visual helps:
- Monitor historical sales trends  
- Identify successful years for strategic planning  
- Understand the impact of decisions on yearly sales  
- Drill down into high/low performance years for more detail

> 💡 Click on any bar to enable the **Details** button and navigate to the detailed sales breakdown report.

# Sales Summary Details Analysis

![image](https://github.com/user-attachments/assets/7f1a9431-0f1b-4d2d-8db6-f383c3c481ef)

# 📊 Sales Trend and YOY Growth Page

This page presents a detailed analysis of **sales trends** and **Year-on-Year (YOY) growth** across different financial years, months, and quarters. It allows users to interactively explore sales performance over time, compare different periods, and easily spot trends with color-coded visualizations. 🌈📈

![image](https://github.com/user-attachments/assets/da9625d5-8925-4063-8c0d-02d23dc7a376)

![image](https://github.com/user-attachments/assets/bc0c7858-a014-4f55-84a9-eb6d3256febb)

![image](https://github.com/user-attachments/assets/02d6cc61-8180-4169-8973-8f2d49710114)

## 🚀 Features

### 🔘 1. Interactive Buttons
Switch between different time granularities using toggle buttons:
- 🗓️ **Year** – View sales data by financial year.
- 📅 **Month** – Breakdown of monthly sales performance.
- 🧮 **Quarter** – Explore sales trends on a quarterly basis.

### 📊 2. Small Multiple Bar Chart
Sales data is displayed using **small multiple bar charts**:
- 📌 Easy visual comparison across years, months, or quarters.
- 🔄 Auto-update when toggling between Year, Month, or Quarter.

### 📅 3. Financial Year Analysis (2017–2021)
Focuses on the **financial years** from 2017-18 to 2020-21:
- 🟢 **2017-18**: Sales = `1,070,386` (YOY Growth = `0%` – First year of business)
- 🟡 **2018-19**: Sales = `7,791,278` (YOY Growth = `627.89%`)
- 🟡 **2019-20**: Sales = `12,087,838` (YOY Growth = `55.15%`)
- 🔴 **2020-21**: Sales = `13,267,782` (YOY Growth = `36.99%`)

### 🌈 4. Color-Coded Performance Visualization
Sales bars are color-coded to highlight performance levels:
- ✅ **Green (Max Sales)** – Highest performance
- 🟨 **Yellow (Medium Sales)** – Moderate performance
- ❌ **Red (Min Sales)** – Lowest performance

---

## 🎯 Purpose of This Page
The goal of this page is to deliver an **interactive and intuitive experience** that allows users to:
- 📈 Track sales performance across time
- 🧠 Identify trends in YOY growth
- 🧩 Make informed decisions based on historical data insights

---

## 🛠️ How to Use
1. **Click the Buttons**: Switch views between **Year**, **Month**, or **Quarter**.
2. **Watch the Colors**: 
   - 🟢 Green = High performance
   - 🟨 Yellow = Moderate
   - 🔴 Red = Low performance
3. **Explore the Trends**: Read the bar charts to track growth or dips and strategize accordingly.

---

## ✅ Conclusion
This page serves as a powerful tool to visualize and analyze business performance across multiple time periods. With **interactive elements** and **dynamic color formatting**, it becomes easier than ever to gain actionable insights and make **data-driven decisions**. 💡📊


> 💬 *“Turning numbers into knowledge!”*


---
### 📉 Expenses Page  
Helps analyze operational and fixed costs with visuals that highlight monthly spikes or savings opportunities.

![image](https://github.com/user-attachments/assets/70a5f9b3-d5fc-452c-a195-5263024b78bd)  

# 💰 Headwise Expenses Analysis
This page provides a comprehensive breakdown of **expenses categorized by different heads**, enabling a detailed understanding of where and how resources are being spent. It allows businesses to track, compare, and control their expenditures more effectively over time.

![image](https://github.com/user-attachments/assets/834fa76b-3947-444f-b3ae-63c268c3e4af)

# 🛒 Purchase Overview Analysis
This page provides a detailed overview of the organization's purchasing activity, offering powerful insights into purchase trends and procurement efficiency. It helps stakeholders monitor and analyze purchasing patterns over time to support smarter, data-driven decision-making.

![image](https://github.com/user-attachments/assets/6f313acf-2331-4612-9104-1e417fb94e18)

# 🔁 Purchase vs Revenue Comparison Analysis

This page offers a side-by-side analysis of **Purchases vs Revenue**, helping businesses evaluate how procurement costs align with the income generated. It delivers key insights into **profitability**, **cost efficiency**, and **business growth trends**.

![image](https://github.com/user-attachments/assets/bf5105ab-a37e-4d7f-af61-25b7c689c80c)


## 📌 Key Features

### 💵 1. Revenue vs Purchase Tracking
- Compare **Total Purchase Cost** with **Revenue Earned** across time.
- Visual indicators highlight whether revenue growth is outpacing procurement expenses.

### 📅 2. Time-Based Comparison
- Analyze trends by:
  - 📆 **Year**
  - 📈 **Quarter**
  - 📊 **Month**
- Understand seasonal shifts in profitability and operational efficiency.

## 🎯 Purpose of This Page

The goal of this analysis is to evaluate **how effectively purchases are being converted into revenue**. It helps stakeholders:

- ⚖️ Balance procurement and sales
- 🔎 Monitor profitability trends
- 📉 Identify inefficiencies or overspending
- 💰 Optimize purchasing strategies to boost margins

## ✅ Conclusion

This analysis equips your business with the insight to manage costs while maximizing revenue. It provides a clear lens into how purchases translate into earnings — enabling smarter financial decisions and stronger profit strategies. 📊💼📈

---

# 💳 Payment Overview Analysis

This page delivers a comprehensive breakdown of **organizational payment trends** over multiple time periods and categories. With interactive and visually enriched insights, it helps uncover how funds are allocated and tracks changes in payment patterns over the years.

![image](https://github.com/user-attachments/assets/0debd8b7-3033-4f25-adf6-737178b7409b)


---

## 📈 Visual 1: Payment Trend Over Time

An interactive **line chart** visualizes payments distributed across:

- 📅 **Financial Year** (2017–2021)
- 📆 Drill-down: **Quarter → Month**

This allows users to deeply explore when the highest payments occurred and how expenses evolved throughout the year.

### 🔍 Data Highlights:
| Financial Year | Total Payment |
|----------------|----------------|
| 2017-18        | ₹819,032       |
| 2018-19        | ₹4,940,894     |
| 2019-20        | ₹9,007,164     |
| 2020-21        | ₹9,127,394     |
| **Grand Total**| **₹23,894,484**|

🧩 Insight: Payments showed consistent growth year over year, with a major spike observed from 2018-19 onwards.

---

## 🍩 Visual 2: Category-wise Payments

A **donut chart** represents how payments are distributed across various categories, offering insights into the nature of expenses.

### 📊 Category-wise Breakdown:
| Payment Category                              | Amount (₹)   |
|-----------------------------------------------|--------------|
| Payment - Credit Expenses                     | 10,046,588   |
| Transfer of Net Profit to Retained Earnings   | 8,191,236    |
| Bank to Cash Transfer                         | 2,177,866    |
| New Loan Raised @ 6%                          | 1,287,254    |
| Payment of Final Dividends                    | 769,600      |
| Payment of Interim Dividends                  | 750,580      |
| Tax Payment for the Previous Year             | 671,360      |

✨ **Net Sales** is elegantly displayed in the **center of the donut** as a card visual – keeping business context upfront while analyzing expenses.

---

## 🎯 Purpose of This Page

This page helps businesses:

- 📊 Analyze payment behaviors across time and categories
- 🧮 Track financial obligations like taxes, dividends, and retained earnings
- 💡 Identify major spending heads and optimize future budgets
- 🔁 Monitor cyclical patterns in payments through drilldowns (Year > Quarter > Month)

---

## 🛠️ How to Use

1. **Use Drill-downs** in the line chart to explore monthly or quarterly payment trends.
2. **Review Category Spend** using the donut chart to identify high-expense areas.
3. **Observe Net Sales** placed at the center of the donut chart for business context.

---

## ✅ Conclusion

The Payment Overview Analysis page serves as a strategic tool to understand payment flows, visualize major expenditures, and support financial planning. With dynamic filtering and clean visuals, it allows for an intuitive and data-driven assessment of financial activity. 📊💸📈

---

> 💬 *"To control your finances, first understand your payments."*

## 🛠️ Key Dashboard Features

- 🎯 **Drillthrough Functionality**: Clicking on any table or chart element enables a “Details” button that leads to a focused drill-through page showing a full data breakdown.
  
- 🔄 **Sync Slicers**: Filters like Date, Department, or Category sync across all report pages — ensuring consistency in exploration.

- 🎛️ **Dynamic Buttons & Navigation**: Custom buttons provide smooth navigation between pages, while visibility toggles (like showing/hiding charts) enhance UX.

- 👁️ **Conditional Formatting**: Automatically highlights spikes in expenses, profit dips, or revenue jumps.

- ⏳ **Time Intelligence**: Uses DAX to enable YoY, QoQ, MoM comparisons.

- 📱 **Responsive Layout**: Optimized layout works well on different screen sizes when viewed in Power BI Service or mobile app.

---

## ⚙️ Tech Stack

- Power BI Desktop  
- Excel (.xlsx) Files  
- Power BI Service  
- DAX, Power Query  
- Power BI Gateway for Auto Refresh  

---
## 🔐 Security Implementation

### 🔹 Row-Level Security (RLS)
User-specific access implemented — for example, Sales Managers can only view their department data.

### 🔹 Page-Level Security
Through navigation & button logic, certain users are restricted from accessing non-relevant report pages.

---

## 🔁 Scheduled Data Refresh

Deployed on Power BI Service with **Personal Gateway + Scheduled Refresh** enabled to keep insights real-time and reliable.

![image](https://github.com/user-attachments/assets/8fe22bd0-692e-4ed3-9df7-8671569e5551)

---

## 🔁 Sharing the Dashboard
After the scheduled refresh is set, the dashboard will be shared with relevant stakeholders according to the following process:
1. Publish the dashboard to Power BI Service.
2. Share the dashboard link or embed it within a company portal or report.
3. Set permissions based on user roles for secure access.

---

## 📌 Conclusion

This **Power BI End-to-End Financial Multi-Report Dashboard** empowers management with a centralized view of the entire financial ecosystem — from revenue and expenses to purchases and payments. With interactive visualizations and real-time insights, decision-makers can:

📈 Track growth trends and revenue performance  
📉 Identify and reduce unnecessary expenses  
💳 Monitor payment flows and vendor engagements  
🧾 Make data-driven purchasing decisions  

Ultimately, this dashboard transforms scattered financial data into an intuitive and actionable decision-making tool — helping businesses operate smarter, faster, and more strategically.

---

## 👨‍💻 About the Author
- **Name**: Goutam Kuir
- **Contact**: gkuiri26@gmail.com
- **LinkedIn**: [Goutam Kuir](https://www.linkedin.com/in/goutam-kuiri-949b632a6)
- **Medium**: [Goutam Kuir](https://medium.com/@goutamkuiri)

