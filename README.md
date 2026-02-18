# HR-Analytics-Report
# Customer Churn Analytics Dashboard

## Project Overview
This project provides a multi-dimensional analysis of customer churn for a telecommunications provider. The dashboards identify key drivers of attrition, demographic patterns, and geographic hotspots to help stakeholders implement targeted retention strategies.

**Total Customers:** 6,687  
**Total Churn:** 1,796  
**Overall Churn Rate:** 26.86%

---

## Dashboard Descriptions

### 1. Executive Overview
The **Overview** dashboard provides a high-level summary of the company's health. It serves as the primary entry point for executives to understand the scale of churn.
* **Key KPIs:** Displays Churn Rate, Total Customer Count, and Total Churned Customers.
* **Contract Analysis:** A donut chart showing that **Month-to-Month** customers make up the largest segment (51.01%) and are likely the highest risk.
* **Geographic Map:** A bubble map of the United States identifying regional churn intensity.
* **Churn by Category:** Highlights that **Competitors** are the leading cause of churn (44.82%).

### 2. Churn Demographics
This page digs into *who* is leaving by analyzing age, seniority, and household composition.
* **Age-Based Churn:** A dual-axis chart shows that while customer volume is high in the 20–60 age range, the **Churn Rate spikes significantly for seniors (ages 65-80+)**, reaching over 40%.
* **Senior/Under 30 Matrix:** A table breaking down churn by age groups. Notably, customers who are both Seniors and not in the "Under 30" category show a high churn rate of **38.46%**.
* **Churn Reasons:** A detailed bar chart ranking specific pain points. The top reason is "Competitor made better offer," followed by "Competitor had better devices."

### 3. Groups and Categories
This dashboard explores the relationship between contract types, gender, and pricing.
* **Contract Type Comparison:** Compares Monthly vs. Yearly churn. The **Monthly churn rate (46.29%)** is nearly 7 times higher than the **Yearly rate (6.62%)**.
* **Gender Analysis:** Shows churn rates across Female, Male, and "Prefer not to say" categories, suggesting that gender does not significantly impact churn compared to contract type.
* **Monthly Charges:** A bar chart correlating the "Number of Customers in Group" with average charges, highlighting how pricing tiers influence retention.

### 4. Service Insights
Focuses on technical triggers and customer support performance.
* **Customer Service Calls:** Highlights that churned customers have a significantly higher average of **Customer Service Calls (Avg: 2-3)** compared to retained customers (Avg: <1) across almost every state.
* **Extra Charges:** Breaks down average extra international charges ($33.64) and extra data charges ($3.37), identifying potential "bill shock" triggers for churn.
* **State-by-State Service:** A line graph tracking service call frequency by state, helping identify regions where technical support may be underperforming.

---

## Key Findings
* **Contract Risk:** Month-to-month contracts are the primary driver of churn.
* **Competitive Pressure:** Nearly half of churn is due to competitors offering better deals or hardware.
* **Senior Vulnerability:** Older demographics are leaving at a disproportionately higher rate.
* **Support Correlation:** There is a direct correlation between the frequency of customer service calls and the likelihood of churn.

## Tools Used
* **Power BI / Tableau:** For data visualization and dashboard construction.
* **DAX / Calculated Fields:** Used for churn rate percentages and age binning.

## Dashboard Overview
![overview- page](https://github.com/user-attachments/assets/340cd049-7221-451a-bc2a-977da6405b06)
![insights](https://github.com/user-attachments/assets/9dd96c3e-7b81-4fb1-9303-5abba9660062)
![Groups and Categories - page](https://github.com/user-attachments/assets/52ab651f-3bb7-4969-80ed-364f7881d778)
![Churn Demographics-page](https://github.com/user-attachments/assets/974a8c69-80e0-48f2-8564-aa9aee4fdf6d)

