# Data-Visualization-Protein-Expression
A Python-based visualization code for exploring and interpreting protein expression data - includes clear, customizable plots and statistical observations to support comparative analysis and biological insight.

# Concepts Covered:

## Data Loading and Initial Exploration: 
Loading data from an Excel file, checking its shape, data types, and identifying missing values.

## Data Preprocessing: 
Handling missing numerical values by filling with the mean, normalizing protein expression values using StandardScaler, and encoding categorical Subtype information using LabelEncoder.

## Descriptive Statistics: 
Computing summary statistics (mean, median, standard deviation) for protein expression.

## Variability Analysis: 
Identifying the most variable proteins across samples.

## Correlation Analysis: 
Visualizing correlations between proteins using heatmaps.

## Subtype-wise Analysis: 
Grouping data by breast cancer subtype to find patterns in protein expression and visualize subtype distribution.

## Statistical Hypothesis Testing: 
Performing ANOVA (f_oneway) to compare protein expression across multiple subtypes and T-tests (ttest_ind) to compare protein expression between two specific subtypes.

## Data Visualization: 
Creating various plots such as countplots, boxplots, heatmaps, and bar plots to visualize distributions, mean expressions, and compare groups. It also includes an example of an interactive plot using Plotly.

## Biological Interpretation:
Providing insights and potential biological relevance of the statistical findings.

# Key Python Packages Used:

pandas: For data manipulation and analysis (e.g., DataFrames, reading data, grouping, calculating statistics).
numpy: For numerical operations, especially with arrays.
sklearn.preprocessing: For data scaling (StandardScaler) and encoding categorical features (LabelEncoder).
seaborn: For creating informative and attractive statistical graphics (e.g., heatmaps, countplots, boxplots, bar plots).
matplotlib.pyplot: For creating static, interactive, and animated visualizations in Python (used in conjunction with seaborn).
scipy.stats: For statistical tests like ANOVA (f_oneway) and T-tests (ttest_ind).
plotly.express: For creating interactive visualizations.
