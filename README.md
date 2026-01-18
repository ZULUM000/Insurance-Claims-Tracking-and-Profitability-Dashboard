# 🛡️ Insurance Claims & Renewal Management System

### 📊 Project Overview
This project focuses on the development of a comprehensive **Claims and Renewal Management System** using **Power BI**. 

In the context of the Nigerian insurance sector—where regulatory demands (such as the **NIIRA 2025**) are increasing the pressure for digitization—manual tracking of policy life cycles is no longer sustainable. We built this solution to transition from reactive, spreadsheet-based management to a proactive, data-driven operational model.

The system is designed to provide Regional Managers and Executives with an immediate view of policy maturity, agent performance, and revenue flow.

---

## 🚩 The Problem
Many insurance firms struggle with the **"Renewal Gap."**
* **Manual Tracking:** Identifying which policies are maturing requires manually sorting through years of data. For example, if a client purchased a **10-year tenure policy in 2015**, the system needs to flag it for action in **2025**. Doing this manually is prone to human error.
* **Opaque Performance:** It is difficult to track which agents are driving revenue versus which are falling behind without consolidating multiple reports.
* **Regulatory Risk:** Delayed claims processing or missed renewals can lead to compliance penalties.

## 💡 The Solution
We developed an interactive dashboard that automates the logic of policy tracking. By integrating **Start Dates** and **Tenure Lengths**, the system automatically calculates maturity dates and flags policies due for renewal.

### Key Features
* **Automated Renewal Logic:** The dashboard dynamically filters policies based on their `Start Year` and `Tenure` to isolate current-year maturities.
* **360° Operational Drill-Down:** Users can drill down from high-level Regional performance to individual Branch and Agent metrics.
* **Financial Visibility:** clear tracking of `Total Annual Premium`, `Claims Processed`, and `Profitability Ratios`.
* **Agent Leaderboards:** A ranked view of sales performance to assist HR and Management in appraisals and incentive distribution.

---

## 🛠️ Technical Approach

### 1. Data Transformation (ETL)
* **Data Cleaning:** Handled missing values and standardized naming conventions for policy types (e.g., Life, Fire, Vehicle) to ensure accuracy.
* **Logic Creation:** Created conditional columns to calculate `End Year` based on the formula:
    > *Start Year + Tenure = Maturity Year*
* **Modeling:** Established relationships between the `Transaction Data`, `Branch Data`, and `Agent Tables` to allow for cross-filtering.

### 2. Dashboard Design & Visualization
* **KPI Cards:** High-level metrics for Total Premium, Total Claims, and Active Policies.
* **Matrix Tables:** Used for the detailed "granular" view, allowing managers to see specific policyholder names and payment statuses without leaving the dashboard.
* **Slicers & Filters:** Added interactive slicers for `Year`, `Region`, and `Policy Type` to empower users to answer their own questions.

---
<img width="1446" height="812" alt="image" src="https://github.com/user-attachments/assets/fe8f2118-b2e4-42cd-a633-97d45a002fc5" />

## 📈 Insights & Business Impact
By deploying this system, we aim to achieve the following outcomes:
1.  **Reduced Churn:** By identifying maturing policies *before* they expire, the retention team can contact clients early, significantly boosting renewal rates.
2.  <img width="1450" height="812" alt="image" src="https://github.com/user-attachments/assets/9f2f3431-5b90-4215-b4b4-471e5fd187ab" />

3.  **Operational Efficiency:** Eliminates hours of manual spreadsheet work previously required to generate weekly reports.
4.  **Data-Driven Appraisals:** Performance reviews for Regional Managers and Agents are now based on transparent, real-time data rather than subjective feedback.
<img width="1445" height="807" alt="image" src="https://github.com/user-attachments/assets/a606563b-4d4a-4329-8ea2-ae5cea38dfe8" />

---

## 🚀 Future Improvements
* **Predictive Analytics:** Integrating Python scripts to predict the likelihood of a customer churning based on payment history.
* **Mobile Layout:** Optimizing the dashboard specifically for mobile view to allow field agents to access data on the go.

---

## 👤 Author
**Chukwuebuka Jeremiah Enoch** *Data Analyst & Business Intelligence Developer*

Let's connect on [LinkedIn](https://www.linkedin.com/) to discuss how data can transform the African financial sector.
