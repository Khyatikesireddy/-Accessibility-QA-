# 🔄 ETL Testing – Sample Test Cases

**Test Case 1 – Source to Target Data Validation**  
- **Scenario**: Verify customer data is loaded correctly from source (SQL DB) into staging.  
- **SQL Query (Source)**:  
  ```sql
  SELECT COUNT(*) FROM Customers WHERE Country = 'US';
SELECT COUNT(*) FROM STG_Customers WHERE Country = 'US';
