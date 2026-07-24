# NGO Program Impact & Beneficiary Tracking System (MEAL Focus)

## 📌 Project Overview
This project is an end-to-end Monitoring, Evaluation, Accountability, and Learning (MEAL) data analytics solution designed for international organizations and non-governmental entities (NGOs). It tracks multi-region humanitarian project key performance indicators (KPIs), fund allocation efficiency, community-level activity engagement, and beneficiary demographics over time.

Link to the Live Project: https://public.tableau.com/app/profile/joshua.dauda/viz/CommunityHealthHumanitarianProject-MEALPerformanceDashboard/NGOMEALExecutiveOverview
---

## 💼 Business Problem
Humanitarian operations often struggle with fragmented reporting, tracking aid distribution across remote regions, and proving donor accountability. Program managers need a centralized system to monitor whether funds are efficiently utilized, if target beneficiary counts are being met, and which communities experience service delivery bottlenecks. 

---

## 🗄️ Data Architecture & Relational Schema
The dataset is structured into three interconnected relational tables:
1. **Beneficiary Master (`Beneficiary_Master.csv`):** Contains demographic profiles, unique beneficiary IDs, enrollment dates, and vulnerability statuses.
2. **Activity Log (`Activity_Log.csv`):** Logs community-level interventions (e.g., training workshops, awareness sessions, medical checkups), dates, and attendance statuses.
3. **Budget & KPI Target (`Budget_KPI_Target.csv`):** Tracks regional financial performance, quarterly allocated budgets versus actual spend, and target versus actual beneficiary counts.

---

## 🛠️ Tech Stack & Tools
* **Data Simulation & Cleaning:** Python (Pandas) / Excel
* **Database & Wrangling:** PostgreSQL / SQL
* **Data Visualization & Dashboarding:** Tableau Public
* **Version Control & Documentation:** Git & GitHub

---

## 🔍 Key Insights & Recommendations
* **Geographic Budget Efficiency:** Analysis revealed specific regions experiencing budget underspends due to logistical access bottlenecks, prompting recommendations for deployable mobile outreach units.
* **Beneficiary Reach Trends:** Cumulative progress tracking indicated steady community engagement, though seasonal weather shifts introduced temporary drops in workshop attendance.
* **Demographic Equity:** Visual distribution breakdowns confirmed equitable participant inclusion across vulnerable demographics and community zones.

---

## 🚀 How to Explore This Repository
* `/data`: Contains the simulated CSV files (`Beneficiary_Master.csv`, `Activity_Log.csv`, `Budget_KPI_Target.csv`).
* `/sql`: Contains documented SQL queries used for data wrangling and calculating KPIs.
* **Tableau Public:** Click the link at the top to interact with filters for regions and project quarters.
