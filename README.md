# 🧾 Crossroad Insurance Claims - Data Analysis & Dashboard

![image](https://github.com/user-attachments/assets/89126074-7ff2-453f-8c29-aef95645019c)

## 📖 Introduction

In today’s data-driven insurance industry, analyzing claims data is essential for identifying operational inefficiencies, uncovering fraud, and improving customer satisfaction. This project focuses on an in-depth analysis of a fictional insurance dataset from Crossroad Insurance, with the goal of extracting meaningful insights from historical claim records.

By leveraging Excel for data preparation and  visualization, this project transforms raw insurance data into actionable intelligence. The resulting dashboard provides a clear view of customer behavior, claim trends, policy performance, and potential fraud indicators—equipping decision-makers with the information needed to optimize processes and reduce risk.


## 🎯 Objective

The goal of this project is to perform a comprehensive analysis of insurance claims data to identify patterns in claim approvals, detect potential fraud, and evaluate policy and customer performance. By transforming raw data into interactive visuals and KPIs, this project aims to:

- Support business decisions through data-backed insights  
- Highlight high-risk areas such as fraudulent claims and policy types  
- Reveal customer trends by age, gender, and claim behavior  
- Recommend strategies to optimize claims processing and policy offerings

The final output includes a clean dataset, insightful analysis, and an interactive dashboard built with Microsoft Excel.


## Data Dictionary:

## 🗂️ Dataset Description

The primary dataset contains **500 records**. Below is a summary of the key columns:

| Column Name        | Description                                                  |
|--------------------|--------------------------------------------------------------|
| Customer ID        | Unique identifier for each policyholder                      |
| Gender             | Gender of the customer (Male/Female)                         |
| Age Group          | Age category (e.g., Young, Middle-aged, Old)                 |
| Region             | Geographic location of the customer                          |
| Vehicle Type       | Type of insured vehicle (Car, Motorcycle, etc.)              |
| Policy Type        | Type of insurance policy (Health, Auto, Home)                |
| Premium Amount     | Annual premium paid by the customer                          |
| Total Claim Amount | Total amount claimed by the customer                         |
| Claim Status       | Status of the claim (Approved, Pending, Rejected)            |
| Tenure             | Number of years the customer has held the policy             |
| Fraudulent         | Indicator of whether the claim was flagged as fraudulent     |


## 🧪 Methodology

This project followed a structured data analytics workflow to ensure accuracy and insight-driven results. The methodology includes the following key steps:

### 1. Data Ingestion
- Loaded the dataset from Excel 
- Explored all sheets to understand the structure and purpose of each

### 2. Data Cleaning and Transformation 
- Removed duplicate entries and standardized column formats
- Handled missing or inconsistent values in key fields (e.g., Claim Status, Gender)
- Converted data types (e.g., string to number, dates, and booleans)
- Created derived fields such as:
  - Age Category (Young, Middle-aged, Old)
  - Fraud Flag (Yes/No)
  - Total Premium & Claim Ratios

### 3. Data Analysis
- Explored trends across gender, age group, and vehicle type
- Analyzed claim distribution by policy type and region
- Examined seasonal claim trends (monthly breakdown)
- Investigated fraud patterns by demographic and policy features
- Calculated key metrics: approval rate, total claims, average claim amount

### 4. Dashboard Design (Excel)
- Built interactive charts and cards for:
  - Claim amounts by gender, age, policy type, and time
  - Fraud detection and status breakdown
  - Monthly trend visualization
- Used slicers for dynamic filtering by category (e.g., Gender, Region)

### 5. Insight Generation
- Interpreted visual patterns and statistical trends
- Highlighted operational inefficiencies and areas of business risk
- Proposed targeted recommendations based on data evidence

   ### Preview Of Data before Cleaning:

  ![image](https://github.com/user-attachments/assets/4021d6a4-71e4-4070-92ee-c562af5019f5)

  
### Preview of data after Cleaning:

![image](https://github.com/user-attachments/assets/88526259-7927-4465-94ae-2933716b8dc3)

### Pivot Table:

![image](https://github.com/user-attachments/assets/ff6f99df-3cdb-4dd2-8d08-d540fe70535a)

### Visualization:

![image](https://github.com/user-attachments/assets/3d041c4b-ebb4-4a00-b8b4-d1f7f4458346)

## Visualization Insights:


- **Total Claims**: 500  
- **Total Claim Amount**: $12,525,490.69  
- **Average Claim Amount**: $25,050.98  

---

### 📊 Claim Status

- **Approved**: 172  
- **Rejected**: 180  
- **Pending**: 148  

> ✅ *Recommendation:* Optimize workflows to reduce pending claims.

---

### 👥 Gender-wise Claim Amount

- **Male**: $6,495,261.74  
- **Female**: $6,030,228.95  

> 💡 *Observation:* Claims are fairly balanced by gender.

---

### ⚠️ Gender & Fraud Analysis

- **Female Fraudulent**: 28%  
- **Male Fraudulent**: 24%  
- **Male Non-Fraudulent**: 26%  
- **Female Non-Fraudulent**: 22%  

> ✅ *Recommendation:* Enhance fraud detection, especially for female segments.

---

### 🕒 Claims by Month

- Peak claims in **March (52)**, **April (52)**, and **May (47)**  
- Lowest in **September (33)**

> ✅ *Recommendation:* Prepare for spikes during Q1–Q2.

---

### 🏠 Policy Type Claim Amount

- **Health**: $4.43M  
- **Auto**: $4.36M  
- **Home**: $3.73M

> ✅ *Recommendation:* Focus risk strategies on Health and Auto policies.

---

### 🧓 Age Group Claim Amount

- **Middle-aged**: $4.52M  
- **Old**: $4.33M  
- **Young**: $3.68M

> ✅ *Recommendation:* Tailor products for middle-aged customers.

---


## ✅ Strategic Recommendations

Based on the analysis of the insurance claims data and the dashboard insights, the following recommendations are proposed to improve operations, mitigate fraud, and enhance customer satisfaction:

### 1. 🔄 Streamline Claim Processing
- **Action:** Reduce the high number of pending claims (148 out of 500).
- **Why:** Delayed claim resolutions can damage customer trust and increase service costs.
- **How:** Automate part of the approval pipeline using predefined eligibility rules and invest in digital claim tracking systems.

### 2. 🕵️‍♂️ Strengthen Fraud Detection Mechanisms
- **Action:** Focus fraud prevention efforts on segments with higher fraudulent claim percentages, especially among female policyholders.
- **Why:** 28% of fraudulent claims were from females—indicating potential fraud trends.
- **How:** Implement machine learning fraud scoring, flagging high-risk profiles early in the claim lifecycle.

### 3. 📆 Prepare for High-Claim Months
- **Action:** Allocate more resources during high-activity months (March to May).
- **Why:** Claim volume spikes were observed in Q1–Q2, leading to potential operational overload.
- **How:** Forecast workload using historical data and implement temporary staffing or system scaling.

### 4. 🚗 Review Underperforming Policy Types
- **Action:** Reevaluate risk models for Health and Auto policies.
- **Why:** These policy types accounted for the highest total claim amounts and potential losses.
- **How:** Use claim-to-premium ratio analysis to determine which products are underpriced or overexposed.

### 5. 🧓 Tailor Services to High-Claim Age Groups
- **Action:** Develop targeted offerings for middle-aged customers.
- **Why:** This group submitted the highest total claims ($4.52M), likely due to broader insurance coverage.
- **How:** Introduce loyalty programs, custom premium discounts, or family policy bundles.

### 6. 📊 Deploy Customer Behavior Monitoring
- **Action:** Monitor claim frequency, tenure, and region patterns for better segmentation.
- **Why:** Some customer groups might pose higher risks or opportunities for upselling.
- **How:** Use dashboards and alerts to track anomalies and customer trends in real-time.


![image](https://github.com/user-attachments/assets/9798a692-de51-42a5-af83-3e94dd4c3aa4)

For any collaborative work or gigs, reach out to me at:

📧 Email: Bosschuks97@gmail.com  📞: 07064106675



