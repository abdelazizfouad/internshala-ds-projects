# 📊 The Bike Haven - Sales Dashboard (Tableau Project)

## 🧠 Project Motive
The aim of this project is to transform static sales reports into an interactive, insightful, and visually appealing Tableau dashboard for **The Bike Haven**, a bike shop based in San Francisco. This dashboard enables better decision-making by tracking product sales, customer insights, budget comparison, and regional performance.

---

## 🏪 Background
**The Bike Haven** was founded by John, a passionate cyclist turned entrepreneur. With years of experience in cycling and a dedication to customer satisfaction, his shop gradually gained popularity across San Francisco and beyond.

As the business grew, Chris—the newly appointed Sales Manager—realized the need to upgrade the company’s reporting system. The existing static reports lacked interactivity and failed to deliver deep sales insights. Chris decided to invest in business intelligence and hired a BI Analyst (me!) to design a modern Tableau dashboard that would serve as a powerful sales analysis tool.

---

## 📍 Problem Scenario
- Static reports lacked flexibility and insight.
- Difficult to analyze product performance, customer segmentation, and regional sales.
- No visual comparison of budgeted vs. actual sales figures.
- Sales team had no interactive filters to view data tailored to specific needs.

---

## ✅ Solution
### Objective:
To build an **interactive Tableau dashboard** using the company's sales data from PostgreSQL and budget data from a spreadsheet.

---

## 🛠️ Steps Taken

### 1. **Database Restoration & Exploration**
- Restored provided `.tar` file into PostgreSQL using pgAdmin.
- Explored 7 interconnected tables: `customer`, `sales`, `date`, `product`, `category`, `subcategory`, `geography`.

### 2. **Data Preprocessing**
- Performed SQL joins to merge:
  - Product hierarchy (`product + category + subcategory`)
  - Customer & region (`customer + geography`)
  - Combined with sales and date tables.
- Removed redundant columns and normalized data.
- Imported and merged budget data from `budgets.csv` for 2023 comparison.

### 3. **Exporting Data**
- Exported cleaned and joined data into CSVs for Tableau.

### 4. **Dashboard Creation in Tableau**
- Designed a user-friendly A4 portrait dashboard including:
  - 📌 Top 10 Products by Sales
  - 💼 Top 10 Customers
  - 📅 Monthly Sales vs. Budget Comparison
  - 🌍 Regional/City Sales Analysis
  - 🛒 Product Categories vs. Sales

- Integrated filters for:
  - Product
  - Customer
  - Region/City
  - Date Range


---

## 🖥️ Tools Used
- **PostgreSQL + pgAdmin** – Data extraction and preprocessing
- **SQL** – Complex joins and filtering
- **Tableau Desktop** – Dashboard design and storytelling
