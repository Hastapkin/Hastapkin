# Hi, I'm Tuan Pham 👋

Final-year **Information Systems** student (Advanced Program, taught entirely in English) based in **Ho Chi Minh City, Vietnam**, graduating on schedule in 2027 and available full time from January 2027.

I like the layer where business processes meet the database: modelling the data, writing the logic that keeps it correct, and turning it into something people can use. I'm looking for an **SAP ABAP fresher / ERP consultant** role, and I'm also open to **junior Data Engineer** and **Data Analyst** roles.

## What I work with

| Area | Tools |
|---|---|
| Languages | SQL (Oracle PL/SQL, T-SQL), Python |
| Databases | Oracle and SQL Server: schema design from ERD, stored procedures, functions, triggers, distributed design with database links |
| Data integration | Oracle Data Integrator (ODI), SSIS, PL/SQL pipelines; exposure to Oracle GoldenGate |
| BI & warehousing | Power BI, Oracle Analytics Server, SSAS (OLAP cubes, star schema) |
| Systems | Linux command line, Oracle Database 19c installation and configuration |
| Analysis & ML | pandas, scikit-learn, mlxtend, XGBoost, PyTorch (coursework) |
| Data apps | Streamlit, NetworkX, Plotly |
| Currently learning | Databricks: Unity Catalog, Delta Lake, Lakeflow pipelines |
| Up next | SAP ABAP and the SAP ecosystem |
| English | TOEIC Listening & Reading 740, Speaking & Writing 300 (July 2026); degree taught in English |

## Experience

**Data Engineering, OSAS Joint Stock Company**, Jun 2025 – Present (joined as an intern, then probation, alongside full-time study)

*Data warehouse for a Vietnamese insurance company (Oracle Database, Oracle Data Integrator)*

Sales and customer analytics domain of an Oracle data warehouse: source systems replicate into an operational data store, and a daily Oracle Data Integrator job loads staging and then the warehouse's dimension and fact tables with watermark-based incremental loads.

- Built loads end to end for around five of the 15 tables in the domain: source views on the operational data store, ODI mappings into staging, and PL/SQL MERGE procedures into dimension and fact tables.
- Wrote test cases that reconcile each loaded table against its source.
- Traced missing data in a target table to a date-window mismatch between the staging extract and the load procedure, using ODI execution history; corrected it and reconciled source and target totals before handing the data to the business analyst.
- Worked from tickets assigned by the team lead: read the requirement, built or fixed the load, tested it and returned the result.

*Database migration for a public-sector client (SQL Server and MongoDB to Oracle Database 19c)*

- Supported post-migration checks, verifying the list of migrated databases and tables in Oracle against the SQL Server and MongoDB sources.
- Installed and configured Oracle Database 19c on Linux.

## Education

**Bachelor of Information Systems, Advanced Program (taught entirely in English)**, University of Information Technology, VNU-HCM, 2022 – 2027

Relevant coursework: Enterprise Resource Planning, Business Process Reengineering, Supply Chain Management, Systems Analysis and Design, Data, Process and Object Modeling, Information Systems Project Management, Distributed Database Systems, Object-Oriented Programming, Data Mining.

## Selected projects

**[DDBMS](https://github.com/Hastapkin/DDBMS)**: a distributed product-management database on Oracle across three sites, with horizontal and vertical fragmentation, PL/SQL procedures, functions and triggers, and cross-site queries. Team project; I led the design and wrote most of the implementation.

**[BI_DSS](https://github.com/Hastapkin/BI_DSS)**: business intelligence on the Superstore dataset: a Power BI dashboard, an SSIS ETL package, and an SSAS cube built on a star schema.

**[Flight-Route-Advisor](https://github.com/Hastapkin/Flight-Route-Advisor)**: route finder and airport hub analysis on the OpenFlights network (7,698 airports, 66,315 routes). A Python pipeline cleans the data and builds the graph; a Streamlit app finds shortest routes and ranks hubs by centrality.

**[gift-shop-ai-advisor](https://github.com/Hastapkin/gift-shop-ai-advisor)**: a gift-shop web app with a Gemini-powered assistant that recommends products from a catalog based on occasion, relationship and budget.

## Get in touch

- LinkedIn: [in/tuan-pham-2681112a1](https://www.linkedin.com/in/tuan-pham-2681112a1)
