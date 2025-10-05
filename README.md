Data Science Projects: India Sectoral Analysis
This repository contains two distinct data analysis projects focusing on different sectors in India. Each project uses Python for exploratory data analysis and visualization.

Project 1: Analysis of R&D Expenditure by Economic Activity
Project Overview
This project analyzes the Research & Development (R&D) expenditure across various economic sectors in India for the fiscal years 2018-19, 2019-20, and 2020-21. The goal is to identify trends, top-spending sectors, and the overall distribution of R&D investment.

Data Source
The dataset used is the sector-wise R&D expenditure data.

Source: India's Open Government Data (OGD) Platform

Website: data.gov.in

Citation (example format):

Department of Science and Technology, Government of India. (2022). Research & Development Expenditure by Economic Activity. Retrieved from data.gov.in.

Files for this Project
rd_analysis_colab.py: Python script for analysis.

rd_scatter_plot.png: Scatter plot comparing 2018-19 and 2019-20 R&D expenditure.

rd_box_plot.png: Box plot showing the distribution of expenditure across three years.

rd_bar_chart.png: Bar chart of the top 10 sectors by R&D expenditure in 2020-21.

Observations and Analysis from Plots
1. Scatter Plot: R&D Expenditure (2018-19 vs. 2019-20)
Observation: Most data points cluster near the y=x reference line, with a significant outlier in the top right. Many points lie slightly above the line, while a few are below it.

Analysis: The powerful outlier represents the "Professional, Scientific and Technical Activities" sector, which dominates R&D spending. The general trend of points above the line indicates that R&D spending increased for most sectors from 2018-19 to 2019-20. The few points below the line show sectors with decreased spending.

2. Box Plot: Distribution of R&D Expenditure (2018-2021)
Observation: The box plots for all three years are highly skewed, with the median (the line inside the box) very close to the bottom. The whiskers and outlier points extend far upwards, indicating a vast range in spending.

Analysis: This plot clearly illustrates the massive inequality in R&D spending. A few sectors spend exceptionally large amounts, while the majority of sectors spend very little, pulling the median down. This highlights a concentration of R&D investment in a small number of key areas.

3. Bar Chart: Top 10 Sectors by R&D Expenditure (2020-21)
Observation: The "Professional, Scientific and Technical Activities" sector's expenditure is dramatically higher than any other sector. "Agriculture, Forestry and Fishing" is a distant second, followed by sectors like "Human Health" and "Electricity, Gas, Steam."

Analysis: This chart confirms the dominance of the scientific/technical sector in national R&D efforts. It provides a clear ranking of which areas receive the most investment, which is crucial for understanding national priorities and economic focus.

Project 2: Analysis of Indian School Education Performance Data
Project Overview
This project performs a basic exploratory data analysis (EDA) on the Performance Grading Index for Districts (PGI-D) data for India. The goal is to load, clean, and visualize key performance indicators to understand the distribution of educational scores across various states, districts, and grades.

The analysis is conducted using Python with the Pandas library for data manipulation and Matplotlib for generating visualizations.

Data Source
The dataset used in this analysis is the Performance Grading Index for Districts (PGI-D), which assesses the performance of the school education system at the district level.

Source: India's Open Government Data (OGD) Platform

Website: data.gov.in

Citation (example format):

Department of School Education & Literacy, Ministry of Education, Government of India. (2024). Performance Grading Index for Districts (PGI-D). Retrieved from data.gov.in.

Files for this Project
education_analysis_colab.py: The main Python script used for data loading, cleaning, analysis, and visualization in a Google Colab environment.

scatter_plot.png: A scatter plot showing the relationship between 'Overall' scores and 'Outcome' scores.

box_plot.png: A box plot comparing the distribution of 'Overall' scores across different grade categories.

bar_chart.png: A horizontal bar chart displaying the top 15 states by average 'Overall' score.

Observations and Analysis from Plots
1. Scatter Plot: Overall Score vs. Outcome Score
Observation: The plot shows a strong, positive, and linear relationship between the 'Overall' score and the 'Outcome' score. As the 'Outcome' score increases, the 'Overall' score increases proportionally.

Analysis: This strong correlation is expected, as the 'Outcome' score is a significant component of the total 'Overall' score. This visualization helps confirm the consistency of the data; a district that performs well in the 'Outcome' category almost always has a high overall score.

2. Box Plot: Distribution of Overall Scores by Grade
Observation: The distribution of 'Overall' scores varies significantly across the different grade classifications (e.g., 'Uttam', 'Prachesta', 'Akanshi'). Higher-tier grades like 'Uttam-2' and 'Uttam-3' not only have a higher median score but also show a wider range of scores, as indicated by the larger interquartile range (the size of the box). Lower-tier grades like 'Prachesta-3' have lower median scores and are clustered more tightly.

Analysis: This plot effectively segments the performance of districts. The 'Grade' is a reliable indicator of the general performance range. For instance, nearly all 'Uttam' graded districts outperform the 'Prachesta' graded districts. This visualization is excellent for understanding the performance benchmarks associated with each grade.

3. Bar Chart: Top 15 States by Average Overall Score
Observation: The bar chart highlights that Punjab, Chandigarh, and Rajasthan have the highest average 'Overall' scores across their districts among the states shown. There is a noticeable drop-off in the average score after the top few states.

Analysis: This provides a high-level administrative overview of state-level performance. While it's useful for comparison, it's important to remember that these are averages. A state with a high average score may still have underperforming districts. This chart is a starting point for a more granular, district-level investigation.

How to Run the Analysis
Clone this repository to your local machine.

Open the relevant Python script (rd_analysis_colab.py or education_analysis_colab.py) in a Google Colab notebook.

Upload the source CSV data file to your Colab session.

Update the file_path variable in the script to match the name of your uploaded file.

Run the cells in the notebook to perform the analysis and regenerate the plots.