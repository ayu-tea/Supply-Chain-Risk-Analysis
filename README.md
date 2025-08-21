# Supply Chain Risk Analysis

My project focuses on analyzing supply chain data to **identify high-risk suppliers**, understand the **factors contributing to risk**, and propose **actionable control strategies**.

## Objectives

* Clean and preprocess raw supply chain data
* Explore key metrics (lead time, shipping cost, defect rates, etc.)
* Score suppliers based on risk
* Visualize insights and patterns
* Recommend control strategies based on risk levels

## Data Cleaning & Preprocessing

* Handled missing values
* Ensured consistency across numeric features
* Created custom features (e.g., efficiency, defect risk, supplier risk score)


## Exploratory Data Analysis (EDA)

* Visualized distributions of lead time, shipping costs, and defect rates
* Compared suppliers using violin plots, boxplots, etc.
* Identified patterns in risk scores by supplier and location


## Feature Engineering

Derived several key features:

* defect_risk_score: Based on defect rates
* shipping_efficiency_score: Based on cost and time
* supplier_risk_score: Composite score for supplier-level risk
* Risk categories and levels: Low, Medium, High


## Recommendations

Based on risk category and score:

* **Low risk**: Maintain and monitor
* **Medium risk**: Review performance, negotiate pricing
* **High risk**: Audit or replace supplier

## Tech Stack

* Python (Pandas, NumPy, Scikit-learn)
* Visualization: Seaborn, Matplotlib
* Clustering: KMeans, PCA
* Notebook (Colab)

