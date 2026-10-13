# 🏗️ SQL Data Warehouse & Analytics Project

Welcome to my **Data Warehouse and Analytics Project**!

This project builds a complete data warehousing and analytics solution in **SQL Server**. It starts with raw CSV files and ends with business-ready insights. I built it as a portfolio project to practise industry-standard data engineering and analytics.

---

## 🏛️ Data Architecture

The warehouse follows the **Medallion Architecture**, with three layers:

| Layer | Purpose | Object Type |
|---|---|---|
| 🥉 **Bronze** | Raw data loaded as-is from the source CSV files | Tables |
| 🥈 **Silver** | Cleaned, standardised, and validated data | Tables |
| 🥇 **Gold** | Business-ready data modelled as a star schema for reporting | Views |

---

## 📋 Project Requirements

### Part 1: Building the Data Warehouse (Data Engineering)

#### 🎯 Objective
Build a modern data warehouse in SQL Server that brings together sales data from different systems, so the business can report on it and make informed decisions.

#### 📌 Specifications
- **Data Sources:** Import data from two source systems (ERP and CRM), provided as CSV files.
- **Data Quality:** Clean and fix data quality issues before analysis.
- **Integration:** Combine both sources into a single, easy-to-use data model built for analytical queries.
- **Scope:** Use the latest dataset only. Historical tracking of data is not required.
- **Documentation:** Document the data model clearly for both business stakeholders and analytics teams.

---

### Part 2: BI, Analytics & Reporting (Data Analytics)

#### 🎯 Objective
Write SQL-based analytics that give detailed insights into:
- **Customer Behaviour**
- **Product Performance**
- **Sales Trends**

These insights give stakeholders the key business metrics they need for strategic decisions.

---

## 🛠️ Tools & Technologies

- **SQL Server Express**: database engine
- **SQL Server Management Studio (SSMS)**: writing and running queries
- **Draw.io**: architecture, data flow, and data model diagrams
- **Git & GitHub**: version control and project hosting

---

## 📁 Repository Structure

```
sql-data-warehouse-project/
├── datasets/          # Raw ERP and CRM CSV files
├── docs/              # Architecture diagrams, data catalog, naming conventions
├── scripts/
│   ├── bronze/        # Scripts to load raw data
│   ├── silver/        # Scripts to clean and transform data
│   └── gold/          # Scripts to create the star schema views
├── tests/             # Data quality checks
└── README.md
```

---

## 🙏 Acknowledgements

This project is based on the SQL Data Warehouse course by [Data With Baraa](https://www.youtube.com/@DataWithBaraa), which is licensed under the MIT License.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share it with proper attribution.

---

## 👋 About Me

Hi there! I'm **Anuraghava Reddy A**. I'm a former Senior Manager with ~7 years of experience in civil engineering and construction management, where I led resource planning and operations across multiple projects. I'm now moving into **data analytics and data engineering**, building hands-on projects that turn raw data into clear business decisions.

- 💼 LinkedIn: www.linkedin.com/in/anuraghava-reddy-anugula-023605159
- 🐙 GitHub: anuraghava-reddy
- 📧 Email: aanuraghavareddy123@gmail.com

⭐ If you found this project useful, feel free to star the repo!
