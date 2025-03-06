### **SQL Assignment: Inventory Management System**  

#### **Objective:**  
The goal of this assignment is to practice SQL queries related to **data retrieval, filtering, sorting, and aggregation** using a single table (`Products`).  

---

### **Table: `Products`**  

This table contains details of the products in an inventory.  

| Column Name    | Data Type        | Constraints                                       | Description                                |
|---------------|----------------|---------------------------------------------------|--------------------------------------------|
| ProductID     | INT             | PRIMARY KEY, AUTO_INCREMENT                      | Unique identifier for each product        |
| ProductName   | VARCHAR(100)    | NOT NULL                                        | Name of the product                       |
| Category      | VARCHAR(50)     | NOT NULL                                        | Category of the product (e.g., Electronics, Furniture) |
| Price         | DECIMAL(10,2)   | CHECK (Price > 0)                               | Price of the product (must be positive)   |
| StockQuantity | INT             | CHECK (StockQuantity >= 0)                      | Available stock quantity (cannot be negative) |
| LastRestocked | DATE            | DEFAULT CURRENT_DATE                            | Date when the product was last restocked  |

---

### **Assignment Questions:**  

1. Retrieve all details of the products available in the inventory.  
2. List all products that belong to the "Electronics" category.  
3. Display the product name and price of all products with a stock quantity greater than 50.  
4. Retrieve all products whose price is between 500 and 1000.  
5. Find the total number of products available in the inventory.  
6. Calculate the average price of all products in the "Furniture" category.  
7. Find the most expensive and least expensive product in the inventory.  
8. Count the number of products available in each category.  
9. Retrieve the top 5 most expensive products.  
10. List all products sorted by their stock quantity in descending order.  

---

### **Submission Guidelines:**  
- Write SQL queries for each question.  
- Submit your SQL queries in a `.sql` file or a properly formatted document.  
- Ensure each query is correctly numbered and tested on sample data before submission.  
