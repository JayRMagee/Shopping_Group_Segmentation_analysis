# Shopping_Group_Segmentation_analysis

# Project Overview
This project aims to identify the most important shopping groups based on age, income, and shopping score using exploratory data analysis (EDA) and k-means clustering. By analyzing mall shopping data, I seek to uncover patterns and segments within the shopper demographic that can be important for targeted marketing and enhanced customer understanding.

# Data
The dataset used in this project consists of several key attributes including age, annual income (measured in thousands of dollars), and a custom "shopping score" which reflects the shopper's engagement and spending behavior at the mall.

# Tools
The analysis was performed using Python, with the following libraries:

1. pandas for data manipulation and analysis
2. seaborn and matplotlib.pyplot for data visualization
3. sklearn.cluster for implementing the k-means clustering algorithm

# Methodology
1. Data Preprocessing: The data was cleaned and preprocessed to ensure it was suitable for analysis. This included handling missing values and standardizing the data.
2. Exploratory Data Analysis: Initial explorations were conducted to understand the distribution and relationship of variables.
3. K-Means Clustering: We applied the k-means clustering algorithm to segment the shopping data into distinct groups. The optimal number of clusters was determined using the elbow method, assessing the inertia of different cluster solutions.
4. Analysis of Clusters: Each cluster was analyzed using summary statistics to understand the defining characteristics and behaviors of the shoppers in each group.
