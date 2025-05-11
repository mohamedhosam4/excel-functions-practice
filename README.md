# Excel Data Analysis & Functions Practice 📊📈

Welcome to my Excel Data Analysis project!  
This workbook documents a complete set of hands-on exercises using **Excel formulas**, logic functions, and real-world-inspired KPIs. The aim is to develop and showcase strong spreadsheet analysis skills by solving tasks step-by-step with clarity and automation.

---

## 📁 Project File Overview

### `excel-functions-practice-with-doc.xlsx`

This Excel workbook contains the following sheets:

| Sheet Name     | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| 📄 Sales Data   | Main dataset with employee records, department info, and sales metrics.     |
| ✅ Tasks        | A checklist of tasks solved using Excel functions.                          |
| 📘 Documentation| In-depth documentation of each function, task, and logic used.              |

---

## ✅ Task Tracker Summary

| Task | Description | Status |
|------|-------------|--------|
| Total Orders | `SUM` to calculate total number of orders across all rows. | ✔️ |
| Average Sales per Month | `AVERAGEIF` used to get average monthly sales. | ✔️ |
| Count Sales Over $1000 | `COUNTIF` to find all sales over $1000. | ✔️ |
| Orders by Employee | `SUMIF` to total each employee’s orders. | ✔️ |
| Max Orders in IT | `MAXIFS` to extract max orders from IT department. | ✔️ |
| Average Rating per Department | `AVERAGEIF` to get average customer ratings per department. | ✔️ |
| Performance Tag | `IF` used to classify performance (High/Medium/Low). | ✔️ |
| Employees in Egypt with Sales > 2000 | `COUNTIFS` with country + sales condition. | ✔️ |
| Number of Employees per Department | `COUNTIF` grouped by department. | ✔️ |

---

## 🧪 Key Excel Functions Used

| Function | Purpose | Example |
|----------|---------|---------|
| `SUM` | Total sum of values | `=SUM(B2:B100)` |
| `AVERAGEIF` | Conditional average | `=AVERAGEIF(C2:C100, "March", D2:D100)` |
| `COUNTIF` | Count based on single condition | `=COUNTIF(D2:D100, ">1000")` |
| `COUNTIFS` | Count using multiple criteria | `=COUNTIFS(C:C, "Egypt", D:D, ">2000")` |
| `SUMIF` | Conditional summation | `=SUMIF(A:A, "Karim", D:D)` |
| `MAXIFS` | Find max value under conditions | `=MAXIFS(D:D, B:B, "IT")` |
| `AVERAGEIFS` | Multi-conditional average | `=AVERAGEIFS(D:D, C:C, "Jan", E:E, "Egypt")` |
| `IF` | Logical conditional output | `=IF(F2>4.5, 200, 100)` |
| `VLOOKUP` | Search and return related values | `=VLOOKUP("Lina", A2:D100, 2, FALSE)` |

---

## 📊 Metrics & Logic Implemented

- **Orders by Employee**: Aggregated using `SUMIF`.
- **Monthly Averages**: Calculated with `AVERAGEIF`.
- **High-Value Sales Count**: Filtered using `COUNTIF`.
- **Country-Specific Analysis**: Applied `AVERAGEIFS`, `COUNTIFS`.
- **Performance Classification**: Used `IF` logic to tag employees:
  - High: Sales > 3000
  - Medium: 1500 < Sales ≤ 3000
  - Low: Sales ≤ 1500
- **Bonuses**: $200 for rating > 4.5, otherwise $100.
- **Dynamic Lookups**: `VLOOKUP` to map employee names to departments.

---

## 🎯 Goals of This Project

- Practice core Excel analysis formulas through real tasks.
- Build a habit of documenting work in a reusable and clean format.
- Understand lookup functions, conditional filtering, and multi-criteria logic.
- Develop a structured analytical mindset suitable for dashboards or reports.

---

## 🧠 Skills Practiced

- 📌 Formula logic (`SUM`, `AVERAGEIF`, `COUNTIF`, `IF`, etc.)
- 📌 Grouped aggregation and filtering
- 📌 Conditional formatting and rule creation
- 📌 Lookup and reference management
- 📌 Planning, execution tracking, and self-review

---

## 🔮 Future Enhancements

- Recreate same logic using **Python (Pandas)**.
- Build visual dashboards using **Pivot Tables & Charts**.
- Add slicers and interactivity to drill into department-level insights.

---

## 🙋‍♂️ About Me

**Aspiring Data Analyst** 🚀  
Passionate about structured analysis, real-world problem-solving, and automation using tools like Excel and Python.  
This project reflects my ability to approach data with clarity and extract insights with precision.
