# S04-26-Equipo-46-Business-Intelligence
End-to-end data pipeline for workforce analytics.

Problema
Automate the generation of workforce executive reports by connecting GlobalForce's internal data sources with interactive dashboards and exportable reports, reducing preparation time from three days to less than one hour.

Descripción
GlobalForce's enterprise clients require monthly executive reports on the status of their workforce: turnover, costs by region, capacity utilization, and goal achievement. Currently, these reports are manually generated in Excel, a process that takes three days per client.

Expectations
Documented unified data model. Interactive dashboard with executive KPIs: turnover, cost by region, and capacity utilization. PDF report automatically generated from the dashboard. User manual for the team operating the system.

Users
GlobalForce analyst who prepares monthly reports for clients. Client manager who uses the executive report.

Flows
Analyst loads period data from internal sources (assignments, hours, headcount) → the ETL pipeline processes and updates the model → the dashboard refreshes with the new data → analyst reviews KPIs → generates the PDF report with one click → sends it to the client.
