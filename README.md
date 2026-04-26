# Socio-Economic-Analysis-of-Employability-in-England-and-Wales-2011-2021-
This project provides a data-driven analysis of how socio-economic factors like gender, education, and geography—influenced the labour market in England and Wales over a ten-year period. 
Utilizing UK Census data, this project was developed as part of a technical study at the University of Bristol, focusing on high-end data visualization and statistical forecasting.

This repository contains a single, multi-story Tableau workbook. Below is a description of the key visual components based on the project's analysis.

1. **Regional Employment Comparison** (Choropleth Maps)
Description: This dashboard utilizes side-by-side geographic maps to compare employment and unemployment rates across Local Authority Districts (LADs) between 2011 and 2021.
Insight: It visually highlights the "London Hub" and its surrounding areas as consistently high-performing economic zones compared to other regions.

2. **Gender & Economic Activity Disparity**
Description: A stacked bar chart analysis comparing the economic activity of males vs. females.
Insight: Highlights a significant gender gap in the "Economically Inactive" category, specifically those "looking after home or family," which accounted for 9.77% of the 2011 population (heavily skewed toward females).

3. **Principal Component Analysis (PCA)**
Description: This visualization represents the variance in educational qualifications across regions.
Insight: By reducing the dimensions of the data, we can see how different regions (like London vs. the North East) cluster based on their level of degree-attainment and skill sets.

4. **t-SNE Dimensionality Reduction**
Description: A t-Distributed Stochastic Neighbor Embedding (t-SNE) plot used to visualize high-dimensional labour market data.
Insight: This non-linear technique groups Local Authorities with similar labour profiles, allowing for a more nuanced understanding of regional economic "personalities."

5. **Educational Qualification Trends**
Description: Horizontal bar charts tracking the growth of Level 4 (Degree or higher) qualifications across 10 major regions.
Insight: Demonstrates that while Level 4 qualifications grew across the board (reaching 3.3M in London by 2021), the population with "No Qualifications" remained largely stagnant, indicating a persistent educational divide.

6. **Forecast & Statistical Distribution**

Description: Detailed views of the statistical distributions and the Bayesian logit-linear regression model.
Insight: These views support the end-to-end application of Tamara Munzner's Task Taxonomy, moving from raw data to predictive insights.



## Technical Framework

> Visualization: Tableau (Packaged Workbook .twbx)

> Methodology: Tamara Munzner’s Task Taxonomy (Data/Task Abstraction and Idiom design).

> Advanced Analytics: PCA, t-SNE, and Bayesian Logit-Linear Regression.

> Data Sources: Office for National Statistics (ONS) / Nomis UK Census data (2011 & 2021).
