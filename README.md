# Analysing Pharmaceutical Sales Data

## Project Overview

This project analyzes pharmaceutical sales data using Python, Pandas, and Matplotlib. The objective is to explore historical drug sales data, identify trends, compare sales performance across drug categories and brands, and visualize insights through charts and graphs.

Project URL: https://roadmap.sh/projects/pharmaceutical-sales-data

---

## Objectives

The analysis answers the following business questions:

* What are the total sales quantities for each drug category (ATC code)?
* Which individual drug brands have the highest total sales?
* Which three drugs have the highest sales in January 2015, July 2016, and September 2017?
* Which drug sold the most frequently in 2017?
* Which drug category has the highest average daily sales?
* Are respiratory drugs (R03) sold more during specific months?

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Project Structure

Analysing-pharmaceutical-sales-data/

├── data/

│── salesdaily.csv

├── pharmaceutical_sales_analysis.ipynb

├── README.md

└── requirements.txt

---

## Dataset

The dataset used in this project is the pharmaceutical sales dataset available on Kaggle.

Place the downloaded dataset inside the `data` folder:

data/salesdaily.csv

---

## Installation

1. Clone the repository

git clone <repository-url>

cd Analysing-pharmaceutical-sales-data

2. Create a virtual environment (optional)

python -m venv venv

3. Activate the environment

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

---

## Requirements

requirements.txt

pandas

numpy

matplotlib

jupyter

Install all dependencies:

pip install -r requirements.txt

---

## Analysis Performed

### Data Preparation

* Loaded CSV dataset using Pandas
* Converted date columns to datetime format
* Checked for missing values
* Performed data cleaning and preprocessing

### Sales Analysis

* Total sales by ATC category
* Top-selling drug brands
* Monthly and yearly sales comparisons
* Drug sales ranking for selected periods
* Average daily sales calculations

### Visualization

* Bar charts
* Line plots
* Monthly trend analysis
* Category-wise sales comparison

---

## Key Insights

* Identified top-performing drug categories
* Determined the highest-selling drug brands
* Analyzed seasonal demand patterns for respiratory drugs (R03)
* Compared monthly and yearly sales performance
* Evaluated average daily sales across categories

---

## Learning Outcomes

Through this project, I learned:

* Data cleaning and preprocessing with Pandas
* Data aggregation and grouping techniques
* Time-series analysis
* Exploratory Data Analysis (EDA)
* Creating visualizations using Matplotlib
* Extracting business insights from real-world datasets

---

## Author

Amrit Raj

B.Tech Mechanical Engineering

Aspiring Data Analyst

---

## Acknowledgements

* roadmap.sh

* Kaggle

* Pandas Documentation

* Matplotlib Documentation

* Python Community

This project was completed as part of the roadmap.sh Data Analysis Projects series.
