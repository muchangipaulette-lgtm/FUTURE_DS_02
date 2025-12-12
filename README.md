# ⭐ **Facebook Ads Performance Analysis Dashboard – Power BI**

This repository contains a complete end-to-end Facebook Ads Performance Analysis project built using **Power BI**, leveraging advertising campaign data to uncover insights on audience behavior, spending efficiency, and conversion performance.
The goal of this project is to demonstrate real-world marketing analytics skills used by digital teams to evaluate ad performance and optimize future campaigns.


## 📊 **Project Overview**

This project analyzes simulated Facebook Ads Manager data containing key ad metrics such as impressions, clicks, spend, age groups, gender, and conversions. The insights are visualized in an interactive Power BI dashboard that helps answer essential marketing questions:

* Which ads performed best?
* How engaged were different audience groups?
* Which interests drove the highest conversions?
* How efficiently was the advertising budget spent?
* What improvements can be made to boost CTR and conversions?


## 🔍 **Key Features**

### ✔ **Interactive Power BI Dashboard**

Includes visually rich and interactive views such as:

* Total Impressions, Clicks & Spend Overview
* CTR, CPC & CPA Performance Cards
* Top 10 Performing Ads (Treemap)
* Audience Performance by Age & Gender
* Conversion Rate & CPC by Gender (Donut Chart)
* Daily Trends of Clicks, Impressions & Spend
* Total Conversions by Interest
* Approved Conversion Waterfall

### ✔ **Slicers Included**

* Age
* Reporting Date

These allow users to drill into specific audience segments.


## 🧰 **Tools & Technologies**

| Tool            | Purpose                                 |
| --------------- | --------------------------------------- |
| **Power BI**    | Dashboard creation & data visualization |
| **Excel / CSV** | Raw dataset storage                     |
| **DAX**         | Custom measure calculations             |
| **GitHub**      | Project hosting & documentation         |


## 🗂 **Dataset**

The dataset includes the following fields:

`ad_id`, `reporting_start`, `reporting_end`, `campaign_id`, `age`, `gender`, `interest1`, `interest2`, `interest3`, `impressions`, `clicks`, `spent`, `total_conversion`, `approved_conversion`


## 📈 **Insights & Recommendations**

### **1. Age Group Optimization**

The **30–34** age group generated the highest total conversions and strong CTR performance. Increasing budget allocation to this group is likely to improve ROI.

### **2. Stronger Performance from Female Audiences**

Females showed more efficient conversion performance. Consider designing creatives tailored to this demographic.

### **3. Interest Segments Require Cleanup**

Certain interest groups show low conversions despite high spend. Reducing spend on low-performing interests can help reallocate budget toward more profitable segments.

### **4. Scale Top-Performing Ads**

The treemap highlights ads with consistently high click volumes. Analyze the elements of these ads (creative, copy, CTA) and consider scaling or cloning them.

### **5. Improve Overall CTR**

The dashboard indicates a **0.02% CTR**, which is below expected Facebook benchmarks. Creative refresh, stronger CTAs, and audience alignment could help lift engagement.

### **6. Tighter Conversion Optimization**

The waterfall chart shows disproportionate increases in spend relative to approved conversions. This signals opportunities in landing page optimization, audience refinement, and creative relevance.

### **7. Stabilize Daily Performance**

Daily trends show irregular fluctuations. Introduce delivery pacing, A/B testing, and frequency monitoring to maintain consistent campaign engagement.

## 🗂 **Repository Structure**

📁 FUTURE_DS_02/
 - Facebook_Ads_Dashboard.pbix     # Power BI Dashboard
 - dataset.csv or dataset.xlsx     # Raw dataset (optional)
 - screenshots/                    # Dashboard screenshots
 - README.md                       # Project documentation

## 🚀 **How to Use This Project**

1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Interact with the filters and visuals
4. Explore audience insights and ad performance trends


## 💡 **Future Enhancements**

* Add revenue & ROI calculation
* Auto-refresh using a connected data source
* Publish report to Power BI Service
* Incorporate Looker Studio comparison dashboard


## 👩‍💻 **Author**

**Paulette Muchangi**

Data Analyst
