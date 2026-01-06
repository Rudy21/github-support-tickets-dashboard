# 📊 GitHub Support Operations Dashboard (API-Driven)

## 🧩 Project Summary
This project demonstrates a **Support Operations Analytics Dashboard** built using **live GitHub Issues data** and **Power BI**.  
GitHub Issues are modeled as **support tickets**, enabling realistic analysis of workload, resolution trends, ownership gaps, and operational risks.

The goal of this project is not visualization alone, but to **replicate how real support teams monitor and manage tickets** in production environments.

---

## 🎯 Business Use Case
Support teams need quick answers to operational questions such as:
- How many tickets are coming in this month?
- How many issues are currently open?
- Are tickets being resolved fast enough?
- Are there unassigned or poorly triaged tickets?
- Is the backlog increasing or decreasing over time?

This dashboard provides a **single, decision-ready view** to answer these questions.

---

## 🏗️ Architecture Overview
GitHub Issues API (Live Data)
↓
Python Script (API ingestion + pagination)
↓
Historical Dataset (CSV)
↓
Power BI (Modeling, DAX, Visualization)


---

## 📊 Key Metrics & Visuals

### 🔹 Workload Monitoring
- Total Issues (Monthly)
- Open Issues (Current)
- Closed Issues (Year-to-Date)

### 🔹 Risk & Quality Indicators
- Unassigned Issues (ownership risk)
- Labeled vs Unlabeled Issues (triage quality)

### 🔹 Trend Analysis
- Open Issues Trend (workload pressure)
- Issues Created vs Resolved (throughput comparison)

---

## 🧠 Insights Enabled
- Detect workload spikes and backlog growth
- Track resolution performance over time
- Identify ownership gaps caused by unassigned issues
- Evaluate ticket categorization using labels
- Compare ticket inflow against resolution capacity

---

## 🛠️ Tools & Technologies Used
- **Python** – GitHub API integration & pagination
- **GitHub REST API** – Live issue data source
- **Power BI** – Dashboard design and analytics
- **Power Query** – Data cleaning and transformation
- **DAX** – KPI and time-based calculations

---

## 🔍 Why GitHub Issues?
GitHub Issues were intentionally chosen as a **real-world proxy for support tickets** because they provide:
- Live and continuously changing data
- Clear Open / Closed status
- Ownership via assignees
- Resolution timelines
- Categorization via labels

This approach avoids static or artificial datasets and reflects real operational behavior.

---

## 🧭 Dashboard Design Logic
The dashboard is structured to mirror **support team workflows**:
- Top KPIs for instant situational awareness
- Trend cards for understanding momentum
- Risk indicators for ownership and triage gaps
- A clean navigation panel aligned with support operations

---

## 📷 Dashboard Preview

<img width="1209" height="673" alt="image" src="https://github.com/user-attachments/assets/f6faf2be-5b64-4e5b-88ad-17c6c1ca6b28" />



## 📬 Feedback & Contributions
Suggestions, feedback, and improvements are welcome.
