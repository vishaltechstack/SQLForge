# ⚒️ SQLForge: Real-World MySQL Database Engineering & Analytics Portfolio

![MySQL](https://img.shields.io/badge/MySQL-8.0%2B-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Relational_Databases-CC2927?style=for-the-badge&logo=databricks&logoColor=white)
![Projects](https://img.shields.io/badge/Case_Studies-20_Domain_Projects-FF6F00?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Design-3NF_&_ACID_Compliant-2EA44F?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**SQLForge** is a comprehensive collection of **20 end-to-end relational database projects** built with **MySQL 8.0+**[cite: 1, 2]. Every project simulates a real-world industry domain—complete with normalized table schemas, realistic sample datasets, and business-intelligence reporting queries covering multi-table joins, CTEs, window functions, stored routines, and data validation checks[cite: 1, 2].

---

## 📂 Repository & Project Architecture

Each domain folder inside `SQLForge` follows a clean, standardized 3-script modular layout[cite: 1, 2]:

```text
SQLForge/
├── Airline Reservation & Flight Analytics/
│   ├── Create Database & Tables.sql          # DDL: Database, tables, keys & constraints
│   ├── Insert Values.sql                     # DML: Realistic domain seed records
│   └── Airline Reservation & Flight Reports.sql  # DQL: Business analytics & KPI queries
├── Banking Customer Transactions/
├── E-commerce Delivery Performance/
├── Employee Workforce Analysis/
├── Food Delivery Platform/
├── Gaming Leaderboard System/
├── Hospital Patient Records/
├── Hotel Reservation System/
├── Library Borrowing System/
├── Loan Management & Credit Analysis/
├── Logistics & Warehouse System/
├── Movie Rating Database/
├── Music Streaming Platform/
├── Online Learning Platform/
├── Real Estate Property Management/
├── Retail Inventory Control/
├── Sales Insight Tracker/
├── Social Media Engagement Analyzer/
├── Telecom Call Records/
├── University Student Performance/
└── README.md
```

---

## ⚙️ How to Run Any Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/vishaltechstack/SQLForge.git](https://github.com/vishaltechstack/SQLForge.git)
   cd SQLForge
   ```
2. **Open your MySQL client** (MySQL Workbench, DBeaver, VS Code SQLTools, or MySQL CLI).
3. **Navigate into any project folder** and run its scripts in exact order[cite: 2]:
   * **Step 1:** Run `Create Database & Tables.sql` to build the schema, primary/foreign keys, and constraints[cite: 2].
   * **Step 2:** Run `Insert Values.sql` to populate the tables with test records[cite: 2].
   * **Step 3:** Run the project's analytical/reporting `.sql` file to execute business queries, rankings, and aggregations[cite: 2].

---

## 🚀 20 Real-World SQL Case Studies

| # | Project Name | Industry Domain | Core SQL Concepts & Business Queries |
| :--- | :--- | :--- | :--- |
| **01** | [**Airline Reservation & Flight Analytics**](./Airline%20Reservation%20%26%20Flight%20Analytics)[cite: 1, 2] | Aviation & Travel | Seat occupancy rates, route revenue joins, flight delay & cancellation reports |
| **02** | [**Banking Customer Transactions**](./Banking%20Customer%20Transactions)[cite: 1, 2] | FinTech & Banking | Account ledger balances, high-value transaction flagging, running totals |
| **03** | [**E-commerce Delivery Performance**](./E-commerce%20Delivery%20Performance)[cite: 1, 2] | E-Commerce | SLA delivery breach tracking, courier turnaround metrics, `DATEDIFF` KPIs |
| **04** | [**Employee Workforce Analysis**](./Employee%20Workforce%20Analysis)[cite: 1, 2] | HR & People Ops | Department salary distribution, tenure cohorts, attrition & manager hierarchies |
| **05** | [**Food Delivery Platform**](./Food%20Delivery%20Platform)[cite: 1, 2] | On-Demand Delivery | Peak-hour order volume, top-rated restaurants, delivery partner performance |
| **06** | [**Gaming Leaderboard System**](./Gaming%20Leaderboard%20System)[cite: 1, 2] | Gaming & Esports | Global & seasonal player rankings (`DENSE_RANK`, `ROW_NUMBER`), win-rate CTEs |
| **07** | [**Hospital Patient Records**](./Hospital%20Patient%20Records)[cite: 1, 2] | Healthcare | Doctor-patient appointment scheduling, treatment billing, diagnosis summaries |
| **08** | [**Hotel Reservation System**](./Hotel%20Reservation%20System)[cite: 1, 2] | Hospitality | Date-overlap room availability checks, seasonal occupancy & revenue analytics |
| **09** | [**Library Borrowing System**](./Library%20Borrowing%20System)[cite: 1, 2] | Education & Admin | Overdue book tracking, late-fee calculations, most-borrowed catalog items |
| **10** | [**Loan Management & Credit Analysis**](./Loan%20Management%20%26%20Credit%20Analysis)[cite: 1, 2] | Credit & Lending | EMI repayment schedules, default risk segmentation (`CASE WHEN`), interest yields |
| **11** | [**Logistics & Warehouse System**](./Logistics%20%26%20Warehouse%20System)[cite: 1, 2] | Supply Chain | Multi-warehouse inventory levels, shipment tracking, reorder threshold alerts |
| **12** | [**Movie Rating Database**](./Movie%20Rating%20Database)[cite: 1, 2] | Media & Entertainment | Weighted audience ratings, genre leaderboards, top-rated director subqueries |
| **13** | [**Music Streaming Platform**](./Music%20Streaming%20Platform)[cite: 1, 2] | Digital Media | Listener stream counts, artist royalty aggregations, playlist relational joins |
| **14** | [**Online Learning Platform**](./Online%20Learning%20Platform)[cite: 1, 2] | EdTech | Course completion funnels, instructor revenue shares, student quiz analytics |
| **15** | [**Real Estate Property Management**](./Real%20Estate%20Property%20Management)[cite: 1, 2] | PropTech | Lease expiration alerts, rental yield analysis, tenant payment history |
| **16** | [**Retail Inventory Control**](./Retail%20Inventory%20Control)[cite: 1] | Retail Operations | Stock-out alerts, supplier lead-time tracking, slow-moving stock identification |
| **17** | [**Sales Insight Tracker**](./Sales%20Insight%20Tracker)[cite: 1] | Business Intelligence | Month-over-month revenue growth (`LAG`), regional sales rep quota performance |
| **18** | [**Social Media Engagement Analyzer**](./Social%20Media%20Engagement%20Analyzer)[cite: 1] | Social Analytics | Post engagement rates, follower growth trends, active user retention cohorts |
| **19** | [**Telecom Call Records**](./Telecom%20Call%20Records)[cite: 1] | Telecommunications | Call detail record (CDR) duration summaries, roaming billing, data plan usage |
| **20** | [**University Student Performance**](./University%20Student%20Performance)[cite: 1] | Higher Education | GPA calculations, department topper rankings, attendance vs. grade correlation |

---

## 🛠️ Core Technical Skills Demonstrated

* **Database Architecture & DDL:** Relational schema modeling, `PRIMARY KEY`, `FOREIGN KEY` cascading rules, `UNIQUE`, `CHECK`, and `DEFAULT` constraints.
* **Analytical Querying:** Multi-table `INNER` / `LEFT` joins, Common Table Expressions (`WITH`), scalar & correlated subqueries, and `CASE WHEN` conditional logic.
* **MySQL 8.0+ Window Functions:** Partitioned ranking (`ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`), row-to-row comparisons (`LAG()`, `LEAD()`), and cumulative running totals.
* **Data Quality & Validation:** Referential integrity checks, duplicate detection, null-handling (`COALESCE`), and aggregate reconciliation (`GROUP BY` / `HAVING`).

---

## 🔗 Explore My Other SQL Repositories

| Repository | Focus Area | Description |
| :--- | :--- | :--- |
| [![SQLAlchemyLab](https://img.shields.io/badge/SQLAlchemyLab-333333?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/vishaltechstack/SQLAlchemyLab) | `MySQL 8.0+` `22-Step Curriculum` | Complete step-by-step MySQL tutorial from database creation to triggers, views, indexes, JSON, and ACID transactions. |
| [![QueryCraft](https://img.shields.io/badge/QueryCraft-008080?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/vishaltechstack/QueryCraft) | `SQL` `Problem Solving` `Joins & CTEs` | Daily hands-on SQL coding challenges and query-building practice problems to sharpen relational logic. |

---

## 👨‍💻 Author

**Vishal Sharma**  
*Software Development & Quality Engineering Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-vishaltechstack-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vishaltechstack)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![SQLForge](https://img.shields.io/badge/SQLForge-20_SQL_Projects-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/vishaltechstack/SQLForge)

---

⭐ *If you find these SQL projects useful for learning or interview preparation, feel free to star the repository!*
