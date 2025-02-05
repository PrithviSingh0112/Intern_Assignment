# Data Analysis - Customer Segmentation and Sales Insights

## Project Overview
This project analyzes transactional and customer data to derive actionable insights for marketing. The goal is to:
1. Identify the **most profitable customers** by total sales.
2. Identify the **most loyal customers** by transaction frequency.
3. Highlight the **top-selling products** by total sales volume.

### Datasets
The analysis was conducted on two datasets:

1. **Transaction Data**:
   - Columns: `DATE`, `STORE_NBR`, `LYLTY_CARD_NBR`, `TXN_ID`, `PROD_NBR`, `PROD_NAME`, `PROD_QTY`, `TOT_SALES`
   - Contains information about each transaction, such as product details, quantity sold, and the total sales amount.

2. **Customer Data**:
   - Columns: `LYLTY_CARD_NBR`, `LIFESTAGE`, `PREMIUM_CUSTOMER`
   - Contains demographic data about customers, including life stage and whether the customer is a premium, mainstream, or budget customer.

### Analysis Insights

#### Most Profitable Customers
The top 3 most profitable customers were identified by summing total sales for each customer. We found that:
1. **Older Families (Premium)** are the highest spenders.
2. **Older Families (Budget)** customers also contribute significantly, although their total spend is lower.

#### Most Loyal Customers
The most loyal customers were identified by counting the number of transactions for each customer. Key findings include:
1. **Older Families** exhibit high loyalty with repeat purchases.
2. **Young Singles/Couples** also show a strong tendency to make regular purchases, indicating potential convenience-driven buying habits.

#### Bestselling Products
The top-selling products, identified by total sales volume, include:
1. **Dorito Corn Chips Supreme 380g** - The most popular product.
2. **Smiths Crinkle Chips Original** - Another highly popular product.
3. **Smiths Crinkle Chips Salt & Vinegar** - A favorite among customers.

### Hypothesis
- **Most Profitable Customers**: Older families, especially those classified as Premium, tend to make high-value purchases. Budget-conscious older families also contribute significantly, though with more selective spending.
- **Most Loyal Customers**: Older families are highly loyal, possibly due to family needs. Younger families and singles/couples tend to be more convenience-driven, leading to frequent transactions.
- **Bestselling Products**: The bestselling products are primarily snacks, with a preference for larger pack sizes, suggesting a focus on family-oriented consumption.

### Plotting
The analysis includes various plots for visualization:
- Bar plots for the top profitable and loyal customers.
- A bar plot for the bestselling products.

### Requirements
To run this project locally, you will need:
- Python 3.x
- Required libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`

You can install the required libraries using pip:
```bash
pip install pandas matplotlib seaborn numpy
