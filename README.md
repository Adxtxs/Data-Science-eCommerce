# Data Science Assignment Submission: eCommerce

## Overview
This repository contains submission for the Data Science assignment focused on eCommerce transactions. The assignment involved performing exploratory data analysis (EDA), building predictive models, and deriving actionable insights from the provided datasets.

### Datasets
The following datasets were utilized in this project:
- **Customers.csv**: [Download Link](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
- **Products.csv**: [Download Link](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
- **Transactions.csv**: [Download Link](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

## Files Description
1. **Customers.csv**
   - **CustomerID**: Unique identifier for each customer.
   - **CustomerName**: Name of the customer.
   - **Region**: Continent where the customer resides.
   - **SignupDate**: Date when the customer signed up.

2. **Products.csv**
   - **ProductID**: Unique identifier for each product.
   - **ProductName**: Name of the product.
   - **Category**: Product category.
   - **Price**: Product price in USD.

3. **Transactions.csv**
   - **TransactionID**: Unique identifier for each transaction.
   - **CustomerID**: ID of the customer who made the transaction.
   - **ProductID**: ID of the product sold.
   - **TransactionDate**: Date of the transaction.
   - **Quantity**: Quantity of the product purchased.
   - **TotalValue**: Total value of the transaction.
   - **Price**: Price of the product sold.

## Assignment Tasks Completed

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Conducted comprehensive EDA on the datasets.
- Derived the following business insights:
  1. **Insight 1**: Customers from North America have a higher average transaction value compared to other regions.
  2. **Insight 2**: The **Electronics** category generates the highest sales volume, indicating a strong market demand.
  3. **Insight 3**: New customers (signed up within the last year) contribute significantly to total sales, suggesting effective marketing strategies.
  4. **Insight 4**: Repeat customers have a higher average purchase frequency, emphasizing the importance of customer retention strategies.
  5. **Insight 5**: Seasonal trends show increased sales during the holiday months, which could guide inventory and marketing strategies.

**Deliverables:**
- **EDA Code**: `FirstName_LastName_EDA.ipynb`
- **Business Insights Report**: `FirstName_LastName_EDA.pdf`

### Task 2: Lookalike Model
- Developed a Lookalike Model to recommend similar customers based on their profiles and transaction history.
- Generated the top 3 lookalikes with similarity scores for the first 20 customers.

**Deliverables:**
- **Lookalike Recommendations**: `FirstName_LastName_Lookalike.csv`

### Task 3: Customer Segmentation / Clustering
- Performed customer segmentation using K-Means clustering.
- Number of clusters formed: **4**
- Davies-Bouldin Index: **0.9863**
- Visualized the clusters effectively.

**Deliverables:**
- **Clustering Results Report**: `FirstName_LastName_Clustering.pdf`
- **Clustering Code**: `FirstName_LastName_Clustering.ipynb`

**Thank you for reviewing my submission!**

