# Database SQL & Query Optimization Project

📘 Group academic project developed as part of the **Database SQL and Query Optimization** course  
within the *Data-Driven Specialist* program.

📄 **Project documentation:**  
👉 View optimization report (PDF)

---

## 📌 Project Overview

This project focuses on the design of a **relational database** and the analysis and optimization  
of SQL queries using a real-world scenario: **waste management in gated communities**.

The main objective was not only to obtain correct results, but to understand **how query performance
can be improved** through proper data modeling, indexing strategies, and execution plan analysis.

---

## 🧱 Database Model

The database was designed using a normalized relational structure, including entities such as:
- Collection locations
- Waste types and classifications
- Collection events and quantities
- Disposal and recycling processes

📊 The full Entity-Relationship model is included in the documentation folder.

---

## 🔍 Analytical Questions

The SQL queries were designed to answer key operational questions:

- Which type of waste is generated most frequently at each location?
- Which days of the week concentrate the highest collection volume?
- Which locations show higher efficiency in separating recyclable waste?

These questions simulate real decision-making needs in operational and environmental management.

---

## ⚙️ Query Optimization

Query performance was analyzed using `EXPLAIN` statements to identify:
- Full table scans
- Temporary tables
- Inefficient joins

Based on this analysis, **indexes (including composite indexes)** were created to improve execution
time and efficiency.

📄 A detailed before-and-after optimization analysis is available in the project report.

---

## 💡 Key Insights

- Waste generation patterns vary significantly by location.
- Collection volume is concentrated on specific days, suggesting scheduling optimization.
- Some locations achieve higher recycling efficiency, serving as benchmarks for best practices.

---

## 🧠 What I Learned

This project helped me strengthen my understanding of:

- Relational database design for analytics
- Writing efficient SQL queries
- Reading and interpreting execution plans
- Applying indexing strategies based on query behavior
- Thinking beyond results and focusing on performance and scalability

More importantly, it reinforced the idea that **good data analysis starts with well-structured and optimized data**.

---

## 🛠️ Tools & Skills

- MySQL
- SQL (JOINs, GROUP BY, subqueries, window functions)
- Query optimization with EXPLAIN
- Indexing strategies
- Relational data modeling
