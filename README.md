# E-commerce Sales Data Analysis

## Project Overview
This project involves a comprehensive analysis of transactional data from a UK-based online retail company. The goal is to understand key aspects of the business, including sales performance, customer behavior, product trends, and temporal patterns. The analysis covers data loading, cleaning, feature engineering, exploratory data analysis (EDA), and specific analyses focusing on customers, products, countries, and time series trends.

## Data Source
The dataset used for this analysis is the "Online Retail" dataset from the UCI Machine Learning Repository. It contains transactional data from 01/12/2010 to 09/12/2011.
Source: [https://archive.ics.uci.edu/ml/datasets/Online+Retail](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

## Files in this Repository
*   `E_Commerce_Analysis.ipynb`: The main Jupyter Notebook containing all the code, analysis steps, visualizations, and detailed explanations.
*   `requirements.txt`: A file listing the Python libraries required to run the notebook.

## How to Run the Notebook
1.  **Clone the repository:**

    ```bash
    git clone https://github.com/AnirbanRoy-cloud/E-Commerce-Analysis
    ```
2.  **Navigate to the repository directory:**

    ```bash
    cd E-Commerce-Analysis
    ```
3.  **Install the required libraries:**

    ```bash
    pip install -r requirements.txt
    ```
4.  **Open and run the notebook:** You can open the `E_Commerce_Analysis.ipynb` file in Jupyter Notebook, JupyterLab, or Google Colab.

## Key Findings
*   The dataset was cleaned by handling missing values, correcting data types, and removing duplicates and inconsistent entries (negative quantity/price), resulting in a dataset of 392,692 rows.
*   New features like TotalPrice, DayOfWeek, Month, and Hour were engineered for deeper analysis.
*   The distribution of TotalPrice is heavily skewed towards lower values.
*   The United Kingdom is the dominant market by both total quantity sold and total revenue.
*   Sales exhibit clear temporal patterns, with peak sales in November and higher activity on Thursdays and Wednesdays, and during late morning/early afternoon hours.
*   Specific products like 'PAPER CRAFT , LITTLE BIRDIE' and 'REGENCY CAKESTAND 3 TIER' are top performers.
*   Customer spending is highly concentrated, with a few high-spending customers significantly contributing to revenue.
*   Time series trends show significant daily fluctuations and a strong upward trend in the latter half of 2011, peaking in November.

## Visualizations
Key visualizations illustrating sales trends, customer behavior, and product performance are included within the `E_Commerce_Analysis.ipynb` notebook.

## Skills Demonstrated
Python (Pandas, NumPy, Matplotlib, Seaborn), Statistical Analysis, Data Visualization, Business Intelligence, Data Cleaning, Feature Engineering.

## License
MIT License

## Contact
[Optional: Add your contact information or links to your profiles]
