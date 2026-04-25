# 📊 AI-Powered Marketing Analytics Dashboard

## 🚀 Overview

This project is an end-to-end marketing analytics dashboard designed to track performance across campaigns, channels, and customer segments.

It integrates data modeling, visualization, and an AI-powered insight layer to support faster and smarter decision-making.

---

## 🎯 Key Features

### 📈 Business & Marketing Performance

* Revenue, Cost, ROAS, CPA tracking
* Campaign-level performance analysis
* Channel efficiency comparison

### 🌐 Website Analytics

* Sessions & User behavior tracking
* Bounce Rate & Engagement metrics
* Traffic quality by channel

### 👥 Customer Analytics

* Revenue per customer
* Customer segmentation (High / Mid / Low value)
* Demographic insights (Age, Gender, Country)

### 🤖 AI-Powered Insights

* Automatically generates performance insights for each campaign
* Evaluates:

  * ROAS
  * Conversion Rate
  * CPC / CPA
* Produces short, actionable recommendations

**Example outputs:**

* Strong performance, optimize CPA
* Low ROAS, reduce budget
* High traffic, low conversion

---

## 🧱 Tech Stack

* **SQL (MySQL / SQL Server)** → Data modeling & transformation
* **Google Sheets** → Data storage & processing layer
* **Looker Studio** → Dashboard visualization
* **Apps Script (JavaScript)** → Automation
* **OpenAI API** → AI-generated insights

---

## 🏗️ Data Pipeline

```text
Raw Data → SQL → Google Sheets → Apps Script (AI) → Looker Dashboard
```

---

## 📊 Dashboard Structure

### 1. Business Overview

* Revenue vs Cost trend
* ROAS performance
* Channel contribution

### 2. Marketing Performance

* CTR & Conversion Rate trends
* Funnel performance
* Campaign comparison table (with AI insights)

### 3. Website Analytics

* Traffic trend (Users vs Sessions)
* Engagement analysis
* Channel quality evaluation

### 4. Customer Analytics

* Customer value segmentation
* Revenue per customer
* Customer quality by channel

---

## 📷 Dashboard Preview

![Dashboard](dashboard/screenshots.png)

---

## 🤖 AI Insight Logic

Insights are generated based on business rules:

* **ROAS > 3 & CR > 4%** → Strong performance
* **ROAS < 2.5** → Weak performance
* **High CPC/CPA + low CR** → Inefficient traffic

The AI converts these signals into concise business insights.

---

## ⚠️ Setup Instructions

1. Clone this repository
2. Connect your data source (Google Sheets / SQL)
3. Add your OpenAI API key in Apps Script:

```javascript
const apiKey = "YOUR_API_KEY";
```

4. Run the script to generate AI insights

---

## 🔐 Note

This project does **not include real production data**.
Sample data is provided for demonstration purposes only.

---

## 👤 Author

**Nguyen Trung**

---

## 💡 Why This Project Stands Out

* Combines **BI + AI** (not just dashboarding)
* Demonstrates **end-to-end data workflow**
* Focuses on **actionable insights, not just metrics**

---

## ⭐ Future Improvements

* Predictive analytics (forecasting campaigns)
* Real-time data pipeline integration
* Advanced customer segmentation (RFM / LTV)
