 ##Customer Churn Prediction

This repository contains a Jupyter Notebook (or Google Colab Notebook) that performs Exploratory Data Analysis (EDA) and initial data preprocessing for a customer churn prediction dataset.
------------------------------------------------------------------------------------------------------------------------------------------
## Project Overview

The goal of this project is to analyze customer data to understand factors contributing to customer churn and to prepare the data for building a predictive model. This notebook covers:

*   **Data Loading and Initial Inspection**: Loading the dataset and checking its basic structure.
*   **Data Cleaning**: Handling missing values and correcting data types, specifically for the `TotalCharges` column.
*   **Descriptive Statistics**: Summarizing key numerical features.
*   **Univariate and Bivariate Analysis**: Visualizing distributions and relationships between features and the `Churn` target variable.
*   **Feature Engineering (Basic)**: Converting `SeniorCitizen` to a more readable format.
-----------------------------
## Dataset

The dataset used is `Customer_churn.csv`, which contains various customer attributes and their churn status. Key columns include:

*   `customerID`: Unique customer identifier
*   `gender`: Customer's gender
*   `SeniorCitizen`: Whether the customer is a senior citizen (0 or 1, converted to 'no'/'yes')
*   `Partner`: Whether the customer has a partner
*   `Dependents`: Whether the customer has dependents
*   `tenure`: Number of months the customer has stayed with the company
*   `PhoneService`: Whether the customer has phone service
*   `MultipleLines`: Whether the customer has multiple lines
*   `InternetService`: Customer's internet service provider
*   `OnlineSecurity`: Whether the customer has online security
*   `OnlineBackup`: Whether the customer has online backup
*   `DeviceProtection`: Whether the customer has device protection
*   `TechSupport`: Whether the customer has tech support
*   `StreamingTV`: Whether the customer has streaming TV
*   `StreamingMovies`: Whether the customer has streaming movies
*   `Contract`: The customer's contract type
*   `PaperlessBilling`: Whether the customer has paperless billing
*   `PaymentMethod`: The customer's payment method
*   `MonthlyCharges`: The amount charged to the customer monthly
*   `TotalCharges`: The total amount charged to the customer
*   `Churn`: Whether the customer churned or not (Target variable)
----------------------------------------------
## Analysis Highlights

The notebook includes visualizations to explore:

*   The overall churn rate.
*   Churn distribution by `gender`, `SeniorCitizen` status, `Contract` type, `PaymentMethod`, and various `InternetService` related features.
*   The distribution of `tenure` for churned vs. non-churned customers.
----------------------------------------------------
## Technologies Used

*   Python 3
*   Pandas
*   Matplotlib
*   Seaborn
---------------------------------------------------
## How to Run the Notebook

1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```
2.  **Ensure you have the necessary libraries installed**:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Open the notebook**:
    *   If you have Jupyter Notebook installed, you can open it directly.
    *   Alternatively, upload the `.ipynb` file to Google Colab and run it there.

4.  **Place the dataset**: Make sure `Customer_churn.csv` is in the same directory as the notebook or update the path in the data loading cell.

