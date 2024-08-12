![Customer-Segmentation-Analysis-1200x675](https://github.com/user-attachments/assets/17fa8191-364e-412a-b7c8-3a6e050bcf21)


# Customer-Segmentation-Analysis
Through segmentation analysis, we aim to uncover meaningful patterns within this data to better understand and target different customer segments. The project aims is to create clusters or groups of these customers to foster marketing decisions and for better undertsanding of customer characteristics which could ultimately impact sales and profit generation.

# Objective Statement
- Derive business insight about how many product sold every month.
  
- Obtain business insight about how much customer spend their money every month.
  
- To reduce risk in deciding where, when, how, and to whom a product, service, or brand will be marketed.
  
- To increase marketing efficiency by directing effort specifically toward the designated segment in a manner consistent with that segment’s characteristics.

# Methodology / Analytic Technique:

- Descriptive analysis
  
- Exploratory analysis
  
- Segment Analysis

# Importance for Business :

- This intend to help the  Business Development Team to create product differentiation based on the characteristic for each customer.
  
- This will also allow business to determine how to treat customer with a specific criteria.

Expected Outcome:

- Know how many product sold every month.
  
- Know how much customer spend their money every month.
  
- Customer segmentation analysis.
  
- Recommendation based on customer segmentation.

# Data Understanding

- Source Data: Online retail dataset by UCI Machine Learning Library. https://archive.ics.uci.edu/ml/datasets/Online+Retail
  
- The dataset has 8 columns and 541909 rows.

- Data Dictionary:

- InvoiceNo: Invoice number uniquely assigned to each transaction.

- StockCode: Product (item) code.
  
- Description: Product (item) name.
  
- Quantity: The quantities of each product (item) per transaction.
  
- InvoiceDate: The day and time when each transaction was generated.
  
- UnitPrice: Product price per unit in sterling.
  
- CustomerID: Customer number uniquely assigned to each customer.
  
- Country: The name of the country where each customer resides.

# Data Cleansing

- There are about 25% of Null CustomerID in the data. We need to remove them as there is no way we can get the number of CustomerID.

- There are few records with UnitPrice<0 and Quantity<0. We need to remove them from the analysis. This could represent cancelled or returned orders.

- There is more than 90% of 'United Kingdom' customers, therefore we will restrict the data to only United Kingdom customers.
