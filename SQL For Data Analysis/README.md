# SQL for Data Analysis

Welcome to the SQL for Data Analysis project folder. This repository contains the datasets, database backups, and structured query workflows used to extract actionable insights from business data.

## 📁 Repository Structure

*   **`AdventureWorksDW2022.zip`**: A compressed backup (`.bak`) of the Microsoft AdventureWorks Data Warehouse (2022) database. This contains simulated data for a manufacturing company, covering sales, product management, and customer tracking.
*   **`SQL_for_Data_Analysts.ipynb`**: A Google Colab / Jupyter Notebook detailing the data exploration, aggregation, and analytical queries executed against the dataset.

---

## 🚀 Projects & Analysis Covered

This project focuses on resolving core business problems using advanced SQL functionalities:
1. **Sales Performance Analysis**: Identifying top-selling products, seasonal revenue trends, and regional performance.
2. **Customer Segmentation**: Analyzing buying patterns, demographics, and customer lifetime value (CLV).
3. **Inventory Management**: Evaluating stock turnover rates and supply chain bottlenecks.

---

## 🛠️ Tools & Technologies Used
*   **Database Engine:** Microsoft SQL Server (MSSQL)
*   **Language:** T-SQL (Transact-SQL)

---

## 📖 How to Get Started

### 1. Restore the Database
To run the queries locally or inside your notebook, you need to restore the data warehouse:
1. Download and extract `AdventureWorksDW2022.zip` to get the `.bak` file.
2. Open **SQL Server Management Studio (SSMS)**.
3. Right-click **Databases** -> Select **Restore Database...**
4. Choose **Device**, locate the extracted `.bak` file, and complete the restoration wizard.

### 2. Run the Analysis Notebook
Open the `SQL_for_Data_Analysts.ipynb` notebook in Jupyter or Google Colab to follow the step-by-step query analysis and data visualizations.
