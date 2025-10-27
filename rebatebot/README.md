# RebateBot Automation

**Goal:** Automate rebate data processing and reporting.

**Problem:**  
Monthly rebate tracking required multiple Excel filters, manual exclusions, and formatting, taking hours to complete.

**Solution:**  
A Python script that loads ERP invoice data, filters out SPJ 111362 and cash accounts, removes excluded items, and creates formatted executive summaries.  
The final output includes key metrics such as total extended cost, revenue, and margin summaries per customer or vendor.

**Stack:**  
Python (pandas, openpyxl), Excel, VBA  

**Output Example:**  
- `RebateBot_Processed_Data_June2025.xlsx`  
- Tabs: Raw Data, Cleaned Data, Summary  
- Includes automated pivot tables and color-coded output  

**Impact:**  
- Reduced manual processing time from ~3 hours to under 10 minutes.  
- Increased accuracy and consistency across rebate reports.  

**Next Steps:**  
- Integrate data validation directly from PostgreSQL.  
- Schedule automatic monthly processing using Python and task scheduling.
