# 🌍 Global Happiness Report Analysis

A clean Python data analysis project exploring happiness across countries and its relationships with GDP per capita, social support, and healthy life expectancy.

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Analysis
- Dataset exploration and data-quality checks
- Top 10 happiest countries
- Bottom 10 countries
- Social Support vs Happiness
- Healthy Life Expectancy vs Happiness
- GDP per Capita vs Happiness
- Correlation matrix and heatmap
- Key findings and exported results

## Project Structure
```text
Global-Happiness-Report-Analysis/
├── README.md
├── data/
│   └── Global_Happiness_Report.csv
├── notebook/
│   └── Global_Happiness_Report_Analysis.ipynb
└── output/
    ├── top_10_happiest_countries.png
    ├── bottom_10_countries.png
    ├── social_support_vs_happiness.png
    ├── healthy_life_expectancy_vs_happiness.png
    ├── gdp_vs_happiness.png
    ├── happiness_correlation_heatmap.png
    ├── top_10_happiest_countries.csv
    ├── bottom_10_countries.csv
    └── happiness_correlation_matrix.csv
```

## How to Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```
Open `notebook/Global_Happiness_Report_Analysis.ipynb`.

## Assumptions & Limitations
Correlation describes association, not causation. Results depend on the supplied dataset version, and missing values are excluded where required.

**Author:** Shyam Gor
