# Maji Ndogo Water Access Dashboard 💧 &nbsp; [![View Dashboard](https://img.shields.io/badge/Power_BI-View_Report-F2C811?logo=powerbi&logoColor=black)](Maji%20Ndogo%20Water%20Access%20Analysis.pdf)

![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-4051B5)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Storytelling-2196F3)
![Status](https://img.shields.io/badge/Status-Complete-success)

> **An interactive Power BI dashboard for the fictional country of Maji Ndogo — helping national and provincial leaders understand water access gaps, infrastructure needs, and funding allocation across 5 provinces.**

<br>

<p align="center">
  <img src="https://img.shields.io/badge/🗺️_Provinces-5-green?style=for-the-badge" alt="Provinces"/>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/📊_Dashboard_Pages-6-blue?style=for-the-badge" alt="Pages"/>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/👥_Stakeholders-2_Personas-orange?style=for-the-badge" alt="Stakeholders"/>
</p>

<br>

## Table of Contents

- [Problem Statement](#problem-statement)
- [Dashboard Design](#dashboard-design)
- [User Stories](#user-stories)
- [Technical Implementation](#technical-implementation)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [How to View](#how-to-view)
- [Author](#author)

<br>

## Problem Statement

How can data visualization help leaders allocate limited resources to improve water access? This dashboard translates complex water infrastructure data into actionable insights for two key stakeholder groups: **national leadership** (President Naledi) who needs the big picture, and **provincial leaders** (Sokoto, Kilimani, Akatsi, Amanzi, Hawassa) who need localized detail. The design follows a clear narrative: **Who needs help → What needs to be done → How much it costs.**

<br>

## Dashboard Design

### National Overview (President Naledi)
- Population vs. access across all provinces
- Urban vs. rural comparisons
- National improvement needs and projected costs
- **Bookmark toggle** switching between budget views: by province or by improvement type
- Summary cards: total cost, % with basic water access, country map

### Provincial Pages (5 provinces)
- Town-level improvement counts and budgets
- Cost per citizen analysis
- Budget allocation by improvement type
- Urban/rural budget splits
- **Drill-through** connections from national overview

<br>

## User Stories

### President Naledi (National Decision-Maker)
> *"I need to understand the scale of the water challenge, where we need to intervene, how much it will cost, and what outcomes to expect."*

### Provincial Leaders (Localized Decision-Makers)
> *"I need to see the situation in my province — the budget needed, towns affected, and types of improvements required."*

<br>

## Technical Implementation

### DAX Measures
- **Rural-adjusted infrastructure costs** — accounting for higher costs in remote areas
- **Water source classification** — categorizing sources as basic or below-basic
- **Budgeted improvement cost per source** — per-unit cost calculations
- **% of population with basic water access** — coverage metrics

### Power BI Techniques
- **Bookmark toggles** for intuitive navigation between views
- **Drill-through pages** connecting national overview to provincial detail
- **Conditional filters** and cross-page interactivity
- **Aggregated transformation** of improvement types
- **Tooltips and annotations** for context on reclassified data

### Design Principles
- Clear **3-part narrative layout**: Who → What → How Much
- **Modular tabs** for each stakeholder role
- **Color-coded visuals** for clarity without distraction

<br>

## Key Insights

- Identified provinces with the lowest basic water access rates
- Quantified the budget gap between urban and rural infrastructure
- Mapped improvement types to specific geographic needs
- Created toggle views allowing leaders to analyze budgets from multiple angles

<br>

## Technologies Used

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard design & interactivity |
| DAX | Calculated measures & columns |
| Data Modeling | Star schema relationships |

<br>

## How to View

1. **PDF Export** — Open `Maji Ndogo Water Access Analysis.pdf` for a static view
2. **Interactive Dashboard** — Open `Maji Ndogo Water Access Analysis.pbix` in Power BI Desktop

```bash
# Clone the repository
git clone https://github.com/ouyale/Maji-Ndogo-Water-Access-Analysis.git
cd Maji-Ndogo-Water-Access-Analysis

# Open the .pbix file in Power BI Desktop
# Or view the .pdf for a static dashboard preview
```

<br>

## Author

**Barbara Obayi** — Machine Learning Engineer

[![GitHub](https://img.shields.io/badge/GitHub-ouyale-181717?logo=github)](https://github.com/ouyale)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Barbara_Obayi-0A66C2?logo=linkedin)](https://www.linkedin.com/in/barbara-weroba-obayi31/)
[![Portfolio](https://img.shields.io/badge/Portfolio-ouyale.github.io-4fc3f7)](https://ouyale.github.io)

---
