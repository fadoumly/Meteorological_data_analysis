# Meteorological Analysis of the Creuse and Isère Departments

# Description
This project analyzes meteorological data for the Creuse and Isère departments in France. The primary objective is to explore humidity measurements, meteorological station altitudes, and precipitation by season and month. The results include descriptive statistics and graphical visualizations that help examine hypotheses about climate variations between these two departments.

# Project Contents
Meteorological Data : Data is contained in a CSV file (meteo.csv) that includes measurements for humidity, altitude, and precipitation from different meteorological stations.
R Markdown Script : The file weather_data_analysis.Rmd contains the code for data analysis and generates a report in HTML format (weather_data_analysis.nb.html) presenting the analysis results.

Analyses Conducted Descriptive Statistics
Number of humidity measurements for each department.
Calculation of average humidity and standard deviation for each department and season.
Comparison of Creuse and Isère data using statistical tests (Wilcoxon test for latitude, etc.).

Visualizations
Boxplots of meteorological station latitudes to compare Creuse and Isère.
Histograms and QQ-plots to assess data normality.

Statistical Tests
Wilcoxon test to assess latitude differences between departments.
Regression analysis to determine the effect of month on precipitation.
Usage Instructions Installation of R Packages: Ensure that necessary packages, particularly ggplot2 for visualization, are installed.

Conclusion : 
This project provides a deeper understanding of climate variations in the Creuse and Isère departments, and the results may be useful for future studies or data-based climate-related decision-making.
