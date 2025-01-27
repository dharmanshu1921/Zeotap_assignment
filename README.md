# Customer Analytics and Segmentation 

## Overview
This assignment focuses on analyzing customer data, building a lookalike model, and performing customer segmentation using a retail dataset. The analysis includes exploratory data analysis (EDA), customer similarity recommendations, and clustering techniques.

## Dataset Description

The project uses three main CSV files:

### 1. Customers.csv
- **CustomerID**: Unique identifier for each customer
- **CustomerName**: Name of the customer
- **Region**: Continent where the customer resides
- **SignupDate**: Date when the customer signed up

### 2. Products.csv
- **ProductID**: Unique identifier for each product
- **ProductName**: Name of the product
- **Category**: Product category
- **Price**: Product price in USD

### 3. Transactions.csv
- **TransactionID**: Unique identifier for each transaction
- **CustomerID**: ID of the customer who made the transaction
- **ProductID**: ID of the product sold
- **TransactionDate**: Date of the transaction
- **Quantity**: Quantity of the product purchased
- **TotalValue**: Total value of the transaction
- **Price**: Price of the product sold

## Project Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Comprehensive EDA of the dataset
- Derivation of 5+ business insights
- **Deliverables**:
  - EDA Jupyter Notebook (`FirstName_LastName_EDA.ipynb`)
  - Business insights report (`FirstName_LastName_EDA.pdf`)

### Task 2: Lookalike Model
- Customer similarity model development
- Recommendations based on profile and transaction history
- **Deliverables**:
  - Lookalike recommendations CSV (`FirstName_LastName_Lookalike.csv`)
  - Model development notebook (`FirstName_LastName_Lookalike.ipynb`)

### Task 3: Customer Segmentation
- Implementation of clustering algorithms
- Calculation of DB Index and other metrics
- Cluster visualization
- **Deliverables**:
  - Clustering analysis report (`FirstName_LastName_Clustering.pdf`)
  - Clustering code notebook (`FirstName_LastName_Clustering.ipynb`)

## Technical Requirements

### Task 1: EDA
- Complete exploratory analysis
- Business insights limited to 100 words per insight

### Task 2: Lookalike Model
- Top 3 lookalikes for customers C0001-C0020
- Similarity scores for each recommendation
- Output format: Map<cust_id, List<cust_id, score>>

### Task 3: Clustering
- Cluster count: Between 2 and 10
- Required metrics: DB Index
- Visualization of clustering results

## Evaluation Criteria

### Lookalike Model
- Model accuracy and logic
- Quality of recommendations
- Similarity score relevance

### Clustering
- Clustering algorithm implementation
- DB Index and other metrics
- Visualization quality

## Submission Guidelines
1. All files must be uploaded to a public GitHub repository
2. Follow the specified file naming convention
3. Ensure all deliverables are properly documented

## Contact
For any questions or clarifications about this project, please open an issue in the GitHub repository.
