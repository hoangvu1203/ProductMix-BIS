# ProductMix-BIS

A Business Intelligence system for **CompanyX** built using the **AdventureWorks** dataset. This project integrates ETL pipelines (SSIS), customer segmentation (Python clustering), and interactive dashboards (Power BI) to optimize product mix decisions and understand customer purchasing behavior.

---

## 📊 Project Overview

The goal of this project is to deliver a complete Business Intelligence system for product mix analysis. It includes:

1. **Data Extraction & Loading**  
   Built with SQL Server Integration Services (SSIS) to extract and load data from the AdventureWorks database into a structured data warehouse.

2. **Clustering & Analysis**  
   Python is used to perform customer segmentation based on purchasing behavior using K-Means clustering.

3. **Visualization**  
   Power BI dashboards provide actionable insights for business stakeholders on sales trends, product performance, and segment behavior.

---

## 🛠 Technologies Used

- **SQL Server Integration Services (SSIS)** – ETL workflows
- **SQL Server / T-SQL** – Data storage and queries
- **Python (pandas, scikit-learn)** – Clustering analysis
- **Power BI** – Dashboards and data visualization
- **AdventureWorks** – Sample dataset simulating sales and customer data

---

## Prerequisites

- **Visual Studio 2022** with **SQL Server Data Tools (SSDT)** for SSIS.  
- **SQL Server** (2019+) with SSIS Catalog (SSISDB).  
- **Python 3.8+** with packages listed in `python/requirements.txt`.  
- **Power BI Desktop** to open and modify `power_bi/dashboard.pbix`.

---
## 📄 Project Objectives
This **BI system** implements the full lifecycle of **data intelligence**:

- **Data source** understanding & **business requirement** gathering

- **Data warehouse** design and implementation

- **ETL** (Extract–Transform–Load) pipeline development

- **Customer segmentation** using clustering algorithms

- Interactive **dashboard** for insight delivery

- **Real-time** or near-real-time data refresh capability