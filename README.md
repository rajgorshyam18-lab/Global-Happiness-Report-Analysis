🌍 Global Happiness Report Analysis

«A Python-based data analysis and visualization project exploring global happiness rankings, life evaluation, social support, healthy life expectancy, and selected happiness-related factors.»

---

📌 Project Overview

Happiness is an important measure of people's overall life satisfaction and wellbeing. Different countries show different levels of life evaluation, which can be explored using data from the Global Happiness Report.

This project analyzes Global Happiness Report data using Python to understand patterns in happiness across countries and explore relationships between life evaluation and selected explanatory factors.

The project includes:

- 🌍 Country-wise happiness analysis
- 🏆 Top 10 happiest countries
- 📉 Bottom 10 countries by happiness
- 🤝 Social support vs happiness
- ❤️ Healthy life expectancy vs happiness
- 🔗 Correlation analysis
- 🧹 Data-quality checks
- 📊 Data visualization

The project demonstrates how Python can be used to load, explore, analyze, and visualize a real-world dataset.

---

🎯 Objectives

The main objectives of this project are:

1. Understand and explore the Global Happiness Report dataset.
2. Examine the structure, columns, and dimensions of the dataset.
3. Check the dataset for missing values and duplicate records.
4. Analyze happiness rankings across countries.
5. Identify the Top 10 happiest countries in the latest analyzed year.
6. Identify the Bottom 10 countries by life evaluation.
7. Explore the relationship between social support and happiness.
8. Explore the relationship between healthy life expectancy and happiness.
9. Examine correlations between selected happiness-related factors.
10. Create meaningful visualizations using Python.
11. Understand and communicate observations from the data.
12. Understand the difference between correlation and causation.

---

📂 Dataset

Dataset: Global Happiness Report

The project uses country-level Global Happiness Report data covering multiple years.

Dataset Information

- Rows: 1,969
- Columns: 13
- Year Range: 2011 – 2024
- Main Happiness Measure: Life evaluation (3-year average)

Main Variables

The dataset contains variables related to:

- Year
- Rank
- Country name
- Life evaluation (3-year average)
- Lower whisker
- Upper whisker
- Log GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Dystopia + residual

The main happiness measure used in the project is Life evaluation (3-year average).

---

🛠️ Technologies & Libraries

Technology| Purpose
🐍 Python| Programming and data analysis
🐼 Pandas| Data loading, manipulation, filtering and analysis
🔢 NumPy| Numerical operations
📊 Matplotlib| Data visualization
🎨 Seaborn| Statistical and exploratory visualization
📓 Jupyter Notebook| Project development and analysis

---

🔍 Analysis Performed

1. Data Exploration

The dataset was initially explored to understand:

- Dataset dimensions
- Column names
- Data types
- Available years
- Country information
- Main analytical variables
- Overall dataset structure

---

2. Data Quality Checks

Basic data-quality checks were performed before the main analysis.

The notebook checks:

- Missing values
- Duplicate records
- Dataset structure and consistency

These checks help identify common data-quality issues before performing analysis.

---

3. Top 10 Happiest Countries

The latest analyzed year was used to identify the Top 10 countries by life evaluation.

A horizontal bar chart was created to compare the happiness scores of these countries.

Purpose:
To understand which countries are ranked highest according to the selected life-evaluation measure.

---

4. Bottom 10 Countries by Happiness

The Bottom 10 countries by life evaluation were identified for the latest analyzed year.

A bar chart was created to compare their happiness scores.

Purpose:
To examine countries at the lower end of the happiness ranking.

---

5. Social Support vs Happiness

A scatter plot was created to explore the relationship between:

- Social support
- Life evaluation

Each observation represents a country from the selected analysis year.

Purpose:
To visually examine how social support and life evaluation are distributed together.

---

6. Enhanced Social Support Visualization

An enhanced scatter plot was created for the social-support analysis.

Additional visual encoding was used to make differences between observations easier to explore.

Purpose:
To provide a richer visualization of the relationship between social support and life evaluation.

---

7. Healthy Life Expectancy vs Happiness

A scatter plot was created to explore:

- Healthy life expectancy
- Life evaluation

Additional visual encoding was used in the visualization.

Purpose:
To examine how healthy life expectancy and reported life evaluation appear together across countries.

---

8. Correlation Analysis

A correlation heatmap was created to examine statistical relationships between selected happiness-related numerical variables.

The heatmap provides a visual summary of the relationships between the selected variables.

«Important: Correlation represents statistical association. It does not prove that one variable causes another.»

---

📊 Visualizations

The project contains six main visual stories:

1. 🏆 Top 10 Happiest Countries

A horizontal bar chart showing the Top 10 countries by life evaluation.

2. 📉 Bottom 10 Countries by Happiness

A bar chart showing the Bottom 10 countries by life evaluation.

3. 🤝 Social Support vs Happiness

A scatter plot comparing social support with life evaluation.

4. 🎨 Enhanced Social Support vs Happiness

An enhanced scatter plot providing additional visual information.

5. ❤️ Healthy Life Expectancy vs Happiness

A scatter plot comparing healthy life expectancy with life evaluation.

6. 🔗 Correlation Between Happiness and Key Factors

A heatmap showing correlations between selected numerical variables.

---

💡 Key Findings

The analysis provides the following broad observations:

- Happiness levels differ between countries.
- The Top 10 and Bottom 10 visualizations clearly show differences in reported life evaluation.
- Social support and life evaluation can be explored together using scatter plots.
- Healthy life expectancy provides another dimension for examining country-level life evaluation.
- Enhanced visualizations can communicate more information than a basic two-variable plot.
- The correlation heatmap provides a broader view of relationships between selected happiness-related variables.
- Different chart types help communicate different aspects of the dataset.

«Note: These are exploratory observations from the dataset and visualizations. The project does not claim that any particular factor directly causes happiness.»

---

⚠️ Assumptions & Limitations

Assumptions

- The provided Global Happiness Report dataset was used as the source for the analysis.
- Life evaluation was used as the primary measure of happiness.
- The latest analyzed year was used for the main country-ranking visualizations.
- Missing-value and duplicate checks were performed before the main analysis.
- Correlation was used as an exploratory measure of statistical association.

Limitations

- Correlation does not imply causation.
- The dataset contains country-level observations and should not automatically be interpreted as individual-level behaviour.
- Life evaluation is based on reported assessments and does not represent every aspect of wellbeing.
- The main happiness measure is a 3-year average.
- The analysis focuses on selected explanatory factors available in the dataset.
- The main country-ranking visualizations focus on the latest analyzed year rather than providing a complete year-by-year analysis of every country.

---

📁 Project Structure

Global-Happiness-Report-Analysis/
│
├── 📓 Global_Happiness_Report_Analysis.ipynb
├── 📄 README.md
│
└── 📊 dataset/
    └── Global Happiness Report dataset

---

▶️ How to Run the Project

1. Download or clone the project

Download the project files or clone the repository.

2. Install the required libraries

pip install pandas numpy matplotlib seaborn jupyter

3. Place the dataset

Place the Global Happiness Report dataset in the dataset folder used by the notebook.

4. Open Jupyter Notebook

jupyter notebook

5. Open the project notebook

Open:

Global_Happiness_Report_Analysis.ipynb

6. Run the notebook

Run the cells from top to bottom to reproduce the analysis and visualizations.

---

📚 What I Learned From This Project

This project helped me practice several important Python and Data Analytics concepts.

Python

I practiced using Python for real-world data analysis.

Pandas

I practiced:

- Loading data
- Exploring DataFrames
- Selecting columns
- Filtering data
- Sorting data
- Performing basic analysis

Data Quality

I learned the importance of checking data for:

- Missing values
- Duplicate records
- Structural issues

before beginning the main analysis.

Data Visualization

I practiced using different visualization techniques depending on the analytical question:

- Bar charts for rankings
- Scatter plots for relationships
- Enhanced scatter plots for additional information
- Heatmaps for correlation analysis

Exploratory Data Analysis

The project helped me understand how to explore a dataset and identify useful patterns without making unsupported conclusions.

Analytical Thinking

One of the main lessons from this project is:

«A chart should answer a question, not simply display data.»

---

🚀 Data Anaylst

This project is one step in my journey toward becoming a Data Analyst.

I want to continue improving my skills in Python, data analysis, visualization, statistics, SQL, and business analytics by working on practical projects and real-world datasets.

My aim is to become better at understanding data, finding meaningful patterns, and presenting insights in a clear and useful way.

---

📌 Conclusion

This project demonstrates how Python can be used to explore a real-world Global Happiness Report dataset and transform the data into meaningful visualizations.

The analysis covers country-level happiness rankings, social support, healthy life expectancy, and relationships between selected happiness-related factors.

The project also helped me practice the basic workflow of data analysis:

Data → Exploration → Data Quality → Analysis → Visualization → Findings

This project has helped me strengthen my practical understanding of Python, Pandas, data visualization, exploratory analysis, and analytical thinking.

---

👨‍💻 Author

Shyam Gor

I am currently learning Data Analytics and developing my practical skills through projects based on real-world datasets.

I am interested in:

- 📊 Data Analytics
- 🐍 Python
- 🐼 Pandas
- 📈 Data Visualization
- 🔎 Exploratory Data Analysis
- 📉 Statistics
- 💼 Business Analytics
- 🧠 Analytical Thinking

I believe practical projects are an important part of learning because they provide an opportunity to apply programming and analytical concepts to real datasets.

This Global Happiness Report project is one of my learning projects, where I practiced data exploration, data-quality checking, analysis, visualization, and interpretation using Python.

🎓 Current Learning Focus

I am currently building my foundation in:

Python • Data Analysis • Pandas • Data Visualization • Statistics • SQL • Business Analytics

My goal is to continue improving my analytical and technical skills by working on more practical projects and learning how to turn data into useful information.

---

🙏 Acknowledgement

I would like to acknowledge the Global Happiness Report dataset used for this educational analysis.

This project was created for learning and academic purposes as part of my Python and Data Analytics learning journey.

---

⭐ Project Summary

Project: Global Happiness Report Analysis
Author: Shyam Gor
Language: Python
Environment: Jupyter Notebook
Libraries: Pandas • NumPy • Matplotlib • Seaborn
Project Type: Exploratory Data Analysis & Data Visualization

---

⭐ Thank You

Thank you for taking the time to review my project.

Working on this project gave me an opportunity to apply what I have learned in Python and Data Analytics to a real-world dataset.

I hope to continue learning new concepts, working on practical projects, and improving my skills step by step.

---
