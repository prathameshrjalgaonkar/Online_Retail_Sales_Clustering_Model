# Online_Retail_Sales_Clustering_Model

# Online Retail Sales Clustering Model

This repository contains a Jupyter Notebook for clustering online retail sales data using the K-Means algorithm. The project leverages Python for data preprocessing, exploratory data analysis (EDA), and clustering, enabling meaningful insights into customer purchasing behaviors.

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Project Workflow](#project-workflow)
5. [Technologies Used](#technologies-used)
6. [How to Run](#how-to-run)
7. [Results](#results)
8. [Conclusion](#conclusion)

---

## **Project Overview**

This project aims to identify customer segments in retail sales data to enhance marketing strategies and improve business decision-making. The dataset includes transaction-level data such as invoice numbers, customer IDs, product descriptions, and sales figures.

---

## **Dataset**

The project utilizes the [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail) from the UCI Machine Learning Repository. Key attributes include:

- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product identifier.
- **Description**: Product description.
- **Quantity**: Number of products purchased.
- **InvoiceDate**: Date of transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Customer’s country of residence.

---

## **Features**

The notebook implements the following key features:

1. **Data Preprocessing**:
    - Handling missing values, duplicates, and outliers.
    - Creating new features, such as `TotalPrice` and date components.
2. **Exploratory Data Analysis (EDA)**:
    - Sales trends by hour, day, and country.
    - Visualization of customer distribution.
3. **Clustering**:
    - Scaling data using standardization.
    - Determining the optimal number of clusters using the elbow method.
    - Implementing K-Means clustering.
4. **Visualization**:
    - Cluster visualization to interpret customer segments.

---

## **Project Workflow**

1. **Data Preparation**
    - Importing necessary libraries (e.g., pandas, matplotlib, seaborn, plotly).
    - Loading the dataset.

2. **Dataset Analysis**
    - Understanding variable distributions.
    - Statistical summaries and missing value detection.

3. **Data Preprocessing**
    - Cleaning data by addressing missing values, duplicates, and invalid entries.
    - Creating new features, such as `TotalPrice`.

4. **Exploratory Data Analysis (EDA)**
    - Visualizing total sales by hour, customer base distribution, and sales per country.

5. **Clustering**
    - Determining the optimal number of clusters.
    - Applying K-Means and interpreting results.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**:
    - Data Analysis: pandas, NumPy
    - Visualization: matplotlib, seaborn, plotly
    - Clustering: scikit-learn

---

## **How to Run**

1. Clone this repository:

   ```bash
   git clone https://github.com/prathameshrjalgaonkar/online-retail-clustering.git
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Online_Retail_Sales_Clustering_Model.ipynb
   ```

4. Run the notebook cells sequentially to execute the analysis and clustering.

---

## **Results**

- The K-Means algorithm successfully clustered customers into segments based on purchasing behaviors.
- Visualizations highlight distinct customer groups, enabling actionable business insights.
- Key findings include peak sales hours and high-value customer segments.

---

## **Conclusion**

This project demonstrates the potential of clustering algorithms like K-Means to derive meaningful insights from transactional data. By preprocessing the dataset, performing exploratory analysis, and identifying customer segments, businesses can tailor marketing strategies and optimize sales processes. The approach outlined here is scalable and can be adapted to various datasets and industries, showcasing the versatility and importance of data-driven decision-making in modern businesses.

---


