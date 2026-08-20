# Unemployment Analysis with Python

## 📌 Project Overview

This project analyzes unemployment data in India using Python.

The project focuses on data cleaning, exploratory data analysis, visualization, unemployment trends, regional differences, and the impact of COVID-19 on unemployment rates.

## 🎯 Objective

The main objectives of this project are:

* Analyze unemployment rates across different regions of India.
* Clean and explore unemployment data.
* Identify regions with high and low unemployment rates.
* Analyze unemployment trends over time.
* Study the impact of COVID-19 on unemployment.
* Identify important patterns in the unemployment data.
* Present the findings using data visualization.

## 📊 Dataset

The dataset used in this project is:

**Unemployment in India.csv**

The dataset contains **740 records and 7 columns**.

The main attributes are:

* Region
* Date
* Frequency
* Estimated Unemployment Rate (%)
* Estimated Employed
* Estimated Labour Participation Rate (%)
* Area

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab / Jupyter Notebook

## 🔄 Project Workflow

1. Load the unemployment dataset.
2. Explore the dataset.
3. Check the dataset structure.
4. Check for missing values.
5. Clean column names and text values.
6. Convert the date column into the appropriate format.
7. Convert numerical columns into numeric data types.
8. Calculate the average unemployment rate.
9. Analyze unemployment rates by region.
10. Identify regions with the highest and lowest unemployment.
11. Analyze unemployment trends over time.
12. Analyze employment and labour participation.
13. Create charts and visualizations.
14. Analyze the COVID-19 period.
15. Present the final findings.

## 📈 Analysis Results

Based on the uploaded dataset:

* **Total Records:** 740
* **Total Columns:** 7
* **Average Unemployment Rate:** 11.79%
* **Highest Average Unemployment:** Tripura — 28.35%
* **Lowest Average Unemployment:** Meghalaya — 4.80%

### Top 5 Regions by Average Unemployment Rate

| Rank | Region           | Average Unemployment Rate |
| ---: | ---------------- | ------------------------: |
|    1 | Tripura          |                    28.35% |
|    2 | Haryana          |                    26.28% |
|    3 | Jharkhand        |                    20.58% |
|    4 | Bihar            |                    18.92% |
|    5 | Himachal Pradesh |                    18.54% |

## 📊 Visualizations

The project includes the following visualizations:

### 1. Top 10 Regions by Unemployment Rate

A bar chart is used to compare the average unemployment rate across the regions with the highest rates.

### 2. Unemployment Trend Over Time

A line graph is used to analyze how the unemployment rate changed over time.

### 3. Employment Analysis

A bar chart compares the estimated employment levels across regions.

### 4. Labour Participation Analysis

The project analyzes labour participation rates across different regions.

### 5. Correlation Analysis

A correlation analysis is performed between:

* Unemployment Rate
* Estimated Employed
* Labour Participation Rate

## 🦠 COVID-19 Impact

The unemployment trend is analyzed during the COVID-19 period.

The dataset shows a significant increase in unemployment during 2020, particularly around the April–June period, followed by a decline.

This visualization helps demonstrate how unemployment changed during the COVID-19 period.

## 💡 Key Insights

* Unemployment rates vary considerably between regions.
* Tripura recorded the highest average unemployment rate in this dataset.
* Meghalaya recorded the lowest average unemployment rate.
* The unemployment rate increased significantly during parts of 2020.
* Employment and labour participation indicators provide additional information for understanding unemployment patterns.

## 📁 Project Structure

```text
CodeAlpha_UnemploymentAnalysis/
│
├── Unemployment in India.csv
├── unemployment_analysis.py
├── README.md
└── screenshots/
```

## ▶️ How to Run

### Step 1: Install required libraries

```bash
pip install pandas numpy matplotlib
```

### Step 2: Keep the files together

```text
Unemployment in India.csv
unemployment_analysis.py
README.md
```

### Step 3: Run the Python program

```bash
python unemployment_analysis.py
```

The program will display the analysis results and generate the required visualizations.

## 🏁 Conclusion

This project demonstrates how Python can be used for unemployment data analysis.

Through data cleaning, exploratory analysis, statistical calculations, and visualization, the project identifies regional unemployment differences and examines changes in unemployment over time, including the COVID-19 period.

## 👩‍💻 Internship Details

**Organization:** CodeAlpha

**Domain:** Data Science

**Task:** Unemployment Analysis with Python
