
# India Unemployment Rate Analysis | COVID-19 Impact Study

## Project Overview

This project explores unemployment trends in India and examines how the COVID-19 pandemic and associated lockdown measures affected the country's labour market.

Using historical unemployment datasets, the analysis investigates changes in unemployment rates across different regions, compares urban and rural unemployment patterns, and identifies significant variations during the pandemic period.

The project was completed as part of the CodeAlpha Data Science Internship.

## Project Objectives

The main objectives of this project are to:

- Explore historical unemployment trends in India.
- Examine changes in unemployment rates during the COVID-19 pandemic.
- Compare unemployment patterns across Indian states and regions.
- Analyse differences between urban and rural unemployment.
- Identify unusual changes, regional variations and potential patterns.
- Communicate findings through meaningful data visualisations.

## Dataset

The project uses two datasets:

1. `Unemployment in India.csv`
2. `Unemployment_Rate_upto_11_2020.csv`

The datasets contain unemployment-related information, including geographical regions, dates, estimated unemployment rates and labour market indicators.

The data is used to investigate unemployment patterns across different locations and periods.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook
- Anaconda

## Data Analysis Methodology

### 1. Data Loading and Inspection

The datasets were imported using Pandas. Initial inspection was performed to understand their structure, column names, data types and general characteristics.

### 2. Data Cleaning and Preprocessing

The datasets were examined and prepared for analysis. This involved handling data-quality issues, standardising relevant fields and preparing date-related information for comparison.

### 3. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand unemployment distributions, identify unusual observations and examine relationships between geographical and time-related variables.

### 4. COVID-19 Impact Analysis

The analysis examined unemployment patterns around the COVID-19 lockdown period, highlighting changes in labour market conditions during the pandemic.

### 5. Regional and Urban-Rural Analysis

Unemployment patterns were compared across states and regions, including differences between urban and rural areas.

### 6. Data Visualisation

Visualisations were created to communicate important patterns, regional differences and changes over time.

## Key Areas of Analysis

- Overall unemployment trends.
- COVID-19 lockdown impact.
- State-wise unemployment differences.
- Regional unemployment variations.
- Urban versus rural unemployment.
- Monthly and time-based patterns.

## Key Findings

The analysis highlights substantial changes in India's unemployment patterns during the COVID-19 period.

It also reveals differences in unemployment rates across geographical regions and between urban and rural areas.

These findings demonstrate the importance of examining economic data across different time periods and population groups rather than relying only on national averages.

## Business and Policy Relevance

The findings can help researchers, policymakers and economic analysts better understand labour market disruptions.

Regional unemployment analysis can support the identification of vulnerable areas, while urban-rural comparisons provide additional context for employment policy and economic recovery planning.

## Project Structure

```text
CodeAlpha_Unemployment_Analysis/
│
├── CodeAlpha_Unemployment_Analysis.ipynb
├── Unemployment in India.csv
├── Unemployment_Rate_upto_11_2020.csv
└── README.md
```

## How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook.

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### Steps

1. Clone the repository:

```bash
git clone https://github.com/Bwalii/CodeAlpha_Unemployment_Analysis.git
```

2. Navigate into the project directory:

```bash
cd CodeAlpha_Unemployment_Analysis
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `CodeAlpha_Unemployment_Analysis.ipynb`.

5. Run the notebook cells sequentially.

Ensure that the dataset files are available in the project directory.

## Limitations

- The analysis relies on historical datasets and does not represent current unemployment conditions.
- The findings describe patterns and associations; they do not independently establish that COVID-19 was the sole cause of every observed change.
- The quality of the findings depends on the coverage and accuracy of the original datasets.

## Future Improvements

- Extend the analysis using more recent labour market datasets.
- Develop interactive dashboards using Streamlit.
- Explore unemployment forecasting using time-series models.
- Incorporate additional economic indicators for deeper analysis.

## Internship Information

This project was completed as part of the CodeAlpha Data Science Internship.

## Author

**Mubarak Bashir Wali**

- GitHub: [Bwalii](https://github.com/Bwalii)
- Project: [Unemployment Analysis](https://github.com/Bwalii/CodeAlpha_Unemployment_Analysis)

## Acknowledgements

Thanks to CodeAlpha for providing the opportunity to work on practical Data Science tasks and strengthen my skills in Python, data analysis and visualisation.
