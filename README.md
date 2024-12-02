# Rohlík Order Analytics Project

This project focuses on analyzing personal order data retrieved from the Rohlík.cz API. The primary goal is to demonstrate data extraction, transformation, and visualization processes using Python, SQL, and Power BI.

---

## Features

1. **Data Extraction**:
   - Connects to the Rohlík.cz API using cookies for authentication.
   - Retrieves detailed data about orders and their items.

2. **Data Transformation**:
   - Creates three structured tables:
     - `dim_order`: Stores order-specific details (e.g., date, total amount, delivery times).
     - `dim_product`: Contains unique product information (e.g., product name, price).
     - `fact_order_product`: Links orders with products and includes metrics like quantity and total price.

3. **Data Storage**:
   - Saves the structured data as CSV files for further analysis.

4. **Future Extensions**:
   - Automate data extraction for new orders.
   - Implement data cleaning and unit standardization in a separate script (e.g., standardizing unit sizes to kilograms/liters).
   - Enhance visualizations to include trends, distributions, and other insights.

5. **Analysis**:
   Using Power BI or Python, you can explore:
   - Total spending over time.
   - Most frequently purchased items.
   - Average delivery times.
   - Additional insights as needed.
