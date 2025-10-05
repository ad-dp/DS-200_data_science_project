# DS200 Assignment: Data Science Visualization Project  

This repository contains a data analysis and visualization project created as part of the **DS200: Data Science Visualization** assignment.  
It use datasets from [data.gov.in](https://data.gov.in) and demonstrate **data cleaning, exploratory data analysis (EDA), and visualization** using Python (`pandas`, `matplotlib`, and `seaborn`).

---

## Analysis of R&D Expenditure by Economic Activity  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qXXDXvaHxsZlkXd8hXsSXnbWVJEFKYnG?usp=sharing)
### Overview  
This project analyzes **Research & Development (R&D) expenditure** across various economic sectors in India for the fiscal years **2018–19, 2019–20, and 2020–21**.  
It identifies key trends, top-spending sectors, and the inequality in national R&D investment.

**Data Source:** [R&D Expenditure by Economic Activity – data.gov.in](https://data.gov.in/)

---

### Project Structure  

```
rd-expenditure-analysis/
├── rd_analysis_colab.py
├── rd_bar_chart.png
├── rd_box_plot.png
├── rd_scatter_plot.png
└── readme.md
```

---


---

### Observations and Inferences  

#### 1. R&D Expenditure (2018–19 vs. 2019–20)
**Observation:** Most sectors lie close to the *y = x* line with a slight upward drift; one dominant outlier stands out.  
**Inference:** Overall spending increased between years, with the *Professional, Scientific and Technical Activities* sector dominating.

#### 2. Distribution of R&D Expenditure (2018–2021)
**Observation:** Data is highly right-skewed, showing a few sectors with very high spending.  
**Inference:** R&D investment is heavily concentrated in select industries, revealing inequality in innovation funding.

#### 3. Top 10 Sectors by Expenditure (2020–21)
**Observation:** The *Professional, Scientific and Technical Activities* sector far outspends all others, followed by *Agriculture* and *Health*.  
**Inference:** National priorities favor scientific and technical R&D, with notable emphasis on agriculture and healthcare.

---

Citations

Government of India. R&D Expenditure by Economic Activity (2018–2021). data.gov.in







