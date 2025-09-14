# 📊 Returns Performance & Employee Insights Dashboard

This project is a **Power BI dashboard** that provides insights into product returns across different regions and employees.  
The goal is to analyze **return trends, return rates, employee-wise performance, and YoY comparisons** for effective decision-making.  

---

## 🚀 Features

- **KPI Cards**  
  - Return Rate % (with YoY change)  
  - Avg. Return Value (with YoY change)  
  - Return Count (with YoY change)  

- **Visualizations**  
  - 📈 Line Chart → Monthly Return Trend with YoY overlay  
  - 📊 Bar Chart → Top 5 Employees/Regions by Return Count with YoY comparison  
  - 🍩 Donut Chart → % Contribution of Each Employee/Region with YoY tooltip  
  - 🎛 Filters & Slicers → by Employee, Region, and Date  

- **Interactivity**  
  - Cross-filtering enabled between all visuals  
  - Drill-down by **Region** and **Person**  

---

## 🗂 Dataset

- **Orders (2014–2016)** → Order details  
- **Returns** → Returned status (Yes/No) + Order ID  
- **People** → Region & Employee mapping  
- **Date Table** → Custom date dimension for time intelligence  

---

## 🧮 DAX Measures

- `Return Rate % = Returned Orders / Total Orders`  
- `Avg Return Value = Average of Returned Order Values`  
- `Return Count = Count of Returned Orders`  
- YoY comparisons using `SAMEPERIODLASTYEAR()`  
- Custom KPI measures with ▲ / ▼ arrows for performance tracking  

---

## 📸 Dashboard Preview

![Return Performance Dashboard](https://github.com/abdulmossawer/Returns_Performance_Employee_Insights/blob/main/dashboard/screenshot/ReturnPerformanceDashboard.png)

---

## 📂 Project Structure

Returns_Performance_Employee_Insights/
│
├── dashboard/
│ └── screenshot/
│ └── ReturnPerformanceDashboard.png
│
├── data/
│ ├── orders2014.csv
│ ├── orders2015.csv
│ ├── orders2016.csv
│ ├── Returns.xlsx
│ └── People.xlsx
│
└── README.md


---

## 🎯 Key Insights

- Return Rate % trend shows seasonal spikes in certain months.  
- West region contributes the highest % of returns compared to other regions.  
- Some employees/regions have consistently higher return counts YoY.  
- Average return value decreased slightly in recent years despite higher return counts.  

---

## 🛠 Tools & Technologies

- **Power BI** → Data modeling, DAX calculations, dashboard design  
- **Excel/CSV** → Data sources  
- **GitHub** → Version control & project showcase  

---

## 🙌 Author

**Abdul Mossawer**  
Data Enthusiast  

📌 [LinkedIn](https://www.linkedin.com/in/analystmossawer/) | [GitHub](https://github.com/abdulmossawer)

---
