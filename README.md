# SQL-BASICS-ADVANCE-

# SQL Learning Resource Pack

A self-contained collection of three PDFs covering SQL theory, practice, and quick reference — built for anyone learning SQL from scratch, brushing up before an interview, or wanting a fast lookup while writing queries. Together, the documents take you from `SELECT * FROM table` to window functions, recursive CTEs, and database design discussions.

## What's Inside

| File | Type | Pages | Best For |
|------|------|-------|----------|
| `SQL_BASICS_AND_ADVANCE_NOTES.pdf` | Study notes | 101 | Learning SQL concepts step by step, from fundamentals to advanced topics |
| `50_SQL_interview_questions.pdf` | Q&A list | 6 | Interview prep — freshers through 2–5 YOE professionals |
| `SQL_CHEAT_SHEET.pdf` | Quick reference | 8 | Fast lookup of syntax while writing or reviewing queries |

---

### 1. `SQL_BASICS_AND_ADVANCE_NOTES.pdf`

A comprehensive, example-driven walkthrough of SQL split into two halves:

**SQL Basics**
- What SQL and RDBMS are, database tables, and basic SQL statement structure
- `SELECT`, `SELECT DISTINCT`, `WHERE`, `AND`/`OR`, `ORDER BY`
- `INSERT INTO`, `UPDATE`, `DELETE`

**SQL Advanced**
- `TOP` / `LIMIT`, wildcards, `LIKE`, `IN`, `BETWEEN`, aliases
- All join types: `INNER`, `LEFT`, `RIGHT`, `FULL`, with worked examples
- `UNION` and `UNION ALL`, `SELECT INTO`
- DDL: `CREATE DATABASE`, `CREATE TABLE`, `ALTER TABLE`, `DROP`, `TRUNCATE`
- Constraints: `NOT NULL`, `UNIQUE`, `PRIMARY KEY`, `FOREIGN KEY`, `CHECK`, `DEFAULT` (creation, alteration, and removal for each)
- Indexes, auto-increment fields, views
- Dates: data types, date/time functions across MySQL, SQL Server, and Oracle dialects (`NOW()`, `CURDATE()`, `DATEDIFF()`, `EXTRACT()`, `FORMAT()`, and more)
- `NULL` handling, data types across Access/MySQL/SQL Server
- SQL functions: aggregate functions (`AVG`, `COUNT`, `SUM`, `MIN`, `MAX`) and scalar functions (`UCASE`, `LCASE`, `MID`, `LEN`, `ROUND`, `FORMAT`)
- `GROUP BY`, including grouping on multiple columns

Every concept is paired with sample tables, SQL syntax, and the resulting output, making it easy to follow along even without a database set up.

### 2. `50_SQL_interview_questions.pdf`

A curated interview question bank organized by difficulty and topic:

- **SQL Basics (Freshers)** — commands, keys, constraints, data types, aggregate functions
- **Queries & Filtering** — `WHERE` vs `HAVING`, duplicates, `DISTINCT`, `IN` vs `EXISTS`, top-N queries
- **Joins** — all join types, self joins, joins vs unions, finding unmatched records
- **Subqueries & CTEs** — correlated vs non-correlated subqueries, CTEs, recursive CTEs
- **Window Functions** — `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `PARTITION BY`
- **Intermediate to Advanced** — indexing, normalization (1NF–BCNF), denormalization, views vs materialized views, stored procedures, triggers, ACID properties
- **Frequently Asked Coding Questions** — nth highest salary, duplicate detection/removal, department-wise rankings, running totals
- **Experienced Professional (2–5 yrs) Scenario Questions** — query optimization, deadlocks, execution plans, OLTP vs OLAP, partitioning, sharding, isolation levels, database design

Useful as a checklist for self-assessment or as a structured guide for mock interviews. Covers roles like Data Analyst, SQL Developer, Business Analyst, Data Engineer, and BI Developer.

### 3. `SQL_CHEAT_SHEET.pdf`

A condensed, visual reference (originally published by LearnSQL.com / Vertabelo) spanning four mini cheat sheets:

- **SQL Basics** — single/multi-table queries, aliases, filtering operators, `LIKE` patterns, aggregation, `GROUP BY`/`HAVING`, subqueries (single-value, multi-value, correlated), set operations (`UNION`, `INTERSECT`, `EXCEPT`)
- **Window Functions** — `PARTITION BY`, window frames (`ROWS`/`RANGE`/`GROUPS`), the full list of ranking, analytic, and distribution functions (`RANK()`, `LEAD()`, `LAG()`, `NTILE()`, `FIRST_VALUE()`, `PERCENT_RANK()`, etc.) with visual before/after tables and the logical order of SQL operations
- **JOINs** — every join type with diagrammed example tables, self joins, non-equi joins, multiple joins, and joins with compound conditions
- **Standard SQL Functions** — text functions (concatenation, `LIKE`, `SUBSTRING`, `REPLACE`), numeric functions (`CAST`, `ROUND`, `CEIL`, `FLOOR`, `MOD`), `NULL` handling (`COALESCE`, `NULLIF`), `CASE WHEN`, and a full date/time/interval/time-zone reference

Designed to be skimmed quickly rather than read end to end — ideal to keep open in a second tab while working.

---

## Suggested Usage

1. Start with the **notes PDF** if you're new to SQL or want a structured refresher.
2. Use the **cheat sheet** as a side reference while practicing or solving problems.
3. Work through the **interview questions** once you're comfortable with the basics, to test recall and prepare for real interview scenarios.

## Attribution

The `SQL_CHEAT_SHEET.pdf` is based on cheat sheets originally published by [LearnSQL.com](https://learnsql.com), owned by Vertabelo SA, distributed under CC BY-NC-ND. The other two documents are compiled study notes and interview question lists.

