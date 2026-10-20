[← Home](https://github.com/Kleber720) · [Development](https://github.com/Kleber720/Kleber720/blob/main/DEVELOPMENT.md) · [Data](https://github.com/Kleber720/Kleber720/blob/main/DATA.md)

<div align="center">

![Kleber Amaro — Data Analytics and Data Engineering](./assets/dados-header.svg)

# Data Analytics & Data Engineering

**SQL to answer business questions. Data modeling to support analysis.**

**Seeking opportunities in Data Analytics and Data Engineering.**

[Data Analytics](#data-analytics) · [Data Engineering](#data-engineering-foundations) · [Projects](#featured-projects) · [Tech stack](#tech-stack-and-evidence)

</div>

## About me

I'm **Kleber Amaro**, a graduate of the **technical IT program at Senac Santana** and a **Game Design student at Anhembi Morumbi**. I'm pursuing a career in data, with projects in **SQL, MySQL, relational modeling, and performance metrics**, alongside practice with **Python and JSON persistence**.

My portfolio connects two stages of working with data: **organizing information into consistent structures** and **writing queries that help interpret results**. My projects apply these foundations to sports analytics and corporate equipment management.

## Data Analytics

**Turn questions into queries and verifiable metrics.**

- **SQL exploration:** join records, select relevant information, filter data, and order results.
- **Performance metrics:** calculate goal contributions, goal difference, and the percentage of available points earned.
- **Operational reporting:** query equipment availability and summarize quantities by department with COUNT, SUM, and GROUP BY.
- **Reusable queries:** organize calculation rules into views, with formulas available for review.

**Start with:** [Corinthians Data Analytics](https://github.com/Kleber720/bancodeDadosCOR) — from a performance question to a SQL query.

## Data Engineering foundations

**Structure the data that supports queries and applications.**

- **Relational modeling:** separate entities and define relationships between players and statistics, or departments, employees, and equipment.
- **Data integrity:** apply primary keys, foreign keys, and NOT NULL and UNIQUE constraints where appropriate.
- **Data-loading scripts:** separate schema creation, record insertion, and view definitions.
- **Database operations:** practice stored procedures and transactions with COMMIT and ROLLBACK.
- **Persistence and integration:** work with JSON files in Python and API-to-MySQL integration in study projects.

**Start with:** [Corporate Notebook Management](https://github.com/Kleber720/ProjetoBancodeDados) — modeling, constraints, and transactional operations in a collaborative project.

## Featured projects

### 01 · [Corinthians Data Analytics](https://github.com/Kleber720/bancodeDadosCOR)

**Data Analytics · SQL · MySQL · Performance metrics**

**Context:** organize player and club statistics to query individual and team performance.

**Questions addressed**

- Which players have the most goals and assists?
- How many direct goal contributions does each player have?
- What is the club's goal difference and percentage of available points earned?

**Implementation**

The model links players to their statistics and stores club totals in a separate table. The player view uses a JOIN and sorts by goals and assists; the club view centralizes performance calculations.

Metrics use explicit rules: **goal contributions = goals + assists**, **goal difference = goals scored − goals conceded**, and **points percentage = points earned ÷ available points × 100**.

**Delivered:** a relational database, data-loading scripts, and two analytical views for querying metrics directly in SQL. The separation into `schema.sql`, `seed.sql`, and `view.sql` documents the database preparation steps.

[Explore the case study](https://github.com/Kleber720/bancodeDadosCOR) · [Review queries and formulas](https://github.com/Kleber720/bancodeDadosCOR/blob/main/sccp-analytics-db/scripts/view.sql) · [View the data model](https://github.com/Kleber720/bancodeDadosCOR/blob/main/sccp-analytics-db/scripts/schema.sql) · [View data loading](https://github.com/Kleber720/bancodeDadosCOR/blob/main/sccp-analytics-db/scripts/seed.sql)

### 02 · [Corporate Notebook Management](https://github.com/Kleber720/ProjetoBancodeDados)

**Data Engineering foundations · Relational modeling · SQL / MySQL**

**Context:** structure equipment, employee, and department records to track notebook assignments and availability.

**Questions addressed**

- Who is responsible for each device, and which department do they belong to?
- Which notebooks are available?
- How are employee-assigned devices distributed across departments?

**Implementation**

The database connects three entities and enforces uniqueness for identifiers such as asset tags and serial numbers. Foreign keys express relationships between records; views combine data and aggregate quantities for operational queries.

The project also includes stored procedures for registration and lookup, along with assignment and return operations using transactions and ROLLBACK handlers for SQL exceptions.

**Delivered:** modeling, operation, and query scripts for an asset-management scenario. The project demonstrates relational database foundations relevant to data preparation and organization.

**Teamwork:** developed at Senac Santana by **César de Oliveira Zanelatto, Kleber Amaro da Silva, and Rafael Sper Moralli**. This repository is a fork of [CesarZanelatto/ProjetoBancodeDados](https://github.com/CesarZanelatto/ProjetoBancodeDados).

[Explore the case study](https://github.com/Kleber720/ProjetoBancodeDados) · [Review tables and constraints](https://github.com/Kleber720/ProjetoBancodeDados/blob/main/ProjetoDB/Tabelas.sql) · [View SQL reports](https://github.com/Kleber720/ProjetoBancodeDados/blob/main/ProjetoDB/Views.sql) · [View transactions](https://github.com/Kleber720/ProjetoBancodeDados/blob/main/ProjetoDB/Transacoes.sql)

## Tech stack and evidence

**SQL and relational databases — applied in the featured projects**

![SQL](https://img.shields.io/badge/SQL-2563EB?style=for-the-badge&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

JOINs · LEFT JOINs · GROUP BY · COUNT / SUM · Views · Keys and constraints · Stored procedures · Transactions

**Python and integration — study practice**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-45556C?style=flat-square&logo=json&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

- [Inventory Management Practice](https://github.com/Kleber720/SistemaLimpeza) — Python, reading and persisting JSON records, and layered data access.
- [Node.js and API studies](https://github.com/Kleber720/estudosNodeTI102) — APIs and MySQL persistence, connecting applications to relational databases.

These two repositories document coursework and programming practice; the case studies above are the main projects for this area.

## Career focus

I'm seeking opportunities involving **SQL queries, performance analysis, reporting, and database organization**, building a career in **Data Analytics or Data Engineering**.

I bring technical IT education, collaborative project experience, and publicly available code for review. Each featured project includes documentation and scripts that explain the data model and query logic.

---

<div align="center">

**From data structures to meaningful analysis.**

[← Home](https://github.com/Kleber720) · [Development](https://github.com/Kleber720/Kleber720/blob/main/DEVELOPMENT.md) · [Data](https://github.com/Kleber720/Kleber720/blob/main/DATA.md)

</div>
