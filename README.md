# Assignment: CSCA 5632 Unsupervised Learning Final Project

# Introduction: Customer Segmentation Using Unsupervised Learning

## Project Overview

### Project Description
This project focuses on segmenting mall customers based on their demographic and behavioral attributes to enable targeted marketing strategies. The task is clustering, a type of unsupervised learning, where no predefined labels are used to group customers into meaningful segments. The algorithms employed include K-Means, DBSCAN, and Gaussian Mixture Models (GMM) to identify distinct customer groups based on features like age, income, and spending score.

### Goal
The goal is to uncover hidden patterns in customer behavior to help mall management tailor promotions, optimize store layouts, and enhance customer experiences. By segmenting customers, businesses can improve marketing efficiency and customer satisfaction, addressing a real-world need in retail analytics.

### Data Source
The dataset is sourced from Kaggle’s “Customer Segmentation Tutorial in Python” dataset, a public dataset designed for clustering tasks. It was gathered to simulate customer profiles for a mall, though specific collection details are not provided by the author.
Citation: Choudhary, V. (2018). Customer Segmentation Tutorial in Python [Data set]. Kaggle. Retrieved from https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Data Description
The dataset contains 200 rows (samples) and 5 columns (features):


* CustomerID: Unique identifier (integer, dropped for clustering).
* Gender: Categorical (Male/Female).
* Age: Numeric (integer, range 18–70 years).
* Annual Income (k$): Numeric (integer, range 15–137 k$).
* Spending Score (1-100): Numeric (integer, range 1–100, reflecting purchase behavior).

The dataset is tabular, stored as a CSV file, with a size of approximately 4 KB.
