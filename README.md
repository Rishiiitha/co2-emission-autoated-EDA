# co2-emission-autoated-EDA
📊 Automated EDA on Tech Layoffs Dataset
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and feature engineering on the tech_layoffs.csv dataset. The goal is to understand patterns in layoffs across companies, industries, and time, and to prepare the dataset for further modeling or visualization.

⚙️ Steps Performed

Data Loading

Imported the dataset using pandas.

Displayed dataset shape and sample records.

Automated EDA

Used ydata_profiling to generate an interactive EDA report (tech_layoffs_report.html).

Manual Quick EDA

Checked missing values.

Generated summary statistics.

Plotted distributions of numeric columns (e.g., layoffs).

Created a correlation heatmap.

Feature Engineering

Converted date column into year, month, and quarter.

Categorized layoffs into Small, Medium, Large, Massive groups.

Applied one-hot encoding to categorical variables (e.g., industry, country).

📂 Files

tech_layoffs.csv → Raw dataset.

tech_layoffs_report.html → Automated profiling report.

eda_script.py or notebook.ipynb → Python script/Jupyter Notebook with code.

🚀 How to Run

Install dependencies:

pip install pandas matplotlib seaborn ydata-profiling


Run the notebook or script:

python eda_script.py


Open tech_layoffs_report.html in a browser to explore the full EDA report.

📈 Insights You Can Explore

Which industries faced the most layoffs?

Which year/quarter had peak layoffs?

Correlation between company size, industry, and number of layoffs.

Severity of layoffs across companies and regions.

🛠️ Next Steps

Handle missing values more rigorously (imputation or dropping).

Normalize or scale numeric features for modeling.

Perform time series trend analysis.

Train ML models to predict layoff severity based on features.