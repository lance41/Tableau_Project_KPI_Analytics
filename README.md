
# 📊 Monthly KPI Dashboard for Call Center Optimization (Tableau)

> *Optimizing performance monitoring and operational insights for Help Desk managers using data visualization.*

---

## 📝 Problem Statement

The Help Desk Manager needed a **Monthly KPI Dashboard** to:
- Monitor overall call center performance
- Evaluate individual agent productivity
- Track call quality and customer satisfaction

However, the manager wasn’t sure what specific metrics were most useful, prompting the need for an exploratory, insight-rich dashboard that could guide decisions.

---

## 🎯 Objectives

- Visualize **weekly call volume** trends
- Summarize **daily inbound calls** and **average call duration**
- Compare **employee performance** based on:
  - Speed of Answer
  - Resolution Rate
  - Resolved Calls
- Assess **customer satisfaction** ratings
- Display a **monthly resolution performance** summary

---

## 📈 Dashboard Overview

![KPI Dashboard](images/KPI_Dashboard.png)

**Key Visuals:**
- Weekly Call Volume bar chart with average line
- KPI cards: Inbound Calls Today, Avg Call Duration, Monthly Resolution Rate
- Satisfaction Rating histogram
- Agent Performance tables:
  - Speed of Answer
  - Resolution Rates
  - Resolved Calls

---

## 🔍 Key Insights

| Insight | Interpretation |
|--------|----------------|
| 🟢 **Monday is the busiest** (284 calls) | Schedule more agents to handle peak traffic |
| 🟢 **Martha has top performance** | Highest resolution rate (78.74%) & most resolved calls (163) |
| 🔶 Satisfaction Ratings peak at 3–4 | Service experience is average; opportunity for improvement |
| 🔴 **Dan's resolution rate is lowest** (59.18%) | Needs coaching and targeted feedback |
| 🟢 **Avg Call Duration is under 4 min** | Indicates strong operational efficiency |

---

## 📊 Recommendations

1. **Optimize Staff Allocation:** Increase agent count on high-volume days (e.g., Mondays).
2. **Reward High Performers:** Recognize Martha, Jim, and Stewart for strong contributions.
3. **Provide Coaching:** Support underperformers like Dan with resolution training.
4. **Improve Satisfaction:** Investigate 3–4 ratings for actionable feedback.

---

## 📂 Dataset Overview

| Field Name         | Description                         |
|--------------------|-------------------------------------|
| `Date`             | Date of call                        |
| `Agent`            | Call center staff member            |
| `Call Duration`    | Duration of call in minutes         |
| `Resolved`         | Whether issue was resolved (Y/N)    |
| `Satisfaction`     | Customer satisfaction rating (1–5)  |

---

## 🛠️ Tools Used

- **Tableau**: Dashboard creation and interactive visuals
- **Excel**: Source data cleaning and transformation

---

## 🗂️ Project Structure

```
KPI-Dashboard-Call-Center/
├── README.md
├── data/
│   └── Call Center Data.xlsx
├── images/
│   └── KPI_Dashboard.png
├── tableau/
│   └── KPI_Dashboard.twb
│   └── KPI_Dashboard_Export.pdf
├── insights/
│   └── KPI_Insights_Report.md
```

---

## 🔧 Skills Demonstrated

- KPI Framework Design
- Data Cleaning & Preparation
- Business Performance Analysis
- Data Storytelling & Visualization
- Stakeholder Communication

---

## 📣 Contact

Created by **Lance Ngan Han Kiong**  
For collaborations or feedback:
- [LinkedIn](https://www.linkedin.com/in/lancenganhk)
- Email: [adiemus80@gmail.com](mailto:adiemus80@gmail.com)

---

> "Data doesn't drive decisions — clarity does. This dashboard helps managers see, compare, and act."
