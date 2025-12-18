# 🧱 LEGO Sets Analysis Dashboard - Power BI

## 🎯 Project Overview
An interactive Power BI dashboard analyzing 4,386 LEGO sets to uncover pricing trends, popular themes, and demographic insights. This project transforms raw toy data into strategic business intelligence for product analysis and market understanding.

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI** (DAX, Power Query, Data Modeling)
- **Data Transformation:** Power Query (M Language)
- **Calculations:** DAX Measures & Calculated Columns
- **Visualization:** Custom visuals, bookmarks, image tooltips
- **Design:** LEGO-themed branding with playful yet professional aesthetics

---

## 📊 Key Metrics & Insights

| KPI | Value | Business Insight |
|-----|-------|------------------|
| **Total Sets Analyzed** | 4,386 | Comprehensive market coverage |
| **Average Price** | $44.73 | Mid-range pricing strategy dominates |
| **Average Pieces per Set** | 411 | Complexity balanced for target demographics |
| **Most Popular Theme** | **Ninjago** | Action/Adventure themes drive sales |
| **Highest Priced Set** | $850 | Premium segment exists for collectors |
| **Most Common Age Range** | **5–9 years** | Primary target market for standard sets |

---

## 🔧 Technical Implementation

### **Data Preparation (Power Query)**
- **Data Cleaning:** Handled missing values, removed unnecessary fields
- **Conditional Columns:** Created `Age Range` and `Price Range` categories
- **Data Transformation:** Standardized formats and optimized data types

### **Data Modeling & DAX**
```dax
// Key Measures Created
Total_Sets = COUNTROWS('LEGO_Sets')
Average_Price = AVERAGE('LEGO_Sets'[Price])
Average_Pieces = AVERAGE('LEGO_Sets'[Pieces])
```
## 📂 Repository Structure
```text
Lego-Sets-Analysis/
├── LEGO_Sets_Analysis.pbix           # The core Power BI report file
├── Docs                              # The Original data_set
    ├── Lego_sets.csv
└── Dashboards/                       # High-resolution screenshots
    ├── Product_Explorer_Main.png     # Main dashboard with image viewer
    └── Hierarchical_Drilldown.png    # Decomposition tree analysis view
```
---

## 📬 Connect With Me

<p align="center">
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/mohamed-ayman-data/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <!-- GitHub -->
  <a href="https://github.com/mohamed-ayman-data" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <!-- Email -->
  <a href="mailto:mohmedaymn2025@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <i>Let's collaborate on data-driven solutions!</i>
</p>

<hr>
<p align="center">
  <sub>📊 Data Analyst | 📈 Business Intelligence | 🎯 Python & SQL Expert</sub>
</p>
