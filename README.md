# PowerBi_project
Bookstore Data Analysis and Visualization in Power BI.
Project details: This project involves the analysis of bookstore sales data. After applied ETL process, normalized the data and created a Power BI dashboard for visualizing .
Data Normalization: Normalized the data to 3rd Normal Form (3NF) by breaking down the larger table into smaller ones and ensure the data dependencies are logical.
I separated the books and authors table into distinct tables to avoid data redundancy.  Order data was linked to both the customer and books table through foreign keys. Also I break the customer table into customer location and age category and both linked through foreign keys to the customer table. 
Visualization and Dashboard :
      After building the data model, the following visualizations was created to give insights into bookstore data.
Filters :   
Country Slicer : Slicer at the top allows user to filter the data by country. User can select multiple countries from the list, to analyze sales performance or book data by specific region.
Categories Slicer : This Slicer allows the user to filter the data by categories of books.
Years Slicer : This Slicer allows user to filter the data by years to analyse the sales, orders details etc.
Visuals :  
Bar and Line chart : The x-axis shows different book categories.
Total Amount: Represented by the bars, each category has total amount in sales.
Stock Quantity: The line plot superimposed on the bars represents the quantity of books in stock (on the right y-axis).
Pie Chart : It shows the sum of total amount and count of title by book categories . Each segment of the pie chart represents a book category
KPI Card :  
Total Sales: Displays the sum of all sales across the filtered data, showing a total of 62.30K.
Average Customer: Shows the average sales amount per customer, displayed as 935.08.
Order Years : It shows the total orders in a year across the filtered , it displayed a total  11k orders.
Line Chart : It shows the sum of price and First city by book categories. 
Treemap visualizes :  The total sales amount broken down by book categories and the first country where those sales occurred.
The size of the blocks represents the magnitude of the total amount for each category.






