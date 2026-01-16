# 📊 Google Ads Year-End Performance Analysis

<img width="500" height="300" alt="kapak" src="https://github.com/user-attachments/assets/cd52225d-8ccb-454f-9077-a1f97df651e5" />

This project analyzes **Google Ads performance data** over a full year to provide clear insights for the marketing team.  
The goal is to transform **raw CSV data** into meaningful **monthly and yearly performance metrics** using Google Sheets.

---

## 🎯 Project Objectives

- Import and clean Google Ads data from a CSV file  
- Calculate key digital marketing metrics  
- Aggregate daily data into monthly summaries  
- Identify best-performing months based on spend, conversions, and revenue  
- Present results in a clear, decision-oriented summary  

---

## 📁 Dataset

- **Source:** Google Ads (CSV format)  
- **Granularity:** Daily data  
- **Key Fields:**
  - Date
  - Impressions
  - Clicks
  - Spend
  - Conversions
  - Revenue

---

## 🧮 Calculated Metrics

The following metrics are calculated in the analysis:

| Metric | Description |
|------|------------|
| CTR | Click Through Rate (Clicks / Impressions) |
| CPC | Cost Per Click (Spend / Clicks) |
| CPM | Cost Per Mille ((Spend / Impressions) × 1000) |
| Conversion Rate | Conversions / Clicks |
| Avg. Conversion Value | Revenue / Conversions |
| ROAS | Return on Ad Spend (Revenue / Spend) |

---

## 📊 Sheet Structure

### 1️⃣ Google Ads Raw Data
- Original imported CSV data  
- No transformations applied  

### 2️⃣ Google Ads Solution
- Daily-level calculated metrics  
- All performance ratios and cost metrics  

### 3️⃣ Google Ads Monthly Data
- Monthly aggregated data using `SUMIF`
- Includes:
  - Monthly Impressions
  - Clicks
  - Spend
  - Conversions
  - Revenue
  - Avg. Conversion Amount
  - ROAS

### 4️⃣ Pivot Tables
- Monthly performance overview
- Quick comparison of best-performing months

### 5️⃣ Summary
- Executive-level overview
- Answers key business questions such as:
  - Total annual spend
  - Total revenue
  - Overall ROAS
  - Average CPC & CPM
  - Total conversions

---

## 📌 Key Insights (Example)

- Monthly aggregation enables clear identification of peak performance periods  
- ROAS provides a direct measure of advertising efficiency  
- Separating raw data, calculations, and summaries improves transparency and scalability  

---

## 🛠 Tools Used

- Google Sheets
- CSV Import
- Spreadsheet formulas (`SUMIF`, `MONTH`, ratios)
- Pivot Tables

---

## 🚀 Outcome

This analysis provides a **clear, structured, and reproducible** framework for evaluating Google Ads performance and supports data-driven decision-making for marketing teams.

---

## 👤 Author
Egemen Efe SAHIN
