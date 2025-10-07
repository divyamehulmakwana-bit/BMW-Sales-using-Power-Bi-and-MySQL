# BMW Sales Dashboard (Power BI + MySQL)

> An interactive sales analytics dashboard for BMW — exploring global sales, model performance, fuel/tranmission trends, and regional insights.

---

## 🧭 Project Overview

This dashboard is built using a **BMW sales dataset** (50,000+ rows) covering variables such as Model, Year, Region, Color, Fuel_Type, Transmission, Engine_Size_L, Mileage_KM, Price_USD, Sales_Volume, and Sales_Classification.  
The goal: turn raw sales data into business insights through visual analytics, model-level breakdowns, and interactive exploration.

**Dataset source:**  
Kaggle — *BMW Sales Dataset*  
(https://www.kaggle.com/datasets/eshummalik/bmw-sales-dataset)

**Repository:**  
This repo contains the Power BI report, MySQL model connection, and screenshot folder highlighting dashboard design and features.

---

## 🎯 Objectives & Questions Addressed

- Which region generates the most revenue and unit sales?  
- How do different BMW models compare in performance, revenue, and trends?  
- What are the dominant fuel types and transmission splits across models?  
- How have total revenue and unit sales evolved over time globally and by model?  
- Which model–region combinations are underperforming or overperforming?

---

## 🛠️ Tech Stack & Tools

| Technology | Purpose |
|------------|---------|
| Power BI Desktop | Visualization & interactive dashboard |
| MySQL | Underlying data storage & query engine |
| Git / GitHub | Version control & project hosting |
| DAX | Measures, KPIs, trend calculations |
| Markdown | README documentation with embedded visuals |

---

## 📊 Executive Summary

**Key Performance Indicators (KPIs):**  
- **Total Revenue:** \$19.07 Trillion  
- **Total Units Sold:** 253 Million  
- **Best Region:** Asia — \$3.25 Trillion  
- **Top Model:** 7 Series — 24 Million units  
- **Most-Sold Fuel Type:** Hybrid (25.5%)  
- **Peak Year:** 2022 — ~18M units, \$1.3T revenue  

_Executive Summary screenshot:_  
![Executive Summary](Screenshots/Executive%20Summary.png)  

From the summary page, users can see the big picture trends, filter by regions, and dive deeper into model-level data.

---

## 📂 Dashboard Pages Overview

### 🏠 Home Page  
A lightweight navigation page that leads users to the Executive Summary.  
![Home Page](Screenshots/Home%20Page.png)

### 📈 Executive Summary  
Displays KPIs, trend charts, fuel-type breakdown, world sales map, and model-wise revenue bars with classification.  
Users immediately grasp overarching patterns in the BMW sales universe.

### 🔍 Detailed Analysis Page (Per-Model)  
Allows filtering by **Model**, then shows:  
- KPI cards (region, units, revenue, avg price, mileage)  
- Region × Sales Classification bar charts  
- Fuel type & Transmission donuts  
- Time-trend charts of revenue + units  
- Embedded model images and gallery  
- Tabs to segment insights visually

---

## 🚗 Model-Wise Analysis Highlights

Here are the key insights by model that showcase variation across regions, fuel types, and performance:

### Series 3  
- **Top Region:** Asia — \$302B  
- **Units Sold:** 23M  
- **Avg Price:** \$75,570  
- **Avg Mileage:** 100,160 km  
- **Highest Rev Regions (High / Low):**  
 • Europe: \$162B / \$142B  
 • Asia (next best)  
- **Fuel Type:** Hybrid dominates  
- **Color:** Silver > Blue  
- **Transmission:** ~50 / 50 split  
- **Peak Year:** 2016  
- ![Series 3 Details](Screenshots/Series%203%20Details.png)

### Series 5  
- **Top Region:** Africa — \$306B  
- **Units Sold:** 23M  
- **Avg Price:** \$75,290  
- **Avg Mileage:** 101,360 km  
- **Top Rev (High / Low):**  
 • Africa: \$155B / \$151B  
 • Asia: \$154B / \$135B  
- **Color:** White > Grey  
- **Fuel Type:** Petrol leads  
- **Transmission:** ~50 / 50 split  
- **Peak Year:** 2016  
- ![Series 5 Details](Screenshots/Series%205%20Details.png)

### Series 7  
- **Top Region:** North America — \$314B  
- **Units Sold:** 24M  
- **Avg Price:** \$75,750  
- **Avg Mileage:** 100,970 km  
- **Top Rev (High / Low):**  
 • North America: \$161B / \$154B  
 • Middle East: \$155B / \$154B  
- **Color:** Black > Silver  
- **Fuel Type:** Hybrid leads  
- **Transmission:** ~50 / 50 split  
- **Peak Year:** 2017  
- ![Series 7 Details](Screenshots/Series%207%20Details.png)

### i3  
- **Top Region:** Africa — \$292B  
- **Units Sold:** 23M  
- **Avg Price:** \$74,800  
- **Avg Mileage:** 98,730 km  
- **Highest Rev Regions:**  
 • North America: \$148B / \$147B  
 • Europe: \$150B / \$144B  
- **Fuel Type:** Diesel leads  
- **Color:** Grey > Blue  
- **Transmission:** ~50 / 50 split  
- **Peak Year:** 2012  
- ![i3 Details](Screenshots/i3%20Details.png)

### i8  
- **Top Region:** Europe — \$322B  
- **Units Sold:** 23M  
- **Avg Price:** \$75,370  
- **Avg Mileage:** 99,450 km  
- **Top Rev (High / Low):**  
 • Europe: \$147B / \$148B  
 • Asia: \$159B / \$142B  
- **Fuel Type:** Hybrid  
- **Color:** Silver > White > Black  
- **Peak Year:** 2018  
- ![i8 Details](Screenshots/i8%20Details.png)

### M3  
- **Top Region:** Asia — \$204B  
- **Units Sold:** 22M  
- **Avg Price:** \$74,840  
- **Avg Mileage:** 99,970 km  
- **High / Low Rev Regions:**  
 • Asia: \$156B / \$148B  
 • Middle East: \$149B / \$137B  
- **Fuel Type:** Hybrid  
- **Color:** Red > Blue > Grey  
- **Peak Year:** 2022  
- ![M3 Details](Screenshots/M3%20Details.png)

### M5  
- **Top Region:** Europe — \$294B  
- **Units Sold:** 23M  
- **Avg Price:** \$74,470  
- **Avg Mileage:** 102,340 km  
- **High / Low Rev Regions:**  
 • Middle East: \$148B / \$150B  
 • Asia: \$155B / \$140B  
- **Fuel Type:** Hybrid  
- **Color:** White > Silver > Red  
- **Peak Years:** 2021 & 2019  
- ![M5 Details](Screenshots/M5%20Details.png)

### X1  
- **Top Region:** Asia — \$310B  
- **Units Sold:** 23M  
- **Avg Price:** \$75,260  
- **Avg Mileage:** 100,380 km  
- **High / Low Rev Regions:**  
 • Asia: \$158B / \$152B  
 • North America: \$153B / \$145B  
- **Fuel Type:** Electric dominates  
- **Color:** Silver > Red > Black  
- **Transmission:** ~50 / 50  
- **Peak Year:** 2014  
- ![X1 Details](Screenshots/X1%20Details.png)

---

## 🔍 Insights & Key Takeaways

- **Regional strengths vary by model:** E.g. Asia leads for many, but Africa leads for Series 5, North America for Series 7.  
- **Fuel Trends:** Hybrid is consistently top, but electric is dominant in X1. Diesel only strong for i3.  
- **Transmission parity:** Nearly all models have a 50/50 split between manual and automatic — interesting consistency.  
- **Color preferences:** Silver, Black, White repeatedly dominate, but standout colors like Red appear for sport models.  
- **Time peaks differ by model:** E.g., 2016 was big for Series 3 & 5, but 2022 for M3.  
- **Revenue vs hype models:** High sales do not always correspond to highest revenue per unit — model mix matters.  
- **Opportunity zones:** Models where certain regions are underperforming could be targets for marketing / expansion.

---

## 🤝 Contact & Collaboration

I’m always **open to work** and **collaborations** on data analytics, BI, or dashboard projects.  
If you like these kinds of reports or want to work together, **let’s connect!**

- LinkedIn: [linkedin.com/in/divya-makwana-2929b4378](https://www.linkedin.com/in/divya-makwana-2929b4378/)  
- GitHub: [divyamehulmakwana-bit](https://github.com/divyamehulmakwana-bit)

---

Thank you for checking out this project! 🚀  
Feel free to explore, reuse visuals, and suggest improvements or collaboration ideas.  

