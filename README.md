# t-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python


🔧 Technical Features

| Feature                             | Description                                                                       |
| ----------------------------------- | --------------------------------------------------------------------------------- |
| **SQLite Database Integration**     | Uses `sqlite3` to connect to and query a local database (`sales_data.db`).        |
| **Table Creation & Data Insertion** | Automatically creates a `sales` table and inserts mock data (only on first run).  |
| **SQL Query Execution**             | Executes a SQL query to calculate total quantity and revenue per product.         |
| **Pandas DataFrame Usage**          | Loads SQL results into a Pandas DataFrame for easy manipulation and display.      |
| **Text Output**                     | Prints the sales summary (total quantity and revenue) in a readable table format. |
| **Matplotlib Visualization**        | Creates a bar chart to visualize product-wise revenue.                            |
| **Chart Export**                    | Saves the chart as an image file (`sales_chart.png`).                             |
| **Modular and Re-runnable**         | Clean code structure allows safe re-running after commenting out data insertion.  |




📈 Data Processing Features
| Feature                       | Description                                                   |
| ----------------------------- | ------------------------------------------------------------- |
| **Group By Product**          | Summarizes sales data for each unique product.                |
| **Revenue Calculation**       | Computes total revenue using `quantity * price`.              |
| **Rounding for Readability**  | Rounds revenue values to 2 decimal places.                    |
| **Supports Multiple Entries** | Aggregates data even when multiple entries exist per product. |


📊 Visualization Features
| Feature                      | Description                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| **Bar Chart Type**           | Uses a simple vertical bar chart to display revenue by product. |
| **Custom Labels and Titles** | Includes axis labels and chart title for clarity.               |
| **Color Customization**      | Light blue color used for visual appeal.                        |
| **Size Adjustment**          | Sets figure size for better readability.                        |

![task7 1](https://github.com/user-attachments/assets/bd69b4bc-e120-4797-a45e-b621f960e869)
![task7 2](https://github.com/user-attachments/assets/e564dd20-6bb6-4645-8a24-f3ba971f1c51)
![task7 3](https://github.com/user-attachments/assets/034c96a2-7b9c-448b-89e7-2ea115576221)



