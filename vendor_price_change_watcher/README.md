# Vendor Price Change Watcher

**Goal:** Track vendor cost changes proactively to support pricing governance.

**Problem:**  
Manual monitoring of vendor cost changes is time-consuming and prone to delays, making it difficult to catch discrepancies quickly.

**Solution:**  
A Python-based watcher script that compares current and prior pricing data from PostgreSQL, detects cost deltas, and generates alerts for material cost changes.  
Future versions will integrate directly with Snowflake and email notifications.

**Stack:**  
Python (pandas, psycopg2), PostgreSQL, VS Code  

**Output Example:**  
- `Vendor_Cost_Change_Report_2025-07-01.xlsx`  
- Columns: Vendor ID, Product ID, Old Cost, New Cost, % Change, Status  

**Impact (Planned):**  
- Enable real-time visibility into vendor price movements.  
- Support Data Governance and OpCo pricing initiatives.  

**Next Steps:**  
- Implement Power BI dashboard integration.  
- Deploy watcher as a scheduled task with notification triggers.
