# Iris Flower Dataset Exploratory Data Analysis (EDA)

**Overview**

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Iris Flower Dataset, one of the most famous datasets in pattern recognition and machine learning. The analysis walks through all key steps in understanding the structure, distribution, and statistical relationships within the data.

*It includes:*

- Data loading and inspection
- Data cleaning and preprocessing 
- Visual exploration
- Descriptive statistical analysis
- Inferential statistical analysis

The purpose of this project is to demonstrate data exploration and statistical analysis skills in Python using standard data science libraries.

---

## Dataset Information

The Iris dataset contains 150 observations of iris flowers from three different species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica


Each flower sample has the following features (in cm):

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Objectives

- Understand the structure and contents of the Iris dataset.
- Perform visual exploration to identify trends and patterns.
- Generate descriptive statistics to summarize the data.
- Conduct inferential statistical analysis to evaluate relationships and differences between species.

---

## Project Structure
```
iris-eda/
│
├── iris_eda_analysis.ipynb         # Main Jupyter Notebook containing the analysis
├── README.md                       # Project README file
├── dataset/
│   └── iris.csv                    # Iris dataset (optional, if not using seaborn or sklearn's built-in)
├── images/
│   └── *.png                       # Visualizations and charts
└── requirements.txt                # Python dependencies
```
---

## Key Analysis Steps

#### 1. Data Loading & Preliminary Exploration

- Previewed the first few rows.
- Checked dataset shape and column types.
- Verified presence of null/missing values.
- Checked class distribution (number of samples per species).


#### 2. Descriptive Statistics

- Measures of central tendency (mean, median, mode).
- Measures of dispersion (variance, standard deviation, IQR).
- Distribution plots (histograms, boxplots).


#### 3. Visual Exploration

- Pairplots to examine relationships between variables.
- Heatmap to visualize correlation between features.
- Species-wise comparison using violin plots and swarm plots.
-Scatter plots and regplots to visualize trends.


#### 4. Inferential Statistics

- ANOVA (Analysis of Variance) to test for significant differences in means across species.
- T-tests for pairwise comparison (Setosa vs Versicolor, etc.).
- Hypothesis testing and interpretation of p-values.


