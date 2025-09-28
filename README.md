# SQL Data Analysis: Medical Appointment No-Show Prediction

## 🚀 Project Overview (Task 4)

This project completes a data analysis task focused on utilizing advanced SQL queries to extract insights from a structured dataset. The objective was to practice using core SQL components—such as aggregation, complex filtering, subqueries, and views—to prepare data for analytical reporting.

The dataset used is the **Kaggle Medical Appointment No-Show Dataset**, which records information about over 100,000 medical appointments in Brazil.

### 🎯 Objective

The primary goal was to perform various analytical operations to identify factors that correlate with patients missing their scheduled appointments (`no_show` = 'Yes').

---

## 🛠️ Technology Used

* **Database:** SQLite
* **Tool:** DB Browser for SQLite
* **Dataset:** Cleaned Medical Appointments Dataset (Kaggle)

---

## 📊 Analysis & Queries Performed

The analysis directly addresses all required hints (a-f) from the task specification. All executable queries are found in the `data_analysis_queries.sql` file.

| Task Hint | Description | Key SQL Feature |
| :--- | :--- | :--- |
| **a** | Find elderly patients (age >= 60) who missed their appointment. | `SELECT`, `WHERE`, `ORDER BY` |
| **d** | Calculate the No-Show Rate and total appointments for the top 10 most active neighborhoods. | `COUNT`, `SUM`, `GROUP BY`, `LIMIT` |
| **c** | Find the average age of no-show patients, then list all patients older than that average. | **Subquery** (`SELECT AVG(age)`) |
| **e** | Create a view to analyze the no-show rate based on pre-existing conditions (Hypertension & Diabetes). | `CREATE VIEW` |
| **f** | Improve query performance for filtering by no-show status. | `CREATE INDEX` |
| **b** | *Demonstrate JOINS* | Included a commented example of a typical `INNER JOIN` structure, as the single-file dataset did not require a live join. |

---

## 📂 Deliverables

1.  **`data_analysis_queries.sql`:** The master file containing all final, executed SQL commands.
2.  **`screenshots/`:** A folder containing output images verifying the results of each major query.
