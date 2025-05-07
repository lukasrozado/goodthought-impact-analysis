
# GoodThought Impact Analysis

This project contains a structured SQL-based analysis of the GoodThought NGO initiatives,
focusing on donation value and regional impact. The objective is to derive key insights from
donation and assignment data using SQL queries.

## 📊 Objectives

- Identify the top five assignments by total donation value, grouped by donor type.
- Determine the assignment with the highest impact score in each region that received donations.

## 🛠️ Technologies Used

- SQL (for querying datasets)
- Python (for data manipulation and notebook integration)
- Jupyter Notebook / SQL Workbench (for execution environment)

## 📁 Outputs

### 1. `highest_donation_assignments`
Top five assignments based on total donation amount per donor type, showing:
- Assignment Name
- Region
- Rounded Total Donation Amount (to two decimal places)
- Donor Type

### 2. `top_regional_impact_assignments`
Highest-impact assignment per region with at least one donation, showing:
- Assignment Name
- Region
- Impact Score
- Total Number of Donations

## 🚀 Getting Started

To reproduce the analysis:
1. Load the SQL database or dataset containing donation, assignment, and region information.
2. Run the SQL queries included in the project notebook/script.
3. Validate outputs match the required column names and formats.

## 📝 Author

**Lukas Rozado**  
GitHub: [@lukasrozado](https://github.com/lukasrozado)

---

> This project is part of a data analysis portfolio highlighting SQL querying skills with real-world inspired NGO data.
