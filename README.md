<div align="center">

<!-- BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=200&section=header&text=Call%20Center%20Performance%20Analysis&fontSize=36&fontColor=ffffff&fontAlignY=38&desc=Turning%20Raw%20Call%20Data%20into%20Actionable%20Insights&descAlignY=60&descSize=16" width="100%"/>

<!-- BADGES -->
<p>
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge&logo=github" alt="Version"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/status-Active-brightgreen?style=for-the-badge" alt="Status"/>
  <img src="https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge" alt="PRs Welcome"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Data%20Analysis-0078D4?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Analysis"/>
  <img src="https://img.shields.io/badge/Data%20Visualization-FF6F00?style=for-the-badge&logo=tableau&logoColor=white" alt="Data Visualization"/>
</p>

<br/>

> 📊 **A comprehensive Power BI solution that transforms call center raw data into strategic KPI dashboards — empowering teams to optimize performance, reduce bottlenecks, and elevate customer satisfaction.**

<br/>

</div>

---

## 📋 Table of Contents

- [📌 About the Project](#-about-the-project)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#%EF%B8%8F-tech-stack)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [📖 Usage](#-usage)
- [📸 Dashboard Preview](#-dashboard-preview)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👤 Author](#-author)

---

## 📌 About the Project

Call centers are the heartbeat of customer service — but without data, decisions are made blind. **Call Center Performance Analysis** is a fully interactive Power BI project that gives managers and analysts a real-time, data-driven view of their operations.

This project ingests structured call center data from Excel, processes it into meaningful KPIs, and surfaces insights through an intuitive dashboard designed for day-to-day operational monitoring and strategic decision-making.

Whether you're tracking agent productivity, measuring SLA compliance, or diagnosing service bottlenecks — this tool delivers clarity at a glance.

---

## ✨ Features

- 📞 **Call Volume Analysis** — Monitor inbound/outbound call trends over time, peak hours, and daily/weekly distributions
- ⏱️ **Response Time Metrics** — Track Average Handle Time (AHT), Average Speed of Answer (ASA), and SLA compliance rates
- 😊 **Customer Satisfaction (CSAT)** — Visualize satisfaction scores and identify patterns tied to agents or call types
- 🧑‍💼 **Agent Performance Evaluation** — Rank agents by productivity, resolution rate, and quality metrics
- 🔍 **Bottleneck Detection** — Pinpoint inefficiencies in call routing, wait times, and abandoned calls
- 🎛️ **Interactive Dashboard** — Dynamic slicers for filtering by date, agent, team, or call category
- 📈 **Trend Forecasting Views** — Spot performance trends before they become problems
- 📊 **KPI Summary Cards** — At-a-glance executive summary with key performance indicators

---

## 🛠️ Tech Stack

| Tool | Purpose | Badge |
|------|---------|-------|
| **Power BI Desktop** | Interactive dashboard & visualization | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |
| **Microsoft Excel** | Data source & preprocessing | ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) |
| **DAX** | Calculated measures & KPI logic | ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white) |
| **Power Query (M)** | Data transformation & ETL | ![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=flat-square&logo=microsoft&logoColor=white) |

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- ✅ **Power BI Desktop** — [Download here](https://powerbi.microsoft.com/en-us/desktop/)  
  *(Free, Windows only — version 2.100+ recommended)*
- ✅ **Microsoft Excel** — For viewing or modifying the source dataset
- ✅ **Git** — For cloning the repository *(optional)*

---

### Installation

**Step 1 — Clone or Download the Repository**

```bash
# Option A: Clone via Git
git clone https://github.com/m0hamed-atif/call-center-performance-analysis.git

# Option B: Download ZIP from GitHub and extract it
```

**Step 2 — Open the Power BI File**

```
📂 Navigate to the project folder
📊 Double-click: CallCenter_Performance.pbix
   └── Power BI Desktop will launch automatically
```

**Step 3 — Connect the Dataset** *(if prompted)*

```
1. In Power BI → Click "Transform Data" in the ribbon
2. Go to: Data Source Settings
3. Update the file path to point to your local Excel file:
   └── /data/CallCenter_Dataset.xlsx
4. Click "Close & Apply"
```

**Step 4 — Explore the Dashboard**

```
✅ Refresh the data if needed (Home → Refresh)
✅ Use slicers to filter by Date, Agent, or Team
✅ Navigate between report pages using the tab bar
```

---

## 📖 Usage

Once the dashboard is open in Power BI Desktop, you can interact with it in the following ways:

**📅 Filter by Date Range**
```
→ Use the Date Slicer on the top panel to select a custom time range
→ KPIs and charts will update dynamically
```

**👤 Drill Down by Agent**
```
→ Select an agent from the Agent slicer
→ View individual performance cards, call counts, and CSAT scores
```

**📊 Monitor KPIs at a Glance**
```
Dashboard Page 1 — Executive Summary:
  ├── Total Calls Handled
  ├── Average Handle Time (AHT)
  ├── First Call Resolution Rate (FCR)
  ├── Customer Satisfaction Score (CSAT)
  └── Abandoned Call Rate

Dashboard Page 2 — Agent Performance:
  ├── Individual Agent Scorecards
  ├── Calls per Agent (Bar Chart)
  └── Productivity Ranking Table

Dashboard Page 3 — Operational Insights:
  ├── Peak Hour Heatmap
  ├── Call Volume by Category
  └── SLA Compliance Trend
```

---

## 📸 Dashboard Preview

<div align="center">

> 🖼️ *Screenshots will be added upon deployment. Below is a placeholder for the dashboard preview.*

| Executive Summary | Agent Performance | Operational Insights |
|:-----------------:|:-----------------:|:--------------------:|
| `[Screenshot 1]` | `[Screenshot 2]` | `[Screenshot 3]` |
| KPIs & Overview | Agent Scorecards | Trends & Heatmaps |

</div>

---

## 📁 Project Structure

```
📦 call-center-performance-analysis/
├── 📊 CallCenter_Performance.pbix     ← Main Power BI dashboard file
├── 📂 data/
│   └── 📄 CallCenter_Dataset.xlsx     ← Source data (Excel)
├── 📂 screenshots/
│   ├── 🖼️ dashboard_overview.png
│   ├── 🖼️ agent_performance.png
│   └── 🖼️ operational_insights.png
├── 📄 README.md                       ← Project documentation
└── 📄 LICENSE                         ← MIT License
```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn and grow. Any contributions you make are **greatly appreciated**!

<details>
<summary>📋 <strong>How to Contribute</strong> (click to expand)</summary>

<br/>

1. **Fork** the repository

2. **Create** your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Commit** your changes
   ```bash
   git commit -m "Add: AmazingFeature that improves X"
   ```

4. **Push** to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **Open** a Pull Request

</details>

<details>
<summary>💡 <strong>Ideas for Contributions</strong></summary>

<br/>

- 🌍 Add support for multi-language data sources
- 📱 Create a Power BI Mobile-optimized layout
- 🤖 Integrate predictive analytics for call volume forecasting
- 📤 Add automated report export functionality
- 🧪 Include sample anonymized dataset for testing

</details>

> ⭐ If this project helped you, please consider giving it a **star** on GitHub — it means a lot!

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

```
MIT License — © 2024 Mohamed Atif
Permission is granted to use, copy, modify, and distribute this software freely.
```

---

## 👤 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/m0hamed-atif" width="100px" style="border-radius: 50%;" alt="Mohamed Atif"/>

### **Mohamed Atif**
*Data Engineer & Analyst*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/m0hamed-atif)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/m0hamed-atif)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamed.atif.gadalla@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=120&section=footer" width="100%"/>

**Made with ❤️ and 📊 data by [Mohamed Atif](https://github.com/m0hamed-atif)**

*If you found this project useful, don't forget to ⭐ star the repo!*

</div>
