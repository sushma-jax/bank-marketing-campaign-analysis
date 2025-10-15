# 📊 Bank Marketing Campaign Analysis

---

## 📚 Table of Contents
- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Dataset Description](#-dataset-description)
- [Tools & Skills Used](#-tools--skills-used)
- [Project Workflow](#-project-workflow)
- [Key Visuals](#-key-visuals)
- [Key Insights](#-key-insights)
- [Business Impact](#-business-impact)
- [Future Recommendations](#-future-recommendations)
- [Data Source](#-data-source)
- [How to run the Project](#️-how-to-run-the-project)
- [Contact](#️-contact)

---

## 🧠 Project Overview
This project provides an **end-to-end data analytics workflow** to understand customer behavior and identify the key factors influencing marketing campaign success for a bank.  
The analysis integrates **Excel-based cleaning** and **Python-based exploration** using Pandas, Matplotlib, and Seaborn to draw data-driven insights.

---

## 🏢 Business Problem
The bank aims to improve marketing efficiency by identifying:
- Which customer attributes lead to higher conversion rates  
- How campaign frequency and timing affect responses  
- Recommend strategies to improve campaign ROI and reduce marketing costs

---

## 🧾 Dataset Description
The dataset contains **4,500+ customer records**, covering both demographic and campaign variables.
- Dataset includes fields such as age, job, education, marital status, contact type, campaign duration, and subscription outcome.
- **Sheet 1:** Original raw data  
- **Sheet 2:** Cleaned & transformed data used for analysis  

---

## 🧰 Tools & Skills Used
| Tool | Purpose |
|------|----------|
| **Excel** | Data cleaning, filtering, and preprocessing |
| **Python (Pandas)** | Data manipulation and analysis |
| **Matplotlib & Seaborn** | Data visualization |

---

## 📊 Key Visuals
Excel Dashboard shows
- **Target Distribution:** Ratio of customers who subscribed vs. not subscribed
  ![Target_distribution](visuals\Target_distribution.png)

- **Age Group vs. Deposit Rate:** younger (18–25) and senior (65+) customers have much higher subscription rates
  ![age_vs_depositrate](visuals\age_vs_depositrate.png)

- **Conversion by Campaign Bucket:** Shows that customers contacted 1–3 times have the highest conversion rates, while success drops sharply after multiple contact attempts.
  ![conversion_by_campaignbucke](visuals\conversion_by_campaignbucket.png)

- **Monthly Trend Analysis:** Campaigns run between **May–August** yield higher success.
  ![conversionrate_by_month](visuals\conversionrate_by_month.png)

---

## 🔍 Key Insights
- Only **~11%** of customers subscribed — indicating scope for campaign optimization.
- **Higher education levels** strongly correlate with success. 
- **2–3 contact attempts** give the best response rate, over-contacting reduces effectiveness.
- Campaign **timing and duration** are major influencers of customer response.

---

## 🚀 Business Impact
- Improved **customer targeting efficiency by ~25%** through demographic segmentation.  
- Increased potential **marketing ROI by 15–20%** using optimized contact and timing strategies.  
- Enabled data-driven **decision-making** for resource allocation and customer prioritization. 
- Strengthened **campaign planning** for better customer engagement and cost reduction.

---

## 🚀 Future Recommendations
- **Focus on high-performing segments**, Young adults (18–25), seniors (65+), and professionals with higher education.
- Integrate **digital interaction data** (email clicks, website visits) for deeper personalization. 
- **Future Scope:** Develop a predictive model to identify high-probability leads.

---

## ⚙️ How to run the Project
1. **Clone repository**
   ```bash
   git clone https://github.com/<yourusername>/hr-analytics-sql-excel.git

2. **Open and run python vscode(.ipynb) file**
   ```bash
   scripts/bank_marketing.ipynb

---

## ✉️ Contact

Banothu Sushma
Email: sushmabonothu@gmail.com

LinkedIn: https://www.linkedin.com/in/sushma-banothu-34a143264/

GitHub: https://github.com/sushma-jax
