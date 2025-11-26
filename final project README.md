# Retail Sales Data Analyzer

This project provides a Python-based Retail Sales Data Analyzer that
loads a CSV file, performs data analysis, and visualizes sales using
charts.

------------------------------------------------------------------------

## 📌 Features

-   Load and validate retail sales CSV data\
-   Calculate key metrics:
    -   Total Sales
    -   Average Sales
    -   Most Popular Product
-   Filter data by column and value\
-   Visualizations:
    -   Bar Chart (Sales by Category)
    -   Line Chart (Daily Sales Trend)
    -   Heatmap (Correlation Matrix)

------------------------------------------------------------------------

## 📁 Required CSV Columns

Your CSV file must include:

-   `Date`
-   `Product`
-   `Category`
-   `Price`
-   `Quantity Sold`
-   `Total Sales`

------------------------------------------------------------------------

## 🚀 How to Use

1.  Run the script\
2.  Enter the path of your CSV file\
3.  Choose an option from the menu:
    -   View summary
    -   Filter data
    -   Generate charts
    -   Exit program

------------------------------------------------------------------------

## 🛠️ Dependencies

Install required libraries:

``` bash
pip install pandas numpy matplotlib seaborn
```

------------------------------------------------------------------------

## ▶️ Running the Program

``` bash
python retail_analyzer.py
```

------------------------------------------------------------------------

## 📌 Project Structure

    RetailAnalyzer
    │── retail_analyzer.py
    │── README.md
    │── sample_data.csv (optional)

------------------------------------------------------------------------

## 🧑‍💻 Author

Developed based on user requirements.
