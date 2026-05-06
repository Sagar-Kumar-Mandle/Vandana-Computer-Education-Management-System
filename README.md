# 🎓 Vandana Computer Education Management System (VCEMS)

A complete Student Management System built in Excel for **Vandana Computer Education, Bhilai** - tracking admissions, fee payments, course progress, and institutional analytics across multiple academic years, all from a single workbook.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Tools & Technologies](#️-tools--technologies)
- [Workbook Structure](#️-workbook-structure)
- [Key Metrics & KPIs](#-key-metrics--kpis)
- [Dashboard](#-dashboard)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Key Insights](#-key-insights)
- [How to Use This Project](#️-how-to-use-this-project)
- [Author & Contact](#-author--contact)

---

## 📖 Overview

VCEMS is a fully self-contained Excel-based student management and analytics system. It handles the complete student lifecycle from admission to course completion while giving management a real-time view of enrollment trends, revenue, batch performance, and geographic reach.

The system covers **375 students** across **16 courses**, **4 batch timings**, and **4 academic sessions** (2024 through 2025-26), with a revenue of **₹21.9 Lakh** and a **96.53% course completion rate**.

---

## 💼 Business Problem

Running a computer education institute involves managing dozens of moving parts at once new admissions every week, fee installments tracked manually, students dropping mid-course, batch timings across morning and evening slots, and no centralized way to see how the institute is actually performing.

VCEMS was built to solve exactly that. Instead of scattered registers and spreadsheets, everything lives in one place student records, payment histories, discontinuation tracking, ongoing course monitoring, and a visual dashboard that updates automatically as data changes.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** - cCre platform for the entire system
- **Pivot Tables** - Aggregated data analysis and cross-tabulation
- **Excel Charts** - Bar charts, donut charts, line graphs, and combo charts
- **Slicers** - Interactive filtering by certification type, session, course duration, and course code
- **Conditional Formatting** - Status highlights and payment tracking
- **Excel Formulas** -  Dynamic KPI calculations, fee balance tracking, completion logic
- **VBA / Hyperlinks** - Navigation tiles on the Home Page for quick sheet access

---

## 🗂️ Workbook Structure

The workbook is organized into **6 sheets**, split into two categories accessible from the Home Page navigation dashboard.

### Data Sheets

| Sheet | Purpose |
|---|---|
| **Main Sheet** | Master student database all 375 records with personal details, course info, fee structure, and installment history |
| **Admission** | Auto-generated admission slips with student details and payment summary |
| **Discontinued** | Records of students who dropped their course mid-way (6 students) |
| **Ongoing** | Students currently enrolled and still completing their course (7 students) |

### Analytics Sheets

| Sheet | Purpose |
|---|---|
| **Pivot Tables** | Aggregated views for enrollment by course, area, batch, session, and duration |
| **Dashboard** | Visual KPI overview, interactive charts with slicers |

---

## 📊 Key Metrics & KPIs

| Metric | Value |
|---|---|
| Total Revenue | ₹21.9 Lakh |
| Total Enrollment | 375 Students |
| Course Completions | 362 |
| Discontinued | 6 |
| Ongoing | 7 |
| Completion Rate | 96.53% |
| Sessions Covered | 2024, 2024-25, 2025, 2025-26 |
| Total Courses Offered | 16 |
| Geographic Areas Covered | 10+ areas across Bhilai |

---

## 📸 Dashboard

### Home Page — Navigation Hub
![VCEMS Home Page](Images\home_page.png)

### Analytics Dashboard
![VCEMS Analytics Dashboard](Images\dashboard_sheet.png)

---

## 🧹 Data Cleaning & Preparation

The Main Sheet contains 375 student records with 49 columns each. Here's how the data was structured and maintained:

**Student Records** include name, date of birth, father's name, mother's name, address, area, contact number, Gmail ID, highest qualification, caste, medium, and document submission status.

**Fee Tracking** uses a multi-installment structure up to 6 payment slots per student with individual dates and running balances, allowing the institute to monitor outstanding dues at any point in time.

**Course Data** captures course name, course code, certification type (Diploma or Certification), session year, duration (3 Month / 6 Month / 1 Year), batch timing, and batch name.

**Status Flags** students are tagged as On-Board, Discontinued, or Ongoing and flow into separate sheets for targeted tracking.

Dates are stored as Excel serial numbers and formatted as DD/MM/YYYY for readability. All fee columns use consistent numeric formats to avoid formula errors in balance calculations.

---

## 💡 Key Insights

**Enrollment is growing fast.** The institute enrolled 199 students in 2024, jumped to 243 in 2024-25, reached 114 in 2025 (mid-year), and already has 18 enrolled for 2025-26  showing strong year-over-year momentum.

**3-Month courses dominate.** Out of 375 students, 246 (65.6%) enrolled in 3-month certification courses, followed by 6-month programs (67 students) and 1-year diploma courses (62 students). Short-duration courses are clearly the most in-demand.

**CDTP leads course enrollment.** CDTP tops the course enrollment chart with 34 students, closely followed by English Typing (33), PGDCA (32), and MS-CIT (32). The diversity across 16 courses shows the institute serves a wide range of skill needs.

**Morning Batch 1 is the most popular.** The morning slot (44% of enrollment) is the highest-attended, followed by Evening Batch 1 (20%), Afternoon Batch 1 (20%), and Afternoon Batch 2 (16%).

**Sector-04 sends the most students.** With 56 students, Sector-04 is the top source area by far, followed by Vaishali Nagar (25) and Sector-09 (24). Geographic concentration in nearby sectors suggests strong local brand recognition.

**Completion rate is exceptional.** A 96.53% completion rate across 375 enrollments  with only 6 discontinuations reflects strong student retention and course quality.

**April and November are peak enrollment months.** Monthly enrollment trends show April hitting 38 admissions and November reaching 40 the two highest months. January through March show consistent baseline enrollment of 31-34 per month.

---

## 🖥️ How to Use This Project

1. **Download** the `.xlsx` file
2. **Open** in Microsoft Excel 2016 or later
3. Start from the **Home Page** click any tile to jump directly to that sheet
4. On the **Dashboard**, use the slicers on the left to filter by:
   - Certification Type (Certification Course / Diploma Course)
   - Session (2024, 2024-25, 2025, 2025-26)
   - Course Duration (1 Year, 3 Month, 6 Month)
   - Course Code (BCC, CCC, DCA, PGDCA, Tally, etc.)
5. All charts and KPI cards update automatically based on your filter selection
6. To add a new student, enter their details in the **Main Sheet** following the existing column structure pivot tables and the dashboard will refresh on the next open or manual refresh


---

## 👤 Author & Contact

**Sagar Kumar Mandle**
Data Analyst | Excel & Power BI

🔗 GitHub: [github.com/Sagar-Kumar-Mandle](https://github.com/Sagar-Kumar-Mandle)

---

*Built with Microsoft Excel · Pivot Tables · Data Visualization · Education Analytics*
