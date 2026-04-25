# Marketing Analytics Dashboard with Insight Automation

## Overview

This project presents an end-to-end marketing analytics dashboard designed to monitor performance, analyze user behavior, and evaluate customer value across multiple dimensions.

The primary goal is to provide a clear and structured view of marketing effectiveness, while integrating a lightweight AI-based insight layer to support faster interpretation of campaign performance.

The system combines data modeling, transformation, and visualization into a unified workflow, enabling both descriptive analytics and basic automated insights.

---
## Dataset Description

This project uses a simulated digital marketing dataset that combines campaign performance, website analytics, and customer transaction data.

The dataset includes key metrics such as impressions, clicks, conversions, revenue, cost, CPC, CPA, and ROAS, along with user behavior and customer attributes (e.g., age group, gender, country).

It is structured to support multi-channel analysis and enable connections between campaigns, users, and orders.

This dataset was designed to mimic real-world marketing behavior for analytical purposes.

- Note: The dataset is not real production data. I enriched and expanded the dataset myself using SQL-based data generation techniques to simulate more realistic scenarios, including repeat purchases and varied performance patterns across channels.
---

## Live Resources

* Looker Studio Dashboard: [View Dashboard](https://datastudio.google.com/reporting/4be8c7da-98e5-43d1-9f91-5c3a459cd96f)
---

## Project Objectives

* Track and evaluate marketing performance across campaigns and channels
* Analyze traffic quality and user engagement behavior
* Understand customer value and segmentation patterns
* Support decision-making through concise, automated insights

---

## Key Capabilities

### Marketing Performance Analysis

* Revenue, Cost, ROAS, CPA tracking
* Campaign-level and channel-level comparison
* Performance trends over time

### Website and User Behavior

* Sessions and Users analysis
* Bounce Rate and engagement metrics
* Traffic quality evaluation by source

### Customer Analytics

* Revenue per customer
* Customer segmentation (High / Mid / Low value)
* Demographic analysis (Age group, Gender, Country)

### Insight Automation Layer

* Generates short, structured insights for campaign evaluation
* Uses key metrics such as ROAS, Conversion Rate, CPC, and CPA
* Focuses on readability and decision support rather than complex modeling

Example outputs:

* Strong performance, optimize CPA
* Low ROAS, reduce budget
* High traffic, low conversion

---

## Technology Stack

* SQL (MySQL / SQL Server) for data modeling and transformation
* Google Sheets as a lightweight data layer
* Looker Studio for visualization and dashboard design
* Google Apps Script for automation
* OpenAI API for generating concise performance insights

---

## Data Pipeline

Raw Data → SQL Processing → Google Sheets → Apps Script → Looker Studio Dashboard

This pipeline reflects a simplified but practical analytics workflow, suitable for small to mid-scale data environments.

---

## Dashboard Structure

### 1. Business Overview

Provides a high-level summary of performance:

* Revenue and Cost trends
* ROAS and Conversion Rate
* Channel contribution

---

### 2. Marketing Performance

Focuses on campaign and channel efficiency:

* CTR and Conversion Rate trends
* Cost distribution across channels
* Campaign performance table with automated insights

---

### 3. Website Analytics

Evaluates traffic and engagement quality:

* Sessions and Users trend
* Bounce Rate and engagement comparison
* Channel-level traffic quality

---

### 4. Customer Analytics

Explores customer value and segmentation:

* Revenue per customer
* Customer value segmentation
* Geographic and demographic breakdown
* Customer quality by acquisition channel

---

## Insight Logic

The insight layer is based on simple, interpretable business rules:

* ROAS greater than 3 combined with strong conversion indicates effective campaigns
* ROAS below 2.5 suggests underperformance
* High CPC or CPA with low conversion indicates inefficient traffic

These signals are translated into short, structured insights to improve readability within the dashboard.

This approach prioritizes clarity and usability over complex modeling.

---

## Setup Instructions

1. Clone this repository
2. Prepare your data source (Google Sheets or SQL database)
3. Open the Apps Script file and insert your OpenAI API key:

```javascript
const apiKey = "YOUR_API_KEY";
```

4. Run the script to generate insights
5. Connect the Google Sheet to Looker Studio

---

## Data Disclaimer

This project uses simulated or sample data for demonstration purposes.
No real production data is included.

---

## Author

Nguyen Thanh Trung
*[Linkedin](www.linkedin.com/in/thanh-trung-nguyen-hcmute)

---

## Project Significance

This project demonstrates:

* A complete analytics workflow from raw data to dashboard
* The ability to structure and model marketing data effectively
* Practical integration of automation into analytics processes
* A focus on transforming data into actionable insights

Rather than emphasizing complex modeling, the project highlights clarity, usability, and business relevance.

---

## Future Improvements

* Integration with real-time data sources
* Predictive analytics for campaign performance
* Advanced customer segmentation (RFM, LTV)
* Alert system for performance anomalies
* Improved automation of insight generation

---

## Notes

The AI component in this project is experimental and intended to support interpretation rather than replace analytical judgment.

The primary value of the dashboard remains in its structured data modeling and clear visualization design.
