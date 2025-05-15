# Iris Flower Dataset: Exploratory Data Analysis (EDA)

![Iris Flowers](https://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg)

A comprehensive exploratory data analysis of the classic Iris flower dataset, featuring statistical analysis, visualizations, and hypothesis testing.

## Dataset Description

The Iris dataset is one of the most well-known datasets in pattern recognition and machine learning. It contains measurements for 150 iris flowers from three species:

- **Setosa**
- **Versicolor**
- **Virginica**

For each flower, four features are recorded:
1. Sepal length (cm)
2. Sepal width (cm)
3. Petal length (cm)
4. Petal width (cm)

## Analysis Goals

Through this EDA, we aim to:
- Understand the basic structure of the Iris dataset
- Identify key features that differentiate species
- Create visualizations to summarize data insights
- Compute descriptive statistics (mean, distribution, etc.)
- Perform inferential statistical tests (t-tests, ANOVA)
- Detect and handle outliers and anomalies
- Explore feature relationships and correlations

## Key Findings

1. **Species Differentiation**:
   - Setosa is clearly distinguishable by petal measurements
   - Versicolor and Virginica show some overlap but can be separated by petal dimensions

2. **Feature Relationships**:
   - Strong positive correlation between petal length and width
   - Sepal length shows moderate correlation with petal dimensions

3. **Statistical Significance**:
   - ANOVA tests confirm significant differences between species across all features
   - Pairwise t-tests show all species pairs are statistically distinct

4. **Outliers**:
   - Few outliers detected in sepal width measurements
   - No extreme outliers that would require removal

## Methods & Techniques

### Data Exploration
- Data loading and initial inspection
- Handling missing values and duplicates
- Data type validation
- Column renaming for analysis

### Visual Analysis
- Box plots for feature distributions by species
- Scatter plots for feature relationships
- Pair plots for multivariate analysis
- Histograms for feature distributions

### Statistical Analysis
- Descriptive statistics (mean, median, std dev)
- Shapiro-Wilk test for normality
- Levene's test for homogeneity of variance
- One-way ANOVA for group differences
- Tukey's HSD for pairwise comparisons

### Data Quality
- Outlier detection using IQR method
- Missing value analysis
- Data type consistency checks

## Tools & Libraries

- **Python**: 3.x
- **Libraries**:
  - pandas (data manipulation)
  - numpy (numerical operations)
  - matplotlib (basic visualization)
  - seaborn (advanced visualization)
  - scipy (statistical tests)
  - statsmodels (ANOVA, Tukey HSD)

## How to Use This Notebook

1. **Prerequisites**:
   - Python environment with required libraries
   - Jupyter Notebook or Jupyter Lab

2. **Execution**:
   - Run cells sequentially
   - Modify visualization parameters as needed
   - Adjust statistical test parameters for different analyses

3. **Customization**:
   - Change color schemes in visualizations
   - Add additional statistical tests
   - Explore different feature combinations

4. **Output**:
   - All visualizations display inline
   - Statistical test results print below relevant cells
   - Key insights noted in markdown cells


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Ronald Fisher for the original Iris dataset
- scikit-learn team for maintaining dataset accessibility
- Open source community for developing the Python data science ecosystem
