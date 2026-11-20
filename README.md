# Retail Sales Analysis Project

An end-to-end retail sales analysis project using eight CSV datasets. The work includes a 21-question business analysis in Excel and Python Pandas, Pandas practice operations in Google Colab, and an interactive Power BI dashboard.

## Project work

### Excel analysis

Completed the 21 sales performance questions using the provided dataset, including revenue, profit, quantity sold, monthly sales, regions, products, employees, customers, stores, sales channels, returns, sales targets, and business insights. The completed workbook contains the Excel analysis and summaries.

### Python Pandas analysis

Used the same data in Google Colab to answer the 21 sales analysis questions and practise the assigned Pandas operations, including:

- Selecting and filtering data
- Cleaning and preprocessing data
- Manipulating and transforming data
- Sorting and ranking
- Grouping and aggregation
- Combining datasets
- Date and time operations
- String operations
- Statistical analysis

## Today's independent analysis task — 20 November 2026

For today's task, I developed 10 original questions from the available dataset columns. I selected each question to explore a pattern that differs from the 21 assigned questions, then created a graph to make the comparison clear. The PNGs below were generated from the repository's CSV data.

### 1. How does revenue vary by day of the week?
This can help identify busy and quiet shopping days for promotions and staffing.

![Revenue by day of the week](Revenue%20by%20day%20of%20the%20week.png)

### 2. Do customer age groups prefer different product categories?
This compares category demand across customer age groups.

![Units sold by age group and product category](Units%20sold%20by%20age%20group%20and%20product%20category.png)

### 3. Which payment methods are used most, and which generate the most revenue?
This compares payment frequency with the revenue associated with each method.

![Orders and revenue by payment method](orders%20and%20revenue%20by%20payment%20method.png)

### 4. Are larger discounts associated with more units sold?
This explores the relationship between discounts and the quantity on order items.

![Discount level and quantity sold](Discount%20level%20and%20quantity%20sold.png)

### 5. Which suppliers contribute the most revenue and profit?
This compares supplier sales and profitability.

![Revenue and profit by supplier](Revenue%20and%20profit%20by%20supplier.png)

### 6. How many days pass between a product launch and its first sale?
This shows how quickly new products begin selling.

![Days from product launch to first sale](Days%20from%20product%20launch%20to%20first%20sale.png)

### 7. Do long-time customers spend more than newer customers?
This compares customer signup dates with total spending.

![Customer signup date and total spending](customer%20signup%20date%20and%20total%20spending.png)

### 8. Which customer cities have the most orders and highest average order value?
This compares order volume and typical order value by city.

![Order count and average order value by city](Order%20count%20and%20average%20order%20value%20by%20city.png)

### 9. Are return reasons more common for particular product categories?
This looks for return patterns that may be concentrated in specific categories.

![Returned items by category and reason](Returned%20items%20by%20category%20and%20reason.png)

### 10. Is employee salary related to revenue generated?
This explores whether salary and sales revenue show a relationship.

![Employee salary and revenue generated](Employee%20salary%20and%20revenue%20generated.png)

The charts show patterns in this dataset; they do not by themselves prove that one factor caused another.

## Google Colab graphs

The Pandas notebook generates the analysis graphs in Google Colab: monthly revenue, revenue by region and sales channel, top 10 products by revenue, return reasons, and monthly actual revenue versus regional targets. These are Colab notebook graphs; Power BI visuals are available in the `.pbix` dashboard.
### Power BI dashboard

Created a four-page interactive dashboard:
## Power BI Dashboard
### Executive Overview
![Retail Sales Executive Overview](RETAIL%20SALES%20PERFORMANCE%20-%20Copy%20%282%29.png)

### Products & Employees
![Products and Employee Performance](PRODUCTS%20AND%20EMPLOYEE%20PERFORMANCE.png)

### Customers & Stores
![Customer and Store Performance](CUSTOMER%20AND%20STORE%20PERFORMANCE.png)

### Returns & Targets
![Returns and Target Achievement](RETURNS%20AND%20TARGET%20ACHIEVEMENT.png)
## Repository structure

```text
Retail_Sales_Analysis_Project/
├── README.md
├── data/
│   ├── customers.csv
│   ├── employees.csv
│   ├── order_items.csv
│   ├── orders.csv
│   ├── products.csv
│   ├── returns.csv
│   ├── stores.csv
│   └── targets.csv
├── excel/
│   └── Sales_Performance_Analysis.xlsx
├── pandas/
│   └── Pandas_Retail_Sales_Operations.ipynb
└── powerbi/
    ├── Retail_Sales_Dashboard.pbix
    └── Retail_Sales_PowerBI_Theme.json
```

## How to use

- Open the Excel workbook in Microsoft Excel to view the analysis and PivotTables.
- Open the notebook in Google Colab or Jupyter and run its cells. If needed, upload the CSV files from `data/` to the notebook environment.
- Open the `.pbix` file in Power BI Desktop. If refreshing the report on another computer, update the data source paths to the CSV files in `data/`.

## Tools used

Microsoft Excel, Python Pandas, Google Colab, and Microsoft Power BI.

