# An Analysis of the Palmer Penguins Data Set
## Principles of Data Analytics
**By A. O'Connor**
*********
<p align ="center"><img src="https://allisonhorst.github.io/palmerpenguins/logo.png" /></p>

*********

## Introduction 
This git repository contains a [jupyter notebook](https://github.com/a-o-connor/palmerpenguins_data_analytics/blob/main/palmerpenguinsanalysis.ipynb) with my analysis of the Palmer Penguins data set.
The data set is available [on Git Hub](https://allisonhorst.github.io/palmerpenguins/articles/intro.html).
The Palmer Penguins data set contains size data gathered for three species of penguin in the Palmer Achipelago in Antarctica. It is often used as a training data set for introductory statistics and data science.
## About this project
This repository contains a jupyter notebook with my own analysis of the Palmer Penguins data set, for the purposes of the Principles of Data Analytics module I am taking as part of a course in Computer Science at ATU. The aim of this analysis is to provide a coherent overview of the large, multivariate Palmer Penguins data set, enabling a deeper understanding of the biology of the penguin population in the Palmer Archipelago in Antarctica. 
## Get Started
To get started with this project, you can open the notebook in Google Colab by clicking on the link below:\
<a target="_blank" href="https://colab.research.google.com/github/a-o-connor/palmerpenguins_data_analytics/blob/main/palmerpenguinsanalysis.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
\
The notebook is written in Python. A number of statistics modules are used throughout the notebook for data manipulation, visualisation and analysis:
- [NumPy](https://numpy.org/doc/stable/index.html) 
- [Pandas](https://pandas.pydata.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/) 

**Overview of notebook contents:**
1. Overview of the Data 
    - The first section of the notebook contains an overview of the data contained in the Palmer Penguins data set. 
    - An interpretation of the types of variables within the data frame is included in this section. 
2. Exploratory Data Analysis
    - The second section of the notebook includes exploratory data analysis of the Palmer Penguins data, in order to get an overview of the data, to identify anomalies and ensure the data set has been loaded in correctly. 
    - Histograms of each the numeric variables in the data frame were made in order to visualise and explore the distribution of each of the variables. 
    - Bar charts and box plots were plotted to explore the differences in penguin attributes between species.
3. Correlations
    - The third section of the notebook contains an analysis of the correlations within the data set. 
    - Bivariate linear regression was used to explore the relationship between flipper length and body mass. 
    - A student's *t*-test was used to analyse the correlation between body mass and sex.  
