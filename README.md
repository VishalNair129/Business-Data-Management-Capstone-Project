# Business Data Management Capstone Project

## Using Data Analysis to Increase Profit and Perform Sales Prediction 

### Author: Vishal Nair 

## 0.1 Executive Summary
In this project, we aim to understand the problems faced by LuLu shopping mall located in Port Blair, Andaman and Nicobar Islands. The shop is owned by Mr. Abdul Kadar and has been operational since 2011, employing around 32 workers. The store sells electronics and gift items, including household goods, mobile phones, laptops, TVs, refrigerators, and air conditioners.

Our task is to use data analysis to help increase the shop's profit by reducing unnecessary costs and identifying the top-selling goods. The analysis will include plotting sales trends and using machine learning models to predict sales.

## 0.2 Dataset Of LuLu Shopping Mall
The dataset for this project was collected from the store's system after a personal meeting with the owner. The data includes sales information for June 2022, with more than 4500 rows and the following columns:
- Invoice date
- HSN code
- HSN percentage
- Quantity
- Taxable value
- CESS amount
- Total amount
- Product Name

### Metadata
- **Invoice date**: Date at which the product was sold
- **HSN code**: Harmonized System of Nomenclature code for classifying goods
- **HSN percentage**: GST rate based on HSN code
- **Quantity**: Number of goods sold
- **Taxable value**: Value on which GST is computed
- **CESS amount**: Additional tax charged over the base tax liability
- **Total amount**: Total selling price of the goods
- **Product Name**: Name of the product sold

## 0.3 Brief Description of the Data Collected
The data provides daily sales information, including the total amount and quantity of various goods sold. The primary dataset was collected from the shop's system in the form of an Excel sheet. The main variables used for analysis are HSN code, Quantity, and Total amount.

## 0.4 Detailed Explanation of Analysis Process/Methods Used

### 0.4.1 Methods Used

#### Pareto Analysis
The Pareto principle states that roughly 80% of consequences come from 20% of causes. Pareto Analysis helps prioritize goods by comparing their share in total revenue percentage.

#### Sales Prediction Using ML Models in Python
Sales forecasting is the process of estimating future sales based on historical data. It helps businesses make informed decisions about inventory, cash flow, and growth. Accurate sales forecasting supports better revenue management and supply chain optimization.

#### Graph Analysis (Plotting Sales Trends)
Sales trendlines show how sales vary over time. The sales growth graph provides an overview of sales performance, which can be used to derive actionable insights.

### 0.4.2 Analysis Tools and Techniques Used

#### For Graphs and Pareto Analysis: Excel and Power BI
Excel is used to plot various graphs like bar charts, scatter plots, histograms, and pie charts. Pivot tables in Excel help arrange data in the required format for analysis. Pareto analysis was performed to identify the top 6 product fields contributing the most to revenue. Additionally, **Power BI** was utilized for more advanced data visualizations and dynamic dashboards, enabling the presentation of insights through interactive reports. Power BI’s robust visualization capabilities helped provide a clearer understanding of sales trends and correlations, making it easier to identify key areas for improvement.


#### For Sales Prediction: Python
Python, along with libraries like NumPy, pandas, and sklearn, is used for sales prediction. Pairplots and heatmaps help visualize correlations between investment and sales. A Linear Regression model is built using sklearn to predict sales based on investment data.

## 0.5 Results and Findings

### Pareto Chart
Pareto analysis revealed that the top 6 product fields (HSN codes: 8517, 8528, 9102, 10704385, 85171211, and 85171290) contribute significantly to the revenue. These include electronic items like mobile phones and TVs.

### Revenue Trend
The sales trend for June 2022 shows the highest sales at the beginning of the month, likely due to salary cycles. Sales are lowest on Sundays and highest on Wednesdays. Providing offers and discounts on Saturdays could help boost sales.

### Correlation Between Sales and Investment
Pairplots and heatmaps show that investment in product ID 85171211 (mobile phones) has the highest correlation with sales. This suggests that investing in these products can maximize profit.

### Prediction of ML Model
A Linear Regression model was used to predict sales based on investment. The model's results can help the shop predict returns on investment for each product field.

## 0.6 Interpretation of Results and Recommendations

### Recommendations
- **Start Doing**:
  - Focus on the top 6 goods identified by Pareto analysis.
  - Increase offers and discounts during the end of the month and on Saturdays.
  - Invest more in products with high sales correlation (e.g., mobile phones).
  - Use the ML model to predict sales and optimize inventory.
  - Keep electronic sales data, introduce discount coupons, and create awareness about exclusive goods.

- **Stop Doing**:
  - Cut costs on low-selling items.
  - Avoid advertising products with low sales returns.
  - Reduce crowding in the shop by managing worker schedules better.
  - Ensure new workers are trained about product availability.

By following these recommendations, the shop can optimize its operations, reduce unnecessary costs, and increase profitability.

## 0.7 Conclusion
Using data analysis and machine learning, we identified key areas where the shop can improve its profitability. By focusing on high-performing products and optimizing inventory and sales strategies, LuLu shopping mall can enhance its competitive edge and customer satisfaction.

---

Thank you for reviewing this project. For further details, please refer to the linked datasets and documentation.


