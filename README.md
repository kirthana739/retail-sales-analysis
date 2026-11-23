# Retail Sales Analysis Project

An end-to-end retail analytics project using Excel, Python (pandas), Google Colab, and Power BI. The project explores eight related CSV datasets, answers 21 assigned business questions, and adds 10 independent questions with supporting charts.

## Project at a glance

- **Business area:** retail sales, products, customers, stores, employees, and returns
- **Data:** eight CSV files covering customers, employees, order items, orders, products, returns, stores, and targets
- **Analysis tools:** Microsoft Excel, Python/pandas, Google Colab, and Power BI
- **Outputs:** Excel workbook, Colab notebooks, analysis charts, and Power BI dashboard screenshots

## Project work

### Excel analysis

Answered 21 sales-performance questions using the supplied dataset. The analysis covers revenue, profit, quantity sold, monthly sales, regions, products, employees, customers, stores, sales channels, returns, and targets. The workbook contains the Excel analysis and summaries.

[Open the Excel workbook](Sales_Performance_Analysis.xlsx.xlsx)

### Python and Google Colab

Used pandas in Google Colab to work through the 21 assigned questions and practise:

- Selecting and filtering data
- Cleaning and preprocessing
- Transforming and sorting data
- Grouping and aggregation
- Combining datasets
- Date and string operations
- Statistical summaries

The repository also includes a notebook with 10 independent questions and charts.

- [Pandas practice notebook](Pandas_Retail_Sales_Operations1.ipynb)
- [Independent questions notebook](Own_Questions_Retail_Sales_Analysis.ipynb)

To run a notebook in Colab, open it and upload the CSV files when prompted. Keep the CSV column names unchanged unless you also update the notebook code.

## Independent analysis questions

These questions were selected to explore additional patterns in the available data. Each is accompanied by a chart in the repository.

1. **How does revenue vary by day of the week?** This can help identify busier and quieter shopping days.

   ![Revenue by day of the week](Revenue%20by%20day%20of%20the%20week.png)

2. **Do customer age groups prefer different product categories?** This compares units sold across age groups and categories.

   ![Units sold by age group and product category](Units%20sold%20by%20age%20group%20and%20product%20category.png)

3. **Which payment methods are used most, and which are associated with the most revenue?** This compares payment frequency and revenue.

   ![Orders and revenue by payment method](orders%20and%20revenue%20by%20payment%20method.png)

4. **Are larger discounts associated with more units sold?** This explores discount levels and item quantities.

   ![Discount level and quantity sold](Discount%20level%20and%20quantity%20sold.png)

5. **Which suppliers contribute the most revenue and profit?** This compares supplier-level sales and profit.

   ![Revenue and profit by supplier](Revenue%20and%20profit%20by%20supplier.png)

6. **How many days pass between a product launch and its first sale?** This explores how quickly products begin selling.

   ![Days from product launch to first sale](Days%20from%20product%20launch%20to%20first%20sale.png)

7. **Do long-time customers spend more than newer customers?** This compares signup timing with customer spending.

   ![Customer signup date and total spending](customer%20signup%20date%20and%20total%20spending.png)

8. **Which customer cities have the most orders and highest average order value?** This compares order volume and average order value by city.

   ![Order count and average order value by city](Order%20count%20and%20average%20order%20value%20by%20city.png)

9. **Are return reasons more common for particular product categories?** This checks how returns are distributed across categories and reasons.

   ![Returned items by category and reason](Returned%20items%20by%20category%20and%20reason.png)

10. **Is employee salary associated with revenue generated?** This explores a relationship in the provided data; it does not show that salary causes revenue.

   ![Employee salary and revenue generated](Employee%20salary%20and%20revenue%20generated.png)

The charts show patterns in this dataset. They do not, by themselves, prove that one factor caused another.

## Power BI dashboard

The Power BI dashboard is organized into four pages:

### Executive Overview

![Retail Sales Executive Overview](RETAIL%20SALES%20PERFORMANCE%20-%20Copy%20%282%29.png)

### Products and Employees

![Products and Employee Performance](PRODUCTS%20AND%20EMPLOYEE%20PERFORMANCE.png)

### Customers and Stores

![Customer and Store Performance](CUSTOMER%20AND%20STORE%20PERFORMANCE.png)

### Returns and Targets

![Returns and Target Achievement](RETURNS%20AND%20TARGET%20ACHIEVEMENT.png)

The repository currently includes screenshots of the dashboard. Add the `.pbix` file if you want reviewers to open and interact with the report in Power BI Desktop.

## Colab analysis graphs

The pandas notebook also creates graphs for monthly revenue, revenue by region and sales channel, top products by revenue, return reasons, and monthly actual revenue compared with regional targets.

## Data files and privacy

The eight CSV datasets are currently listed at the repository root:

- `customers.csv`
- `employees.csv`
- `order_items.csv`
- `orders.csv`
- `products.csv`
- `returns.csv`
- `stores.csv`
- `targets.csv`

Before sharing the repository publicly, confirm that the customer and employee data are synthetic or explicitly approved for public release. If they contain real or identifiable personal or confidential information, remove them from the public repository and its history. Do not publish customer email addresses or confidential salary information.

## Repository files

```text
retail-sales-analysis/
├── README.md
├── Own_Questions_Retail_Sales_Analysis.ipynb
├── Pandas_Retail_Sales_Operations1.ipynb
├── Sales_Performance_Analysis.xlsx.xlsx
├── customers.csv
├── employees.csv
├── order_items.csv
├── orders.csv
├── products.csv
├── returns.csv
├── stores.csv
├── targets.csv
├── CUSTOMER AND STORE PERFORMANCE.png
├── Days from product launch to first sale.png
├── Discount level and quantity sold.png
├── Employee salary and revenue generated.png
├── Order count and average order value by city.png
├── PRODUCTS AND EMPLOYEE PERFORMANCE.png
├── RETAIL SALES PERFORMANCE - Copy (2).png
├── RETURNS AND TARGET ACHIEVEMENT.png
├── Returned items by category and reason.png
├── Revenue and profit by supplier.png
├── Revenue by day of the week.png
├── Units sold by age group and product category.png
├── customer signup date and total spending.png
└── orders and revenue by payment method.png

```

The chart and dashboard screenshot image files are stored at the repository root and embedded in this README. The `.pbix` source file is not shown in the current repository file listing.

## How to use

- Open the Excel workbook in Excel to review the analysis and summaries.
- Open either `.ipynb` notebook in Google Colab or Jupyter. In Colab, upload the required CSV files when prompted.
- View the dashboard page screenshots above. If the `.pbix` file is added, open it in Power BI Desktop. When refreshing on another computer, update the data source paths as needed.

## Tools used

- Microsoft Excel
- Python
- pandas
- Google Colab
- Microsoft Power BI

## Limitations

- Findings describe the supplied dataset and depend on the metric definitions used in each analysis.
- A relationship or correlation in a chart does not prove causation.
- The employee salary and revenue comparison should be treated as exploratory and should only be shared if the data is approved for that use.
- Confirm discount, sales, profit, return-rate, and target definitions before presenting them as official business metrics.

## Planned extension: Order Health and Basket Analysis

This is a proposed next dashboard, not a completed project page. It would use the same order, order-item, and product data to explore questions such as:

- How do order statuses differ by sales channel?
- How does cancellation rate change by month and region?
- What is the estimated value of cancelled orders?
- Which sales channels have larger order baskets?
- How do discounts relate to gross profit margin?
- Which product categories are commonly purchased together?

Any cancelled-order value should be labeled as an estimate, not completed revenue. Product-category combinations require preparing a table of categories appearing in the same order.


