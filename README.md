University Rankings Data Analysis

This repository contains a data analysis project focused on understanding factors that influence university rankings and scores. The analysis uses Python with libraries such as pandas, matplotlib, and scikit-learn to explore and visualize a dataset of university rankings.

Project Overview

The main goal of this project is to analyse the relationship between various university attributes (e.g., teaching quality, research, international student ratio) and their impact on overall scores and citation index. The analysis includes:

Data Cleaning: Handling missing values and removing duplicates from the dataset.

Descriptive Analysis: Visualising the number of universities per country to identify the top countries represented in the dataset.

Correlation Analysis: 

- Examining the correlation between teaching quality and the ratio of international students.
- Investigating the strong correlation between teaching quality and research quality.
- Exploring the relationship between research quality and citations.

Multiple Linear Regression:
- Building a 3D linear regression model to predict the Citations Index based on Teaching Quality and Research Quality. The analysis shows that Research Quality has a much larger impact than Teaching Quality on citations.
- Creating another 3D linear regression model to predict the Total Score of an institution based on Teaching Quality and Research Quality. The results indicate that these two factors explain a significant portion of the variance in the total score.

Tools and Libraries

The following Python libraries were used for this project:
- Pandas: For data manipulation and analysis.
- Matplotlib: For creating static, animated, and interactive visualizations.
- Scipy: Used for linear regression to find correlations.
- Scikit-learn: For building the multiple linear regression models.
- Numpy: For numerical operations, especially in creating grids for the 3D plots.
- Mpl_toolkits.mplot3d: For creating the 3D scatter plots.

Analysis Results

Key Findings:

- Research vs. Citations: Research Quality has a significantly greater impact on the Citation Index compared to Teaching Quality (R-squared = 0.28).
- Teaching & Research vs. Total Score: Teaching and Research scores together account for a very high percentage of the variance in the Total Score (R-squared = 0.86), showing their significant influence.
- Country Representation: The analysis identified the top countries with the most universities in the dataset, with the United States and the United Kingdom having a high number of ranked institutions.
