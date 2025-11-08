# Insurance-Analytics-Dashboard


# 🧾 Insurance Analytics Dashboard – Excel | SQL | Power BI | Tableau

## 📘 Project Overview
This project provides an **end-to-end business analytics solution** for an insurance company.  
It integrates **Excel, SQL, Power BI, and Tableau** to analyze sales performance, policy renewals, revenue achievements, meeting frequency, and opportunities.

The dashboard was developed to help stakeholders track KPIs, visualize performance, and make data-driven decisions.

---

## 🧩 Objective
To build an integrated analytical dashboard that helps stakeholders monitor:
- Revenue and target achievement by **income class** (Cross-sell, New, Renewal)
- **Meeting frequency and trend** by Account Executives
- **Open vs Won Opportunities**
- **Invoicing performance** across branches
- **Target vs Achievement %** for individuals and teams

---

## ⚙️ Tools & Technologies Used
| Tool | Purpose |
|------|----------|
| **Excel** | Data cleaning, KPI calculation, and dataset preparation |
| **MySQL (SQL)** | Database creation, queries, and performance computation |
| **Power BI** | Interactive dashboards and drill-through insights |
| **Tableau** | Data visualization and comparative analysis |
| **PowerPoint** | KPI presentation and stakeholder briefing |

---

## 🧱 Project Components
| Folder | File | Description |
|---------|------|-------------|
| 📊 `Data/` | `Excel_Dashboard.xlsx` | Processed dataset and KPI base sheet |
| 🧮 `SQL/` | `Insurance_SQL_Analysis.sql` | SQL scripts for KPI, meeting, and revenue analysis |
| 💡 `PowerBI/` | `PowerBI_Dashboard.pbix` | Interactive Power BI dashboard |
| 📉 `Tableau/` | `Tableau_Dashboard.twbx` | Tableau dashboard for comparative visualization |
| 📄 `Documents/` | `Insurance_Column_Descriptions.docx` | Table-wise field descriptions |
|  | `Insurance_KPI_Sheet.pptx` | PowerPoint summarizing KPIs and dashboard flow |

---

## 🧮 SQL Analytics Summary
SQL scripts are designed to analyze and summarize data across various insurance tables.

### ✅ Key SQL Insights
- **Invoice Analysis:** Count invoices by Account Executive and income class.  
- **Meeting Trends:** Identify meeting counts and yearly distribution.  
- **Target vs Achievement:** Compare budgets, brokerage, and fee collections by category.  
- **Stage Funnel Analysis:** View opportunities by stage (Open, Qualify, Propose, Won).  
- **Top Opportunities:** Highlight high-value opportunities by revenue.

These SQL results power KPIs and visuals inside Power BI and Tableau dashboards.

---

## 📊 KPI Metrics and Dashboard Insights

### 🧭 Major KPIs
1. **Number of Invoices by Account Executive**  
2. **Yearly Meeting Count**  
3. **Cross-Sell / New / Renewal** – Target vs Achieved vs Invoiced  
4. **Stage Funnel by Revenue**  
5. **Meetings by Account Executive**  
6. **Top Open Opportunities**  
7. **Conversion Ratio (Won / Total Opportunities)**  

---

## 🖥️ Dashboard Details

### 📊 Power BI Dashboard
**Branch Dashboard:**
- Displays *New*, *Renewal*, and *Cross-Sell* performance for each branch.  
- Includes KPIs like Target %, Achieved %, and Invoiced %.  

**Individual Dashboard:**
- Provides *Account Executive* level insights with drill-through navigation.  

**Stage Funnel View:**
- Shows opportunity stage distribution by revenue and count.

---

### 📈 Tableau Dashboard
- Simplified interactive view for comparing performance across income classes.  
- Visualizes *revenue, targets, and opportunity funnels* using filters and charts.  

---

## 🗃️ Data Description Summary
Detailed data documentation is provided in `Insurance_Column_Descriptions.docx`, covering:
- **Brokerage**
- **Fees**
- **Budgets**
- **Invoices**
- **Meetings**
- **Opportunities**

Each table includes fields like:
`client_name`, `policy_number`, `income_class`, `branch_name`, `amount`, `revenue_transaction_type`, etc.

---

## 🧠 Insights Derived
- Identified top-performing branches for *new policies* and *renewals*.  
- Highlighted *Account Executives* contributing the most to revenue.  
- Showed improvement areas through *Target vs Invoice %* analysis.  
- Visualized *meeting consistency* and *open opportunity trends*.  
- Provided *funnel-based revenue projections* for management.  

