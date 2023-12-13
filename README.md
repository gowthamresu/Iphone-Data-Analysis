# iPhone Data Analysis

## Introduction
This repository contains Python code for analyzing iPhone product data using the pandas library. The dataset used is related to various iPhone models, including product details, pricing, and ratings. The analysis includes basic statistics, price range filtering, and insights into the highest and lowest-priced iPhones.

## Requirements
Make sure you have the following libraries installed:
- pandas

You can install them using the following command:
```bash
pip install -r requirements.txt
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/iphone-data-analysis.git
cd iphone-data-analysis
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook or Python script to perform the analysis.
Dataset
The dataset (apple_products.csv) contains information about various iPhone models, including:

Product Name
Product URL
Brand
Sale Price
MRP (Maximum Retail Price)
Discount Percentage
Number of Ratings
Number of Reviews
UPC (Universal Product Code)
Star Rating
RAM
Analysis Highlights
Basic Data Summary: Use df.info() and df.count() to provide an overview of the dataset's structure and completeness.
Price Analysis: Display the maximum and minimum prices for iPhones and identify the specific models with these extreme values.
Price Range Filtering: Filter iPhones within a specified price range to analyze high-end and budget-friendly options.
Unique Product Names: Display a list of unique product names to identify the diversity of iPhone models in the dataset.
Model Name Extraction: Create a new column, 'Model Name', from the 'Product Name' for better categorization.
Star Rating Analysis: Analyze unique values, counts, and sort the DataFrame based on 'Star Rating' to find the highest-rated iPhones.
Files
iphone_data_analysis.ipynb: Jupyter Notebook containing the analysis code.
apple_products.csv: CSV file containing the raw dataset.
