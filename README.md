# Bank Clients Clustering

## Overview
This project involves creating an unsupervised machine learning clustering model to group bank customers based on various features and studying each cluster.

**Note:**
This project is a continuation of the project on the classification of clients (where the EDA analysis was already done)

### Development Environment
- **Platform**: Google Collaboratory

## Libraries Used
### Data Pre-Processing and Analysis
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- missingno

### Model Training
- K-Means

### Evaluation Metrics
- sklearn.metrics
- yellowbrick

## Introduction to the Dataset
- **Source**: Bank marketing Dataset available in the git folder as `bank-marketing.csv`.
- **Description**: The dataset includes banking data to facilitate a marketing campaign, focusing on how banks can target customers to maximize the product selling potential.
- **Size**: 45211 rows and 23 columns.

### Attribute Information
- **Age**: Customer's age.
- **Age Group**: Age group of the customer.
- **Eligibility**: Eligibility for the campaign.
- **Job**: Customer's occupation.
- **Salary**: Customer's salary.
- **Marital Status**: Marital status.
- **Education Level**: Highest level of education attained.
- **Marital-Education Status**: Combined marital status and education level.
- **Targeted**: If the customer is targeted by the campaign.
- **Default Status**: Default status of the customer.
- **Account Balance**: Account balance.
- **Housing Status**: Housing information.
- **Loan Status**: Loan information.
- **Contact Source**: Source of contact information.
- **Day & Month**: Date of contact.
- **Duration**: Duration of contact in days.
- **Campaign**: Campaign details.
- **Pdays**: Days since last contact.
- **Previous Response & POutcome**: Outcome of previous campaigns.
- **Y (Decision)**: Customer's decision (Yes/No).
- **Response**: Customer's response.

## Project Steps
1. Data Import
2. Handling missing values (Remove, fill NaN values)
3. Features Selection
4. Feature Engineering
5. Feature Scaling(Standartization)
6. Feature Encoding
7. Dimensionality reduction - UMAP
8. selecting the number of clusters
9. Model Training
10. Interpretation

## Results and Metrics
The model performance is summarized by the following metrics:
- **Silhouette Score**: 0.5
- **Calinski-Harabasz Index (Variance Ratio Criterion)**: 52000
- **Davies–Bouldin Index**: 0.82

