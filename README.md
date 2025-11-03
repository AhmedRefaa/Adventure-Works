# 🧭 AdventureWorks Sales & Operations Dashboard

An interactive **Power BI** dashboard analyzing sales, product, and operational data from the **AdventureWorks** sample database.

---

## 📘 Project Overview

This project provides a comprehensive **business intelligence solution** for the fictional company **AdventureWorks Cycles**.  
Using a Power BI report (`Adventure Works.pbix`), this dashboard aggregates and visualizes **key performance indicators (KPIs)** related to:

- Sales performance  
- Customer demographics  
- Product inventory  
- Reseller activity  

The goal is to deliver **actionable insights** to business stakeholders, enabling them to make **data-driven decisions** about sales strategies, marketing campaigns, and inventory management.

---

## 🗄️ Data Source

This dashboard uses the standard **AdventureWorks** sample database provided by **Microsoft**, a robust transactional (OLTP) database simulating a real-world bicycle manufacturer and retailer.

**Main tables include:**
- **Sales:** `SalesOrderHeader`, `SalesOrderDetail`
- **Production:** `Product`, `ProductCategory`, `ProductSubcategory`
- **Purchasing:** `PurchaseOrderHeader`, `PurchaseOrderDetail`
- **Person/Customer:** `Person`, `Customer`, `Store`
- **Geography:** `Address`, `CountryRegion`

---

## 🧰 Tools & Technologies Used

### 🟨 Microsoft Power BI Desktop
- **Use:** Primary tool for building the report.  
- **Functions:**
  - **Data Ingestion:** Connecting to the AdventureWorks database (SQL Server)
  - **Data Modeling:** Creating relationships and hierarchies between tables
  - **Data Visualization:** Designing charts, maps, and KPIs
  - **DAX (Data Analysis Expressions):** Creating dynamic calculations and time intelligence metrics

### 🟩 Power Query (M Language)
- **Use:** For ETL (Extract, Transform, Load) processes inside Power BI  
- **Functions:** Cleaning, shaping, and transforming raw data before loading into the model

### 🟦 DAX (Data Analysis Expressions)
- **Use:** Writing calculated columns and measures  
- **Functions:** 
  - Time intelligence (YTD, MTD, YoY growth)  
  - Sales performance metrics  
  - Filtering and dynamic calculations

---

## 📁 Project File Structure

