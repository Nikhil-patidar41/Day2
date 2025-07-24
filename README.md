This project is part of my internship assignment at Main Flow Services and Technologies Pvt. Ltd., Sector 63, Noida. It focuses on performing Exploratory Data Analysis (EDA) and building a linear regression model to analyze and predict sales performance using the Global Superstore dataset.

 Objectives
Clean and explore a real-world sales dataset

Identify trends, outliers, and correlations

Visualize business metrics like profit, sales, region, category

Build a simple machine learning model to predict sales

Gain business insights from the data

 Dataset Description
The dataset includes:

Sales, Profit, Discount, Shipping Cost

Order Date, Ship Date, Customer Info

Region, State, Segment, Product Category & Sub-Category

The dataset was cleaned by removing duplicates, converting dates, and dropping an unknown column (记录数).

 Technologies Used
Python 3

Pandas, NumPy – for data analysis

Matplotlib, Seaborn – for data visualization

Scikit-learn – for predictive modeling

Jupyter Notebook – for development & reporting

Key Visualizations
Histogram of Sales distribution

Boxplot for detecting Profit outliers

Heatmap for correlation between numerical features

Time series plot: Sales over time

Scatter plot: Profit vs. Discount

Bar chart: Sales by Region

Pie chart: Sales by Category

Predictive Modeling
A Linear Regression model was built to predict Sales using:

Features: Profit, Discount

Target: Sales

Evaluation Metrics:
R² Score: ~0.29

Mean Squared Error (MSE): Calculated using scikit-learn

The model explains ~29% of the variation in sales using just two features. Further improvement is possible by including more predictors.

