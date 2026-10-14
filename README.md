# Wine Quality Analytics & Predictive Modelling

A comprehensive data analysis and statistical modeling project to identify the key chemical characteristics that drive wine quality, helping producers and exporters make informed decisions about product positioning and quality control.

## 📊 Project Overview

This analysis examines a combined dataset of **red and white wines** to understand the relationship between chemical properties and perceived quality. By leveraging statistical modeling and exploratory data analysis, this project provides evidence-based insights into which measurable attributes most strongly influence wine quality ratings.

### Dataset
- **Source**: winequality-combined.csv
- **Observations**: 6,497 wine samples (both red and white)
- **Key Variables**: 
  - Chemical properties: alcohol content, volatile acidity, citric acid, sulphates, pH, residual sugar, and more
  - Quality rating: Subjective quality score (0-10 scale)

## 🎯 Key Objectives

1. **Exploratory Analysis**: Understand the distribution and relationships between chemical properties and wine quality
2. **Statistical Modeling**: Develop regression models to quantify the impact of each chemical variable on quality
3. **Predictive Insights**: Generate predictions and actionable recommendations for winemakers and exporters

## 🔬 Methodology

### Data Preparation
- Combined red (0) and white (1) wine data for unified analysis
- Cleaned dataset: removed duplicates and verified data completeness
- Created readable wine labels for enhanced visualization

### Analysis Approach
- **Exploratory Data Analysis (EDA)**: Correlation analysis and distribution examination
- **Regression Modeling**: Simple and multiple linear regression to isolate the independent effects of each variable
- **Visualization**: Comprehensive charts and tables to illustrate relationships

## 📈 Key Predictors

The analysis focuses on four primary chemical characteristics:

1. **Alcohol** - % alcohol content by volume
2. **Volatile Acidity** - measure of wine's acidity and flavor
3. **Citric Acid** - contributes to freshness and flavor
4. **Sulphates** - wine preservative and antioxidant

These variables were selected based on their strong correlation with wine quality and their practical relevance to production decisions.

## 🔑 Key Findings

- **Alcohol Content** shows the strongest relationship with perceived quality
- The correlation matrix reveals simple relationships between variables and quality
- **Regression analysis** is essential to understand independent variable contributions while holding others constant
- Chemical properties explain a significant portion of quality variation, providing actionable insights for producers

## 📖 Full Analysis Report

The complete analysis with detailed visualizations, statistical tables, and in-depth modeling results is available in the interactive HTML report:

**[View Full Report - Report_Template.html](Report_Template.html)**

The report includes:
- Detailed exploratory data analysis with visualizations
- Correlation matrices and heatmaps
- Linear regression results and model diagnostics
- Predictive modeling outcomes
- Industry recommendations and implications

## 🛠️ Technologies Used

- **Python 3** - Data processing and analysis
- **Pandas** - Data manipulation and cleaning
- **Statsmodels** - Statistical modeling and regression analysis
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive analysis and reporting

## 💡 Use Cases

This analysis is valuable for:
- **Wine Producers**: Optimizing production methods to achieve desired quality characteristics
- **Exporters**: Understanding quality drivers for international market positioning
- **Quality Control Teams**: Setting production standards based on chemical property targets
- **Data Scientists**: Reference for regression modeling and exploratory analysis workflows

## 📝 Report Structure

1. **Introduction** - Project overview and objectives
2. **Data Overview** - Dataset description and preparation
3. **Analysis** - Exploratory analysis and correlation examination
4. **Modelling** - Regression analysis and predictive modeling
5. **Conclusions** - Key findings and real-world implications

---

**Project Date**: 2026  
**Author**: Vlad Riabokon  
**Contact**: vriabokon23@gmail.com
