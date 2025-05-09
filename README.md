# 📊 Shield Insurance Analysis – Power BI Report  
*A project from my internship at AtliQ Technologies (Codebasics Power BI Job-Ready Program)*

[🔗 Live Power BI Report](https://app.powerbi.com/groups/me/reports/594c8264-5823-4d27-a316-8446d109005a/c09573defdd0410a2cd3?experience=power-bi) • [🎙️ Audio Presentation](https://youtu.be/PMYL6mf0oFM)

---

## 🏢 About the Company

**Shield Insurance** is a fictional, trusted insurance provider in India offering comprehensive coverage for both individuals and businesses. The company focuses on:

- Customer satisfaction  
- Tailored insurance plans across all age groups and cities  
- Secure and reliable services for policyholders

---

## 🎯 Business Objectives

The key analytical goals of this project were to:

- Track **total revenue** and **customer growth** trends  
- Monitor **daily KPIs** for revenue and acquisition  
- Analyze **city-wise** and **age-wise** segmentation  
- Evaluate **sales performance by channel**  
- Understand **policy preferences by age group**  
- Estimate **settlement behavior by age**  

The ultimate aim was to **identify growth opportunities**, **optimize offerings**, and **enhance sales channels**.

---

## 📁 Data Sources

Structured using a **Star Schema**, the report uses 5 main datasets:

| Dataset              | Description                                      |
|----------------------|--------------------------------------------------|
| `dim_customer.csv`   | Customer details (City, Date of Birth)           |
| `dim_date.csv`       | Date hierarchy (Months, Weekdays, Week Numbers)  |
| `dim_policies.csv`   | Policy metadata (Base Cover, Base Premium)       |
| `fact_premiums.csv`  | Premium payments and sales mode                  |
| `fact_settlements.csv`| Settlement percentages by age group             |

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**  
- **Power Query Editor & DAX**  
- **Microsoft Excel / CSV**  
- **Microsoft PowerPoint** (for presentation)  

---

## 🧠 Data Modeling Approach

We used a **Star Schema** for the data model, enabling:

- Accurate relationships  
- Simplified analysis  
- Effective performance in DAX measures  
- Seamless dashboard creation  

---

## 📊 Report Overview

### 🏠 Home Page

- Shield Insurance branding  
- Overview of dashboard focus areas  
- Navigation buttons to:  
  - **Overview**  
  - **Sales Mode Analysis**  
  - **Age Group Analysis**
  - **Guide**

---

### 📈 General View Page

- **Key KPIs**: Total Revenue, Total Customers, Daily Revenue Growth, Daily Customers Growth  
- **Customer by Age Group**
- **Revenue by City**
- **Monthly Revenue Trends**
- **Customer Segmentation by City**

---

### 💼 Sales Mode Page

- **Customer Split by Channel**: (Agent, Direct, App, Website)  
- **Revenue by Sales Mode**  
- **Monthly Revenue Trends by Mode**  

---

### 👥 Age Group Analysis

- **Policy Preferences by Age Group**
- **Settlement Expectation vs Age**
- **Sales Mode Preference by Age** 
- **Customer Count by Age Group**  
- **Monthly Activity by Age Group**  

---

## ✅ Final Recommendations

- 🎯 **Retain & Upsell**: Target 31–40 age group with personalized offers  
- 📱 **Grow Digitally**: Improve App & Website UX  
- 🧍‍♂️ **Target Gaps**: Focus on 18–24 and 65+ demographics  
- 🌆 **City Strategy**: Scale Delhi NCR success to other metro cities  
- 📉 **Risk Control**: Use smarter pricing for high-settlement age segments  

---

## 🔗 Links

- **Live Power-BI Dashboard**: [Access Here](https://app.powerbi.com/groups/me/reports/594c8264-5823-4d27-a316-8446d109005a/c09573defdd0410a2cd3?experience=power-bi)  
- **Presentation (Audio)**: [Listen Here](https://youtu.be/PMYL6mf0oFM)  
- **Finalized Client Mockup**: [Download](https://github.com/mohan1212576/Shield-Insurance-Analysis/blob/main/client_updated_mockup.pdf)  

---

## 🙏 Thank You!

This project was part of my internship with **AtliQ Technologies**, guided by the **Codebasics Power BI Job-Ready Program**.
