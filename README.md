# Power BI Assignment: Advanced Measures and Visualizations

## **Project Overview**
This project involves analyzing sales data using **Power BI** to create advanced **DAX measures** and visualizations. The goal is to gain meaningful insights into sales trends, growth, and regional performance.

## **Objectives**
- Import and clean the given sales dataset.
- Create advanced **DAX measures** to analyze sales performance.
- Develop interactive **Power BI visualizations**.
- Identify key insights and trends in sales data.

## **Process**
1. **Dataset Import & Cleaning:**
   - Loaded the dataset containing `SalesDate`, `Region`, `SalesAmount`, `TransactionID`, and `CustomerID`.
   - Converted `SalesDate` into the correct datetime format.
   - Identified missing values in `total sum` and `average` columns.

2. **Measure Creation (DAX):**
   - **Total Sales**: Sum of all sales transactions.
   - **Average Sales per Transaction**: SalesAmount / Number of Transactions.
   - **Sales Growth Percentage**: Year-over-year sales percentage change.
   - **3-Month Moving Average**: Rolling average of sales over 3 months.
   - **Year-to-Date (YTD) Sales**: Cumulative sales from the start of the year.
   - **Cumulative Sales**: Running total of sales over time.

3. **Visualizations Created:**
   - **Bar Chart**: Total Sales by Region.
   - **Line Chart**: Sales Growth Percentage over time.
   - **Line & Clustered Column Chart**: Overlay of 3-Month Moving Average with Total Sales.

## **Tools Used**
- **Power BI** (Data modeling, DAX, Visualizations)
- **Microsoft Excel** (Data cleaning, preliminary analysis)
- **DAX (Data Analysis Expressions)** for measure calculations

## **Key Insights**
1. **Total Sales:** **$259,677.83**
2. **Average Sales per Transaction:** **$519.36**
3. **Top Performing Regions:**
   - **West:** **$58,222.90** (Highest sales revenue)
   - **South:** **$53,763.65**
   - **Central:** **$51,221.00**
4. **Lowest Sales Region:**
   - **North:** **$47,712.74** (Lowest revenue)

## **Insights from Visualizations**
- **Bar Chart - Total Sales by Region:** Clearly highlights the **West region** as the highest contributor to revenue, while the **North region** underperforms, indicating potential areas for market expansion or improvement.
- **Line Chart - Sales Growth Percentage Over Time:** Sales growth fluctuates significantly, showing **positive trends in some years** and **declines in others**. This suggests external factors like market demand, economic conditions, or seasonal variations impacting revenue.
- **Line & Clustered Column Chart - 3-Month Moving Average with Total Sales:** The **moving average line smooths out fluctuations**, revealing a consistent trend in overall sales growth, while spikes and dips in total sales indicate periods of high and low demand.

## **Challenges & Solutions**
| **Challenges** | **Solutions** |
|--------------|--------------|
| **Inconsistent Date Formatting** | Used Power BI’s `DATE` and `FORMAT` functions to standardize date formats. |
| **Missing Values in Total & Average Sales Columns** | Ignored `total sum` and `average` columns, instead recalculating these metrics dynamically using DAX. |
| **Sales Growth Percentage Calculation Errors** | Adjusted the `SAMEPERIODLASTYEAR` function in DAX to correctly reference prior year sales. |

## **Visualizations**
### **1. Bar Chart - Total Sales by Region**
This visualization presents total sales figures for each region, identifying the highest and lowest performing areas.

![Total Sales by Region](path_to_image1.png)

### **2. Line Chart - Sales Growth Percentage Over Time**
This chart helps in tracking yearly sales growth trends, highlighting periods of increase or decline.

![Sales Growth Percentage](path_to_image2.png)

### **3. Line & Clustered Column Chart - 3-Month Moving Average with Total Sales**
Combines total sales (columns) with a smoothed trend line to show sales stability over time.

![3-Month Moving Average](path_to_image3.png)

## **Conclusion**
This Power BI project successfully analyzed sales trends, created advanced DAX measures, and visualized insights. The **regional sales breakdown** and **sales growth trends** provide valuable business intelligence for decision-making. 🚀
