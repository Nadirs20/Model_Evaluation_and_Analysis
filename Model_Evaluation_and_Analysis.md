# Model Evaluation and Analysis – Clustering, Regression & Market Basket Analysis

## Disclaimer

This homework project was developed for educational purposes to demonstrate model evaluation, clustering techniques, regression modeling, and association rule mining using IBM SPSS Modeler.

---

## Project Overview

This project focuses on applying different data mining techniques including:

- Two-Step Clustering
- K-Means Clustering
- Feature Selection
- Linear Regression
- Residual Diagnostics
- Market Basket Analysis (Apriori Algorithm)

All modeling steps were performed following proper data partitioning to ensure model validity.

---

## Datasets Used

1. car_sales_knn_mod.sav (Demos)
2. retail_purchase_data.txt (Demos)

---

## Methodology

### 1. Two-Step Cluster Analysis

Dataset: car_sales_knn_mod.sav  
Variables used:
- Engine Size
- Horsepower
- Price

Procedure:
- Applied Partition node before modeling
- Used Two-Step clustering algorithm
- Determined optimal number of clusters automatically
- Interpreted cluster characteristics based on price and engine performance

---

### 2. K-Means Clustering with Auto Cluster

- Used Auto Cluster node
- Tested different cluster sizes
- Evaluated model performance metrics
- Identified ideal cluster size based on model quality indicators

---

### 3. Feature Selection

- Applied Feature Selection node
- Removed:
  - Partition field
  - Type field
  - Other unimportant predictors
- Retained only significant predictors for modeling

---

### 4. Linear Regression Model

Target Variable:
- Price

Steps:
- Applied Partition node before modeling
- Built Linear Regression model
- Evaluated model coefficients and statistical significance
- Interpreted impact of engine size and horsepower on price

---

### 5. Residual Analysis

- Examined distribution of residuals
- Checked normality assumption
- Exported residual normality graph in PNG format
- Evaluated model validity based on residual behavior

---

### 6. Market Basket Analysis (APRIORI)

Dataset: retail_purchase_data.txt  

Steps:
- Applied Partition node
- Used Apriori algorithm
- Generated association rules
- Evaluated:
  - Support
  - Confidence
  - Lift
- Identified strong product combinations

---

## Skills Demonstrated

- Clustering using Two-Step and K-Means algorithms
- Automatic cluster optimization
- Feature selection and dimensionality reduction
- Linear regression modeling
- Residual diagnostics and assumption testing
- Association rule mining using Apriori
- Proper use of Partition node for model validation
- End-to-end data mining workflow in SPSS Modeler

---

## Tools & Technologies Used

- IBM SPSS Modeler (Clementine)
- Statistical modeling techniques
- Data mining algorithms
- Model validation methods

---

## Key Learning Outcomes

- Comparing clustering algorithms and selecting optimal cluster size
- Performing regression diagnostics
- Understanding importance of feature selection
- Applying market basket analysis for business insights
- Ensuring model reliability through proper partitioning
