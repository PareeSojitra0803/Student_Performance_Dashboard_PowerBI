# 🎓 Student Performance Dashboard  
## Academic & Behavioral Insights (Power BI Practical Exam)

> **Final Practical Examination Project** — built to analyze **student academic performance, attendance patterns, and behavioral insights** using structured data modeling, DAX, and advanced Power BI interactivity.

---

## ✨ Project Overview

This project is a **complete end-to-end Power BI solution**, designed and executed under **practical exam constraints**, with emphasis on:

- Clean and logical **data modeling**
- Purpose-driven **DAX calculations**
- Insightful **academic & behavioral analysis**
- Professional **dashboard design and UX**
- Real-world **interactivity and storytelling**

The dashboard enables educators and stakeholders to **monitor student performance**, **identify behavioral trends**, and **drill down into individual student profiles** seamlessly.

---

## 🧩 Project Objectives

- Build a **relational data model** using multiple CSV datasets
- Calculate **academic KPIs** using DAX
- Analyze **attendance and behavior patterns**
- Create **interactive multi-page dashboards**
- Implement **drillthrough, tooltips, bookmarks**
- Design a **mobile-optimized layout**

---

## 🗂️ Repository Structure

├── Student Performance Dashboard - Academic & Behavioral Insights.pbix
│
├── Data/
│ ├── Students - Students.csv
│ ├── Scores - Scores.csv
│ ├── Attendance - Attendance.csv
│ └── Behavior - Behavior.csv
│
├── Icons/
│ ├── 001-filter.png
│ └── 002-filter-1.png
│
├── Output/
│ ├── Academic Overview.png
│ ├── Student Details.png
│ ├── Custom Tooltip.png
│ ├── FilterPane Using Bookmarks.png
│ ├── Dashboard.mp4
│ └── Mobile Layout.mp4
│
└── README.md


---

## 📦 Data Sources

| File | Description |
|-----|-------------|
| **Students.csv** | StudentID, Name, Gender, Class, Section |
| **Scores.csv** | StudentID, Subject, ExamType, Score, MaxScore, Term |
| **Attendance.csv** | StudentID, Date, Status (Present/Absent), Reason |
| **Behavior.csv** | StudentID, Date, BehaviorType, Notes |

✔ All datasets cleaned in **Power Query**  
✔ Correct data types applied  
✔ Relationships created using **StudentID**

---

## 🧠 Data Model Design

- Centralized student-based model
- One-to-many relationships across:
  - Scores
  - Attendance
  - Behavior
- Optimized for **filter propagation and drillthrough**
- Unnecessary columns hidden for clarity

---

## 📐 DAX Measures & Calculations

### 🔢 Academic Metrics
- `% Score = Score / MaxScore`
- `Average Score`
- `Average Score by Subject`
- `Average Score by Term`

### 🕒 Attendance Metrics
- `Attendance %`
- `Present Students`
- `Absent Students`

### 🧩 Behavioral Metrics
- `Behavior Count by Type`

### 🎯 Performance Classification
- `Performance Category (High / Medium / Low)`
  - Implemented using `SWITCH`

---

## 📊 Dashboard Pages & Visuals

### 🟣 Academic Overview Page

![Academic Overview](Output/Academic%20Overview.png)

**Key Insights:**
- Total Students, Attendance %, Average Score KPIs
- Performance trend across **Terms**
- Subject-wise academic comparison
- Student behavior distribution
- Top 10 performing students with conditional formatting

---

### 👤 Student Details Page (Drillthrough)

![Student Details](Output/Student%20Details.png)

**Features:**
- Individual student profile
- Average score & attendance
- Behavior breakdown
- Context-aware drillthrough experience

---

## 🎯 Interactivity & UX Enhancements

### 🔘 Filter Pane using Bookmarks
![Filter Pane](Output/FilterPane%20Using%20Bookmarks.png)

- Custom show/hide slicer panel
- Controlled via bookmarks & buttons
- Custom filter icons used

### 🧠 Custom Tooltip
![Tooltip](Output/Custom%20Tooltip.png)

- Contextual insights on hover
- Enhances analytical depth without clutter

---

## 📱 Mobile Layout

The dashboard is optimized for **Power BI Mobile App** viewing 📲

🎥 Mobile Layout Demo:  
➡️ `Output/Mobile Layout.mp4`

---

## 🎥 Dashboard Walkthrough

🎬 Full dashboard recording demonstrating:
- Page navigation
- Interactions
- Drillthrough
- Filters & tooltips

➡️ `Output/Dashboard.mp4`

---

## 🏆 Practical Exam Coverage

| Component | Status |
|--------|--------|
| Data Modeling & Cleaning | ✅ |
| DAX Calculations | ✅ |
| Visualizations & Storytelling | ✅ |
| Slicers & Filters | ✅ |
| Drillthrough | ✅ |
| Tooltips | ✅ |
| Bookmark Navigation | ✅ |
| Mobile Layout (Optional) | ✅ |

---

## 🚀 Final Remarks

This project demonstrates not only **technical proficiency in Power BI**, but also:

- Analytical thinking
- UI/UX discipline
- Story-driven dashboard design
- Real-world BI problem solving

> 📌 **Submitted as Practical Examination Work**

---

### 👤 Author

**Paree G. Sojitra**  
Power BI & Data Analytics Enthusiast  
📍 Surat, India
