# 👥 Employee Life Circle Analysis

A multi-page Power BI report that tracks the full employee lifecycle — from workforce composition and attrition through performance ratings and training gaps — giving HR teams and leadership a data-driven view of workforce health.

---

## 📁 File

| File | Description |
|------|-------------|
| `Employee_Life_Circle_Analysis.pbix` | Power BI Desktop report file |

---

## 📌 Overview

This dashboard covers four key stages of the employee lifecycle:

1. **Workforce Overview** — who is in the organization right now
2. **Attrition & Retention** — who is leaving and why
3. **Performance** — how employees are rated across roles and departments
4. **Training** — training frequency, gaps, and their connection to attrition

The report uses the **Frontier** theme and is built on a **1280 × 720** canvas across all pages.

---

## 📐 Report Structure

| # | Page Name | Description |
|---|-----------|-------------|
| 1 | Workforce Overview | High-level headcount, employment type, qualifications |
| 2 | Attrition & Retention | Resignation trends, exit reasons, attrition by department |
| 3 | Performance | Performance ratings by role, qualification, and department |
| 4 | Training | Training recency, gaps, and link to resignation patterns |

---

## 📊 Page-by-Page Visual Breakdown

---

### Page 1 — Workforce Overview

Provides a snapshot of the current workforce composition.

#### KPI Cards

| Metric | Value | Description |
|--------|-------|-------------|
| **Total Employees** | 3,000 | Total headcount across the organization |
| **Active Employees** | 1,531 | Employees currently employed |
| **Resigned Employees** | 1,469 | Employees who have left |
| **Full Time Employee** | 1,538 | Count of full-time staff |
| **Contract Employee** | 1,462 | Count of contract staff |

#### Charts & Visuals

| Visual | Type | Description |
|--------|------|-------------|
| **Active Vs Resigned** | Donut Chart | 1,531 active (51.03%) vs 1,469 resigned (48.97%) |
| **Fulltime % vs Contract %** | Donut Chart | 51.27% full-time vs 48.73% contract |
| **Head Count by Department (Active vs Resigned)** | Column Chart | Active and resigned employee counts per department |
| **Qualification Distribution** | Clustered Column Chart | Professional Cert leads, followed by BA, BSc, MSc, HND, MBA, Diploma |
| **Role Breakdown Table** | Table | Role-level view of Active and Resigned employee counts |

---

### Page 2 — Attrition & Retention

Explores why employees are leaving and where attrition is highest.

#### KPI Cards

| Metric | Value | Description |
|--------|-------|-------------|
| **Attrition Rate %** | 48.97% | Overall percentage of employees who have resigned |
| **Retention Rate %** | 51.03% | Percentage of employees still active |
| **FT Attrition Rate %** | 49.48% | Attrition rate specific to full-time employees |
| **Avg Tenure (Resigned)** | 18.13 months | Average months of service before resignation |
| **Avg Tenure (Active)** | 36.56 months | Average months of service for current employees |

#### Charts & Visuals

| Visual | Type | Description |
|--------|------|-------------|
| **Attrition Rate % by Department** | Clustered Bar Chart | Sales leads attrition, followed by Engineering and Finance |
| **Exit Interview Reason** | Clustered Bar Chart | Career Change is the top reason, followed by Better Opportunity and Low Compensation |
| **Resignation Date by Year** | Stacked Area Chart | Resignations peaked sharply around 2024 |
| **Active and Resigned by Employment Status** | Clustered Column Chart | Full-time and contract employees show near-equal active/resigned splits |
| **Attrition by Qualification Table** | Table | See breakdown below |

**Attrition by Qualification:**

| Qualification | Total | Active | Resigned | Attrition Rate % | Avg Perf Rating |
|---------------|-------|--------|----------|------------------|-----------------|
| BA | 470 | 244 | 226 | 48.09% | 3.16 |
| BSc | 434 | 221 | 213 | 49.08% | 3.02 |
| Diploma | 372 | 204 | 168 | 45.16% | 2.98 |
| HND | 418 | 200 | 218 | 52.15% | 3.05 |
| MBA | 406 | 213 | 193 | 47.54% | 3.04 |
| MSc | 424 | 199 | 225 | 53.07% | 3.00 |
| Professional Cert. | 476 | 250 | 226 | 47.48% | 3.00 |
| **Total** | **3,000** | **1,531** | **1,469** | **48.97%** | **3.04** |

---

### Page 3 — Performance

Drills into how employees are rated, and whether performance differs between active and resigned staff.

> ℹ️ This page supports **drillthrough** — right-click a department on any other page to navigate here filtered by that department.

#### KPI Cards

| Metric | Value | Description |
|--------|-------|-------------|
| **Avg Performance Rating** | 3.04 | Overall average rating across all employees |
| **Avg Perf Rating (Active)** | 3.04 | Average rating for currently active employees |
| **Avg Perf Rating (Resigned)** | 3.04 | Average rating for employees who resigned |
| **High Performers** | 628 | Count of employees with top ratings |
| **Low Performers** | 581 | Count of employees with bottom ratings |

#### Charts & Visuals

| Visual | Type | Description |
|--------|------|-------------|
| **Total Employees by Rating** | Column Chart | Fairly even distribution across Ratings 1–5; Rating 5 is slightly highest |
| **Active vs Resigned by Rating** | Clustered Column Chart | Active and resigned employees are nearly equal across all rating bands |
| **Avg Performance Rating by Qualification** | Column Chart | All qualifications cluster tightly around 3.0; BA scores slightly higher |
| **Avg Performance Rating by Department** | Radar Chart | All departments score around 2.7–3.2; fairly balanced across the org |
| **Performance by Role Table** | Table | Role-level view of average performance rating for active employees |

**Notable Role Ratings (Active Employees):**

| Role | Avg Perf Rating |
|------|-----------------|
| Product Analyst | 3.45 ⬆ highest |
| QA Tester | 2.33 ⬇ lowest |
| Account Executive | 3.34 |
| Accountant | 2.65 |
| HR Generalist | 2.08 |

---

### Page 4 — Training

Examines training recency and gaps, and their relationship to employee retention.

#### KPI Cards

| Metric | Value | Description |
|--------|-------|-------------|
| **Avg Training Gap (Active)** | 27.23 months | Avg months since last training — active employees |
| **Avg Training Gap (Resigned)** | 27.31 months | Avg months since last training — resigned employees |
| **Average Tenure** | 27.54 months | Overall average tenure across all employees |
| **Avg Tenure (Resigned)** | 18.13 months | Average tenure of employees before resignation |
| **Lack of Growth Exit** | 145 | Employees who cited lack of growth as their exit reason |

#### Charts & Visuals

| Visual | Type | Description |
|--------|------|-------------|
| **Training Date by Year** | Line Chart | Training activity grew steadily, peaking around 2024 near 1,000 events |
| **Exit Reason Distribution** | Column Chart | Career Change leads, followed by Better Opportunity and Low Compensation |
| **Tenure Distribution — Resigned Employees** | Funnel Chart | See breakdown below |
| **Training Gap & Performance by Department** | Table | All departments average ~26–28 months since last training |
| **Training Gap by Qualification** | Table | See breakdown below |

**Tenure Distribution of Resigned Employees:**

| Tenure Band | Resigned Employees |
|-------------|-------------------|
| 0–6 months | 430 (largest group) |
| 7–12 months | 259 |
| 25–36 months | 230 |
| 13–18 months | 181 |
| 19–24 months | 170 |
| 37–48 months | 106 |
| 48+ months | 93 (smallest group) |

**Training Gap by Qualification:**

| Qualification | Avg Gap (All) | Avg Gap Active | Avg Gap Resigned |
|---------------|---------------|----------------|------------------|
| BA | 26.92 | 26.86 | 26.98 |
| BSc | 27.24 | 25.90 | 28.63 |
| Diploma | 26.43 | 27.04 | 25.70 |
| HND | 27.66 | 28.00 | 27.35 |
| MBA | 26.34 | 26.58 | 26.08 |
| MSc | 29.15 | 30.15 | 28.27 |
| Professional Cert. | 27.06 | 26.51 | 27.68 |
| **Total** | **27.27** | **27.23** | **27.31** |

---

## 🗄️ Data Model

### Primary Table: `employee_lifecycle_data`

| Column | Description |
|--------|-------------|
| `Role` | Employee job role/title |
| `Department` | Department the employee belongs to |
| `Qualification` | Highest educational qualification |
| `Employment Status` | Full-time or Contract |
| `Resignation Date` | Date of resignation (null if still active) |
| `Exit Interview Reason` | Stated reason for leaving |
| `Last Training Date` | Date of most recent training |
| `Tenure Distribution` | Bucketed tenure band (e.g., 0–6 months, 7–12 months) |
| `Rating` | Performance rating score (1–5) |

---

### Measures Table: `Key Measures`

| Measure | Value | Description |
|---------|-------|-------------|
| `Total Employees` | 3,000 | Total headcount |
| `Active Employees` | 1,531 | Employees with no resignation date |
| `Resigned Employees` | 1,469 | Employees with a resignation date |
| `Full Time Employee` | 1,538 | Count of full-time employees |
| `Contract Employee` | 1,462 | Count of contract employees |
| `Fulltime %` | 51.27% | Percentage of workforce on full-time contracts |
| `Contract %` | 48.73% | Percentage of workforce on contract |
| `Attrition Rate %` | 48.97% | Resigned ÷ Total Employees |
| `Retention Rate %` | 51.03% | Active ÷ Total Employees |
| `FT Attrition Rate %` | 49.48% | Attrition rate for full-time employees only |
| `Avg Tenure Active` | 36.56 months | Average months of service — active employees |
| `Avg Tenure Resigned` | 18.13 months | Average months of service — resigned employees |
| `Average Tenure` | 27.54 months | Overall average tenure |
| `Avg Performance Rating` | 3.04 | Mean performance rating — all employees |
| `Avg Perf Rating Active` | 3.04 | Mean performance rating — active employees |
| `Avg Perf Rating Resigned` | 3.04 | Mean performance rating — resigned employees |
| `High Performers` | 628 | Count of employees with top rating |
| `Low Performers` | 581 | Count of employees with lowest rating |
| `Avg Training Gap Active` | 27.23 months | Avg months since last training — active employees |
| `Avg Training Gap Resigned` | 27.31 months | Avg months since last training — resigned employees |
| `Avg Training Gap Months` | 27.27 months | Overall average training gap |
| `Training Gap Label` | Text | Label for training gap (e.g., "Overdue") |
| `Lack of Growth Exit` | 145 | Employees citing lack of growth as exit reason |
| `Dept Headcount Label` | — | Label used for drillthrough filtering by department |

---

## 🔍 Key Insights

### 🏢 Workforce Composition
- Out of **3,000 employees**, **1,531 (51.03%) are active** and **1,469 (48.97%) have resigned** — an almost perfectly even split that signals a significant retention problem.
- The workforce is nearly equally divided between **full-time (51.27%, 1,538)** and **contract (48.73%, 1,462)** staff. Nearly half the workforce being on contract increases churn risk and reduces institutional knowledge retention.
- **Professional Certificate holders (476)** form the largest qualification group, followed by BA (470) and BSc (434). Diploma holders are the smallest group at 372.
- Roles like **Account Executive (73 resigned vs 58 active)** and **Sales Associate (71 resigned vs 49 active)** show more resignations than active employees — flagging these as high-risk roles.

### 📉 Attrition & Retention
- The **overall attrition rate is 48.97%** — nearly 1 in 2 employees has left — which is critically high by any industry standard. Full-time attrition at **49.48%** is equally alarming.
- Employees who resigned had an **average tenure of only 18.13 months**, compared to **36.56 months** for active employees. This means most resignations happen well before the 2-year mark, pointing to early engagement and onboarding failures.
- **430 resignations (the largest group) occurred within the first 0–6 months** of employment. This is the single most critical finding — the organization is losing employees almost immediately after hiring them.
- **Sales has the highest attrition rate** by department, followed by Engineering and Finance. These three departments require the most urgent HR intervention.
- The **top exit reason is Career Change**, followed by **Better Opportunity** and **Low Compensation** — suggesting employees don't see a long-term future in the organization and feel underpaid relative to the market.
- **145 employees cited Lack of Growth** as their exit reason — a direct signal that career development and promotion pathways are insufficient.
- **MSc holders have the highest attrition rate at 53.07%**, followed by HND at 52.15%. Higher-educated employees are leaving at above-average rates, suggesting the organization may not be offering roles or growth that match their qualifications.
- Resignations grew sharply year-on-year, **peaking around 2024**, indicating the attrition problem is worsening rather than stabilizing.

### 📈 Performance
- The **average performance rating is 3.04 out of 5** across all employees, and strikingly, **active (3.04) and resigned (3.04) employees share the exact same average rating**. This means the organization is not selectively losing low performers — attrition is spread evenly across performance levels.
- There are **628 high performers** and **581 low performers**, with the majority of employees clustering in the middle rating bands.
- **Product Analyst is the highest-rated active role at 3.45**, while **QA Tester is the lowest at 2.33** — a gap of over 1 full point, suggesting significant variation in performance standards or role clarity across teams.
- The **Radar Chart shows all departments scoring between 2.7 and 3.2**, with no single department dramatically outperforming or underperforming — performance issues are systemic rather than department-specific.
- Performance rating shows **minimal variation by qualification level**, with all groups hovering around 3.0. Education level alone is not a strong predictor of performance in this organization.

### 🎓 Training
- The **average training gap is virtually identical for active (27.23 months) and resigned (27.31 months) employees** — only an 8-day difference. This suggests training frequency alone is not what's driving attrition.
- However, **145 employees cited Lack of Growth as their exit reason**, which points to a quality-of-development problem rather than a frequency problem. Employees are being trained but not developed or promoted.
- **MSc holders have the highest training gap at 29.15 months overall**, and 30.15 months for active MSc employees — suggesting the most highly qualified staff are waiting the longest between training opportunities.
- The **BSc resigned group has a notably higher gap (28.63 months) than their active counterparts (25.90 months)** — one of the clearest qualification-level signals that training recency may contribute to specific group departures.
- Training activity **grew steadily year-on-year, peaking near 1,000 events in 2024**, which aligns with the resignation peak — suggesting training investment increased reactively as attrition worsened, rather than proactively.
- The **0–6 month tenure band accounts for 430 resignations** — far exceeding any other band. Given that average training gaps exceed 27 months, new employees are likely leaving before they ever receive meaningful training or development.

---

## 🎨 Theme & Styling

| Setting | Value |
|---------|-------|
| Base Theme | CY26SU02 |
| Custom Theme | Frontier |
| Canvas Size | 1280 × 720 |
| Display Option | Fit to Page |
| Custom Visuals | Radar Chart, KPI Viz |
| Page Backgrounds | Blue-grey tinted per page |

---

## ⚙️ Report Settings

| Setting | Value |
|---------|-------|
| Drillthrough | Enabled — Page 3 (Performance) filtered by Department |
| Cross-Visual Drill Filtering | Enabled on all visuals |

---

## 🚀 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (latest version recommended)

### Opening the Report

1. Clone or download this repository.
2. Open `Employee_Life_Circle_Analysis.pbix` in Power BI Desktop.
3. Update the data source under **Home → Transform Data → Data Source Settings**.
4. Click **Home → Refresh** to load your data.

### Using Drillthrough

On the **Workforce Overview** or **Attrition & Retention** pages, right-click any department data point and select **Drillthrough → Performance** to open a department-filtered performance view.

### Connecting Your Data

The report expects a dataset with at minimum these fields:

- `Role`, `Department`, `Qualification`, `Employment Status`
- `Resignation Date`, `Exit Interview Reason`
- `Last Training Date`, `Rating`

---

## 📬 Contributing

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature/employee-lifecycle-update`
3. Commit your changes: `git commit -m "Describe your change"`
4. Push to the branch: `git push origin feature/employee-lifecycle-update`
5. Open a Pull Request.

