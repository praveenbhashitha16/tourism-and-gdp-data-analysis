# Tourism and GDP Data Analysis

## Project Overview

This project focuses on data cleaning, preprocessing, and integration of tourism arrivals and GDP per capita datasets.

The main objective is to prepare a clean and integrated dataset for further analysis by combining tourism and economic indicators from different data sources.

The analysis covers the common period from 2011 to 2024.

## Project Objectives

- Inspect and understand the original datasets.
- Identify and handle missing values.
- Detect and investigate outliers.
- Perform data cleaning and transformation.
- Integrate multiple datasets using common columns.
- Perform exploratory data analysis (EDA).
- Create visualizations to understand data patterns.

## Datasets

This project uses two datasets:

1. **Tourist Arrivals Dataset** – Contains information about tourist arrivals by country and year.
2. **GDP per Capita Dataset** – Contains GDP per capita information by country and year.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Loading and Inspection
2. Data Cleaning
3. Missing Value Handling
4. Outlier Detection and Investigation
5. Data Transformation
6. Data Integration
7. Exploratory Data Analysis
8. Data Visualization

## Data Integration

The two datasets were integrated using the common columns:

- Country
- Year

An inner join was used to retain matching country-year records from both datasets.

## Visualizations

The project includes:

- Boxplots for outlier investigation.
- Histograms for understanding data distributions.
- Time-series visualizations.
- Scatter plots for exploring relationships between tourism arrivals and GDP per capita.

## Final Output

The final output is a clean and integrated CSV dataset containing:

- Country
- Year
- Tourist Arrivals
- GDP per Capita

The final dataset covers the common period from 2011 to 2024.

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook in the `notebooks` folder.
4. Run the notebook cells to reproduce the data cleaning and integration process.

## Repository Structure

```text
Tourism_and_GDP_Data_Analysis/
│
├── Cleaned_Data/
│   ├── GDP_Cleaned.csv
│   ├── GDP_Tourism_Cleaned.csv
│   └── Tourism_Cleaned.csv
│
├──  GDP_and_Tourist_Arrivals_Data_Management.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Author

Praveen Bhashitha

BSc in Applied Data Analytics
University of Colombo
