# 👥 HR Analytics Dashboard | Employee Attrition Analysis (Power BI)

An interactive Power BI dashboard that analyzes employee attrition across departments, age groups, gender, education fields, and job roles, helping HR teams understand **who is leaving and why**, and where to focus retention efforts.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Human%20Resources-blue)
![Type](https://img.shields.io/badge/Type-Attrition%20Analysis-green)

---

## 📌 Problem Statement

Employee attrition is costly: it increases hiring expenses, disrupts teams, and leads to loss of skills. This project answers key HR questions:

- What is the overall attrition rate, and how many employees have left?
- Which **departments, age groups, and education fields** see the highest attrition?
- How does attrition differ by **gender and age group**?
- How satisfied are employees across different **job roles**?

---

## 📊 Dashboard Preview

![HR Analytics Dashboard](screenshots/hr-analytics-dashboard.png)

---

## 📈 Key Metrics

| Metric | Value |
|--------|-------|
| Overall Employees | 1,470 |
| Attrition (employees left) | 237 |
| Attrition Rate | 16.12% |
| Active Employees | 1,233 |
| Average Age | 37 |

---

## 🔍 Key Insights

- **Department:** R&D accounts for the largest share of attrition (133 employees, 56.12%), followed by Sales (92, 38.82%) and HR (12, 5.06%).
- **Age group:** The 25–34 group has the highest attrition (112 employees), and also forms the largest part of the workforce. Attrition is lowest among employees over 55.
- **Education field:** Life Sciences (89) and Medical (63) see the most attrition, followed by Marketing (35) and Technical Degree (32).
- **Job satisfaction:** Sales Executives and Research Scientists are the largest roles, and their satisfaction ratings can be compared across levels 1–4 in the matrix.

---

## ✨ Features

- **KPI cards** for employees, attrition, attrition rate, active employees, and average age.
- **Department-wise attrition** pie chart.
- **Employees by age group and gender** stacked column chart.
- **Job satisfaction matrix** by job role and rating.
- **Education field-wise attrition** bar chart.
- **Attrition rate by gender for each age group** donut charts.
- **Education level slicers** (High School, Associate's, Bachelor's, Master's, Doctoral) to filter the whole dashboard.

---

## 🛠️ Tools & Technologies

| Area | Tools |
|------|-------|
| Visualization | Power BI Desktop |
| Data Transformation | Power Query |
| Calculations | DAX |
| Source Data | HR employee dataset (CSV/Excel) |

---

## 📁 Project Structure

```
├── README.md
├── HR_Analytics_Dashboard.pbix   # Power BI dashboard file
├── data/                         # Dataset (CSV/Excel)
└── screenshots/                  # Dashboard images
```

---

## ▶️ How to Run

1. Clone the repository:
   ```
   git clone https://github.com/RahulGaikwad2327/hr-analytics-dashboard.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, update the data source path to the dataset in the `data/` folder (Transform data → Data source settings).
4. Click **Refresh** and use the education slicers to explore the dashboard.

---

## 💡 Business Recommendations

- Focus retention programs on **R&D and Sales**, where most attrition occurs.
- Offer career growth and mentoring for the **25–34** age group.
- Review satisfaction levels in high-attrition job roles and act on low ratings.

---

## 🚀 Future Improvements

- Add a machine learning model to predict which employees are at risk of leaving.
- Include more factors such as salary, overtime, and years at company.
- Publish the report to Power BI Service for sharing.

---

## 👤 Author

**Rahul Gaikwad**
Final-year B.E. student, Artificial Intelligence & Data Science

- 📧 rahulgaikwad2327@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/rahul-gaikwad-92aa7b318/)
- 🐙 [GitHub](https://github.com/RahulGaikwad2327)