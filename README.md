

## 📊 Tableau Workbook (`Book002.twb`) – Detailed Explanation

  * Data source information
  * Sheets, dashboards, filters
  * Calculated fields
  * Parameters and actions
* This file **does not contain raw data**, only **references to the data source**

---

### 2️⃣ Tableau Version & Environment

* Created using **Tableau Desktop (Build 20253.25)**
* This indicates a **modern Tableau version**, supporting:

  * Advanced calculations
  * Dashboard actions
  * Parameters
  * Schema-based data modeling

---

### 3️⃣ Data Source Explanation

* The workbook connects to an **external data source** (such as Excel / CSV / Database)
* Tableau stores:

  * Column names
  * Data types (string, number, date)
  * Roles (Dimension / Measure)
* Actual data remains outside the `.twb` file

📌 This approach keeps the workbook **lightweight** and **easy to share**

---

### 4️⃣ Fields & Data Structure

Inside the workbook:

* **Dimensions**

  * Categorical data (e.g., Category, Region, Product)
  * Used for grouping and filtering
* **Measures**

  * Numerical data (e.g., Sales, Profit, Quantity)
  * Used for calculations and charts

Tableau internally maps:

* Field aliases
* Default aggregations (SUM, AVG, COUNT)
* Formatting rules

---

### 5️⃣ Sheets (Worksheets)

* The workbook contains **multiple worksheets**
* Each worksheet defines:

  * Rows and Columns shelves
  * Marks (Bar, Line, Text, etc.)
  * Filters and sorting rules
* Sheets are built using **drag-and-drop logic**, saved as XML definitions

📌 Each worksheet is an independent analysis view

---

### 6️⃣ Calculated Fields

* Custom calculations are defined inside the workbook
* Examples:

  * Profit Margin = Profit / Sales
  * Conditional logic using IF / ELSE
* These calculations:

  * Are reusable across sheets
  * Improve business-level insights

---

### 7️⃣ Filters & Parameters

* Filters control:

  * Date ranges
  * Categories
  * Regions or values
* Parameters allow:

  * Dynamic user input
  * Interactive dashboards

📌 This makes the dashboard **dynamic and user-driven**

---

### 8️⃣ Dashboard & Actions

* Dashboards combine multiple sheets into **one visual screen**
* The workbook uses **Actions**, such as:

  * Filter Actions (click one chart → update another)
  * Parameter Actions
  * Clear Selection Actions

This improves:

* User interaction
* Drill-down analysis
* Business storytelling

---

### 9️⃣ Formatting & Design

* Formatting includes:

  * Colors
  * Labels
  * Fonts
  * Tooltips
* Tooltips often contain:

  * Calculated values
  * Contextual explanations

📌 Helps non-technical users understand insights easily

---

### 🔟 Business Purpose of This Workbook

This Tableau workbook is designed for:

* **Data analysis**
* **Trend identification**
* **Performance comparison**
* **Decision support**

It converts **raw data into meaningful insights** using:

* Aggregations
* Visual analytics
* Interactive dashboards
