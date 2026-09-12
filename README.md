# 📊 Agents Performance Dashboard — Power BI

An interactive **Power BI dashboard** designed to analyze and monitor **sales agent performance**, monthly sales trends, performance changes, discounts, and employee-level rankings.

The dashboard provides a centralized view of sales performance across employees, stores, and sales channels, helping identify high-performing agents, performance improvements, and areas requiring attention.

---

## 🚀 Project Overview

The **Agents Performance Dashboard** transforms sales data into an interactive analytical report using **Microsoft Power BI**.

The dashboard focuses on answering key business questions such as:

* Which sales agents are performing the best?
* What are the current Month-to-Date (MTD) sales?
* How has each agent's performance changed compared with the previous month?
* How many employees have improved their sales performance?
* Which employees generated more than **100K in MTD sales**?
* What is the average MTD sales generated per employee?
* How do sales performance and discounts vary across employees?
* How does performance differ by **store** and **sales channel**?

---

## 🎯 Key Features

### 👥 Agent Performance

The dashboard provides employee-level performance analysis including:

* Agent ID
* Agent Name
* Performance Rank
* MTD Sales
* Month-over-Month (MoM) performance
* MTD percentage change
* Comparison with the previous month

Agents are ranked based on their sales performance, making it easy to identify top and bottom performers.

---

### 💰 Sales KPIs

The dashboard contains several KPI cards providing a quick overview of sales performance:

| KPI                                  | Description                                                                     |
| ------------------------------------ | ------------------------------------------------------------------------------- |
| **Employees with Positive Change %** | Number of employees whose performance improved compared with the previous month |
| **Average MTD Sales**                | Average Month-to-Date sales generated per employee                              |
| **Average MTD % Change**             | Average percentage change in MTD sales                                          |
| **Employees > 100K MTD Sales**       | Number of employees generating more than 100K in MTD sales                      |

These KPIs provide an executive-level snapshot before drilling down into individual agents.

---

## 📈 Visualizations

The report contains multiple visualizations for analyzing employee performance.

### Agent Ranking Table

A detailed table displaying:

* Agent ID
* Agent Name
* Rank
* MTD Sales
* Previous Month comparison
* Percentage change

This allows users to quickly compare individual employees.

### Employee Performance Charts

The dashboard includes charts for:

* **MTD Sales by Employee**
* **Average MTD Sales**
* **MTD Percentage Change**
* **Average Total Discount**

These visualizations help identify performance patterns and outliers.

---

## 🎛️ Interactive Filters

The dashboard supports interactive filtering to allow users to analyze specific segments.

### Store Filter

Users can filter the dashboard based on individual stores.

### Channel Filter

Users can analyze performance across different sales channels.

### Top / Bottom N Analysis

The dashboard includes a **Top/Bottom N** selection that allows users to focus on the highest- or lowest-performing agents.

This makes the report useful for both performance recognition and identifying employees who may require additional support.

---

## 🧮 Data Model & DAX

The project uses a Power BI data model with dedicated dimensions and measures.

Key model components include:

* `DimEmployee`
* `DimStore`
* `DimChannel`
* `Top-Bottom-N`
* `Actuals-vs-PctChange`
* `# Measures`
* `Clustered Employees`

### Important Measures

Some of the key measures used in the dashboard include:

* **MTD Total Sales**
* **Table MTD Sales**
* **Employee Name**
* **Rank**
* **vs Previous Month**
* **vs PM MOM %**
* **Employees Avg MTD Sales**
* **Employees Avg MTD % Change**
* **Employees with Positive Change %**
* **Employees selling more than 100K MTD**
* **TopN / BottomN MTD Sales**
* **TopN / BottomN Avg MTD Sales**
* **TopN / BottomN MTD % Change**
* **TopN / BottomN Avg Total Discount**

DAX is used to calculate dynamic KPIs, rankings, MTD metrics, and month-over-month comparisons.

---

## 🛠️ Tools & Technologies

| Technology             | Purpose                                   |
| ---------------------- | ----------------------------------------- |
| **Microsoft Power BI** | Dashboard development and visualization   |
| **DAX**                | Measures, calculations, KPIs, and ranking |
| **Power Query**        | Data transformation and preparation       |
| **Data Modeling**      | Relationships and analytical structure    |
| **GitHub**             | Project documentation and version control |

---

## 📊 Dashboard Insights

The dashboard can be used by sales managers and business stakeholders to:

* Identify top-performing sales agents
* Detect declining employee performance
* Compare current sales against previous months
* Track MTD sales performance
* Analyze performance across stores
* Compare sales channels
* Monitor discount patterns
* Identify agents exceeding sales targets
* Evaluate overall sales-team performance

---

## 🔍 Business Use Cases

### Sales Management

Managers can use the dashboard to monitor employee performance and quickly identify agents who are exceeding or falling behind expectations.

### Performance Evaluation

The ranking and MoM comparison features provide a data-driven approach to evaluating sales employees.

### Store Analysis

Store-level filtering allows management to compare employee performance across different locations.

### Channel Analysis

Channel filtering helps understand how sales performance changes across different sales channels.

### Target Monitoring

The **100K MTD Sales** KPI provides a quick way to identify employees reaching a significant sales threshold.

---

## 📁 Project Structure

```text
Agents-PowerBI/
│
├── Agents.pbix
├── README.md
└── assets/
    └── dashboard-preview.png
```

> Add a screenshot of the dashboard inside the `assets` folder and rename it to `dashboard-preview.png` if you want it displayed on GitHub.

---

## ▶️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Agents-PowerBI.git
```

### 2. Open the Power BI File

Open:

```text
Agents.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Interact with the Dashboard

Use the available filters to analyze:

* Stores
* Sales Channels
* Top/Bottom N employees

Select different employees or segments to dynamically update the dashboard visuals and KPIs.

---

## 📌 Key Analytical Metrics

The dashboard emphasizes several important sales-performance metrics:

**MTD Sales**

Measures sales generated during the current month-to-date period.

**MoM Change**

Compares current performance with the previous month.

**Performance Rank**

Ranks employees based on their sales performance.

**Positive Change**

Identifies employees whose performance has improved compared with the previous month.

**Average MTD Sales**

Calculates the average MTD sales contribution per employee.

**Total Discount**

Helps analyze discounting behavior alongside employee sales performance.

---

## 💡 Project Highlights

* 📊 Interactive Power BI dashboard
* 👥 Employee-level sales analysis
* 🏆 Dynam
