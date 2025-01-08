# <h1>PSM</h1>

<h2>Purpose</h2>
To provide a user-friendly interface for process or equipment technicians and engineers to quickly search and filter production parameter settings from a local MS SQL Server database. This system will enable fast access to machine parameters, settings history, and relevant production data without requiring the user to know SQL queries.

<h2>Project Goal</h2>
This project aims to reduce the time users spend manually querying the database and ensure they can quickly find critical information to troubleshoot issues, ensuring minimal downtime and better decision-making.

<h3> Example Scenario</h3>
Bob is troubleshooting an issue with one of the machines on the production line. By using the search tool, Bob quickly enters a keyword (e.g., 'beam setting') and receives a table of relevant parameters, including the most recent changes and any historical changes, without needing to understand SQL queries or database structures.

<h2>Development Info:</h2>
Database: Relational, stored static on a local level thorugh MS SQL Server. 
Frontend Development:  Plain HTML, CSS, and minimal JavaScript (Fetch API for async requests).
Backend API: Flask + basic Python SQL queries (using pyodbc for MS SQL connection).
