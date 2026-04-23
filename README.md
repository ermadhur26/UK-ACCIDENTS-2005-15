🚗 Road Accident Data Analysis (SQL)

📌 Project Overview

This project focuses on analyzing large-scale road accident data across three core dimensions: Accidents, Vehicles, and Casualties.
The primary goal was to uncover temporal, environmental, and behavioral patterns while ensuring high-performance querying on a large dataset.

Problem Statement: Extracting meaningful insights from multi-million record datasets often leads to connection timeouts and memory limits.

Key Focus: SQL performance tuning, multi-table joins, and advanced analytical window functions.

🛠️ Tech Stack & Optimization

Database: SQL (MySQL/PostgreSQL)

Techniques: Multi-table Joins, Window Functions, Subqueries, CTEs.

Performance Tuning:

Resolved Error 2013: Overcame "Lost Connection" errors by implementing pre-aggregation strategies.

Query Optimization: Applied early filtering (WHERE clauses) to reduce initial data scans before heavy joins.

Indexing: Utilized indexing on Accident_Index and frequently grouped columns to decrease execution time.

📊 Key Analysis & Insights

The project answering several critical business and safety questions:

Temporal Patterns: Identified peak accident months (e.g., higher casualties in October/November) and daily trends.

Severity Analysis: Analyzed the distribution of Fatal vs. Slight injuries; discovered that "Slight" severity accounts for the bulk of casualties (approx. 84%).
Environmental Impact: Evaluated how weather (Dry vs. Rain) and lighting (Daylight vs. Night) correlate with accident frequency.
Vehicle & Driver Profiling: Linked driver age and vehicle type to injury severity, finding that car accidents contribute to nearly 80% of total casualties.
