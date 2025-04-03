# Customer Analytics Project

## Project Overview

This project focuses on analysing customer behaviour, purchasing trends, and marketing engagement for an e-commerce company. The goal is to explore customer segmentation, purchasing habits, promotional engagement, and retention rates. The project consists of an **interactive Tableau Dashboard** for visualising key metrics and a **Jupyter Notebook** containing the analytical analysis to support data-driven decision-making.

Key visualisations and analyses include:

- **Customer Spending** across different product categories (e.g., Wines, Fruits, Meat Products, etc.).
- **Engagement with Promotional Campaigns** and Discounts.
- **Customer Retention Rates** and trends over time.
- **Recency of Purchases** and its relationship with customer engagement.
- **Purchase Behaviour by Channel** (Website, Catalogue, Store).

## Project Contents

### 1. Tableau Dashboard

The **Tableau Dashboard** provides an interactive visualisation of customer data and key performance indicators (KPIs). The dashboard allows users to explore customer demographics, product categories, and purchasing behaviour.

**Features:**
- Displays **average spending per customer** across different product categories.
- Visualises **customer engagement** with promotional campaigns and discounts.
- Tracks **customer retention** and purchasing patterns.
- Analyzes **purchasing behaviour by channel** (e.g., website, catalogue, in-store).
- Allows filtering by customer demographics.
- Available for viewing and interaction on **Tableau Public**.

### 2. Jupyter Notebook

The **Jupyter Notebook** provides the code and analysis for cleaning, processing, and analysing the customer data. It includes:

- Data loading, cleaning, and processing.
- Exploratory data analysis (EDA) to uncover trends and patterns.
- Statistical analyses for calculating key metrics.
- Data visualisations using **Matplotlib** and **Seaborn** to support insights.

The notebook complements the Tableau visualisations by providing a deeper dive into the analysis, data processing, and feature engineering steps that led to the creation of the dashboard.

## Technologies Used

- **Data Visualisation**: Tableau
- **Data Analysis & Processing**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Notebook Environment**: Jupyter Notebook
- **Data Sources**: Customer demographics, purchasing behaviour, marketing engagement, and purchase channel data.

## Dashboard Access

The **Customer Analytics Dashboard** is available on **Tableau Public**. You can view and interact with the dashboard through the following link:

[**View Dashboard on Tableau Public**](https://public.tableau.com/views/understanding_customer_behavior/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Jupyter Notebook Access

The analysis for this project is available in a Jupyter Notebook format. You can view and run the notebook for a deeper dive into the analysis and the methods used. The notebook covers:

- Data loading, cleaning, and processing.
- Exploratory data analysis (EDA).
- Calculating key metrics such as spending per customer, retention rates, and promotional engagement.
- Visualising data trends using Python libraries (Matplotlib, Seaborn).

## Setup & Requirements

### To run the Jupyter Notebook locally:

1. **Install Jupyter Notebook**: If you don't have Jupyter Notebook installed, you can install it via Anaconda or pip:

   3. **Download the Notebook**: Clone or download the repository and open the Jupyter notebook file (`analysis.ipynb`).
4. **Run the notebook**: Open the notebook in Jupyter and run the cells to reproduce the analysis and visualisations.

### To view the Tableau Dashboard locally:

1. **Download Tableau Desktop**: Install Tableau Desktop to open the workbook file locally.
2. **Download the Tableau Workbook**: Download the `.twbx` file from the repository.
3. **Open the workbook**: Open the file in Tableau Desktop to explore the visualisations and interact with the filters.

## Project Structure

- `understanding_customer_behaviour.twbx`: Tableau workbook containing all visualisations and calculations.
- `analysis.ipynb`: Jupyter Notebook for data analysis, cleaning, and exploration.
- `data/`: Folder containing any datasets used in the project (if shared).
- `documentation/`: Additional documentation explaining project methodology, data processing steps, and insights.

## Key Insights

### Tableau Dashboard:

- **Customer Spending Trends**: Visualises the average spending per customer across different product categories (e.g., Wines, Fruits, Meat, etc.).
- **Engagement with Promotional Campaigns**: Shows the success rate of different campaigns and the percentage of customers responding to discounts.
- **Customer Retention**: Tracks retention rates over time and identifies which customers are more likely to return.
- **Purchasing by Channel**: Analyzes purchases by channel (Web, Catalogue, Store) and identifies high-performing channels.

### Jupyter Notebook:

- **Customer Segmentation**: Grouped customers based on spending behaviour and demographics.
- **Retention and Engagement Analysis**: Statistical analysis of retention rates and promotional engagement.
- **Visualisation of Key Metrics**: Line charts and heatmaps showing how recency of purchase impacts future spending.

## Future Improvements

- **Predictive Analytics**: Extend the dashboard to include predictive models for customer churn or lifetime value.
- **Additional Filters and Granularity**: Add more detailed filters or demographic segments for better insights.
- **Automated Reports**: Set up automated reports or notifications for key stakeholders based on updated data.

