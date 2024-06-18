# Analysing Customer Interaction Networks in E-Commerce - 2024

## Overview
This GitHub repository contains the project files for the analysis of customer interaction networks within an e-commerce platform. By employing network analysis techniques, this project aims to discover insights into customer preferences, product recommendations, and community dynamics that traditional data analysis methods might overlook.

## Dataset
The analysis leverages customer-product interaction data sourced from the UCI Machine Learning Repository's "Online Retail II" dataset. This dataset documents transactions from a UK-based online retail from December 2009 to December 2011.

### Dataset Accessibility
- **Source and Licensing**: The dataset is available under a public domain license from the UCI Machine Learning Repository and can be accessed [here](https://archive.ics.uci.edu/ml/datasets/online+retail+ii).

### Schema Overview
- **Invoice**: Invoice number, a unique identifier for each transaction.
- **StockCode**: Product code item.
- **Description**: Product description.
- **Quantity**: The quantities of each item per transaction.
- **InvoiceDate**: Invoice date and time.
- **Price**: Unit price.
- **Customer ID**: Customer number, a unique identifier for each customer.
- **Country**: Country name.

## Project Structure
The project is structured into several tasks, each addressing different aspects of network analysis:

### Task 1: Network Construction
- Construct a bipartite graph of customers and products based on transaction data.

### Task 2: Community Detection
- Apply community detection algorithms to identify clusters of frequently co-purchased products and customers with similar buying patterns.

### Task 3: Influence Analysis
- Analyze temporal dynamics of the network and model changes in network properties such as centrality measures and community structures.

### Task 4: Recommendation Systems
- Implement and compare graph-based recommendation systems using the PageRank algorithm against traditional collaborative filtering methods.

## Project File Structure
- **Analysing_Customer_Interaction_Networks_DMSN.ipynb**: Jupyter notebook containing all the code and documentation for executing the tasks mentioned above.

## Methods and APIs Used
- **NetworkX**: Used for constructing and analyzing the network.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For generating visualizations.
- **Surprise**: For implementing collaborative filtering recommendation systems.

## How to Use
1. Clone this repository.
2. Install the required libraries
3. Navigate to the task-specific code cells to run scripts or notebooks.

## Key Findings
- Insights into the most influential products and customers.
- Understanding of the seasonal trends affecting customer buying behaviors.
- Comparison of recommendation systems shows the effectiveness of graph-based methods in leveraging network structure.

## Conclusion
This project demonstrates the applicability of network analysis in extracting meaningful insights from complex customer-product interaction data, providing a basis for informed decision-making in marketing and product placement strategies.
