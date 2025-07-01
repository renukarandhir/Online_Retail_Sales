# Tata Data Visualization Job Simulation

## Project Origin

This project is part of the **Tata Data Visualization Job Simulation** offered through Forage. The simulation provides real-world experience in solving business challenges using data analysis and visualization techniques—simulating the role of a data consultant.

The program consists of four tasks, each aligned with business decision-making and communication using data insights.

---

## Task 1: Drafting Strategic Business Questions

### Background

In Task 1, I acted as a data consultant for an online retail company. The company is performing well and considering expansion. The leadership team—specifically the **CEO** and **CMO**—requires insights into key revenue drivers, customer behavior, and growth opportunities.

- **CEO Focus**: Operational performance, revenue trends, regional analysis.
- **CMO Focus**: Customer loyalty, purchase patterns, and marketing strategies.

### Objective

- Reviewed the provided retail dataset.
- Drafted four strategic questions each for the CEO and CMO.
- Aligned questions with business goals to guide analysis in later tasks.

### Questions for the CEO

1. Which region is generating the highest revenue, and which is generating the lowest?
2. What is the monthly trend of revenue? Which months show spikes or drops?
3. Which months generated the most revenue? Is there seasonality?
4. Who are the top customers and how much do they contribute to total revenue?

### Questions for the CMO

1. What percentage of customers are repeat buyers? Are they buying the same products?
2. How long do repeat customers take to reorder?
3. What revenue is generated from customers who have ordered more than once?
4. Who are the most frequent repeat customers, and what is their revenue contribution?

---

## Task 2: Selecting the Right Visuals for Business Scenarios

### Objective

To choose the most effective visualizations to represent business scenarios and make insights clear to senior leadership.

### Approach

- Evaluated five scenarios based on CEO and CMO needs.
- Selected visuals (e.g., line chart, bar chart, map) aligned with best practices.
- Ensured visuals clearly communicated trends, rankings, and comparisons.

### Key Learning

Understanding business context is essential for selecting the right chart type. The right visual improves comprehension and supports better decisions.

---

## Task 3: Creating Visualizations Based on Business Questions

### Objective

To create and present visuals in Power BI (or Tableau) that address four business questions using cleaned and transformed data.

### Data Preparation

- Removed rows where `Quantity < 1` (returns)
- Excluded records with `Unit Price < £0` (incorrect pricing)
- Ensured only valid transactional data was used for accurate visualizations

### Visualizations Created

**Question 1 – CEO: Monthly Revenue Trend (2011)**  
- Visual: Line Chart  
- Purpose: Identify seasonal trends and support future forecasting.

**Question 2 – CMO: Top 10 Revenue-Generating Countries (Excl. UK)**  
- Visual: Bar Chart with revenue and quantity  
- Purpose: Understand regional performance excluding dominant UK data.

**Question 3 – CMO: Top 10 Customers by Revenue**  
- Visual: Sorted descending bar chart  
- Purpose: Prioritize high-value customers for retention strategies.

**Question 4 – CEO: Product Demand by Country (Excl. UK)**  
- Visual: Map or matrix-style visual  
- Purpose: Identify regions with high demand for expansion planning.

### Tools Used

- **Power BI Desktop** (.pbix format)

---

## Task 4: Presenting Insights to Business Leaders

### Objective

To deliver a clear, 5-minute video presentation to the CEO and CMO covering data cleaning, visual creation, and key business insights.

### Approach

- Developed a concise script explaining the full analytical journey.
- Highlighted the business context behind each visual.
- Tailored language and findings to CEO and CMO priorities.

### Presentation Coverage

1. **Data Cleanup**  
   Ensured clean, reliable data using transformation rules.

2. **Insights Summary**  
   - Monthly revenue trends helped forecast future sales (CEO)
   - Top countries (excluding UK) highlighted high-potential markets (CMO)
   - Top customers by revenue identified retention targets (CMO)
   - High-demand countries pointed to expansion opportunities (CEO)

3. **Recommendations**  
   - Focus on high-performing, non-UK countries for expansion.  
   - Leverage loyal customers for upselling opportunities.  
   - Align promotions with seasonal revenue spikes.

---

## Dataset Overview

The dataset used in this simulation was titled **Online Retail.xlsx**, representing real-world e-commerce transactions for a UK-based retailer.

### Key Features

- **InvoiceNo**: Unique transaction ID  
- **StockCode**: Product/item code  
- **Description**: Product name  
- **Quantity**: Number of units per transaction  
- **InvoiceDate**: Date and time of transaction  
- **UnitPrice**: Price per unit in GBP  
- **CustomerID**: Unique customer ID  
- **Country**: Customer's country

### Notes

- Covers transactions from **Dec 2010 to Dec 2011**
- Includes **returns** (negative quantities)
- Contains **data entry errors** (e.g., `UnitPrice < 0`) that were cleaned
- **United Kingdom** dominates the data and was excluded in specific visualizations to uncover global insights

This dataset served as the basis for analysis and visualization across all tasks in the project.

---
