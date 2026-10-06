# Data Analysis with Python

Lab notebooks from the IBM **Data Analysis with Python** course on Coursera. The labs cover the full analysis workflow, from loading raw data to building and evaluating predictive models.

## What's Covered

### 1. Importing Datasets
- Loading CSV data into pandas DataFrames
- Inspecting data with `head()`, `info()`, `describe()`, and `dtypes`
- Saving datasets to different formats

### 2. Data Wrangling
- Identifying and handling missing values (dropping vs. replacing with mean or most frequent value)
- Correcting data types
- Data standardization and normalization
- Binning continuous variables
- Creating indicator (dummy) variables for categorical data

### 3. Exploratory Data Analysis (EDA)
- Descriptive statistics and value counts
- Grouping data with `groupby()` and pivot tables
- Visualizing relationships with scatter plots, box plots, regression plots, and heatmaps
- Correlation analysis using Pearson correlation and p-values

### 4. Model Development
- Simple and multiple linear regression
- Polynomial regression and pipelines
- Evaluating models visually with residual and distribution plots
- Measuring fit with R² and Mean Squared Error (MSE)

### 5. Model Evaluation and Refinement
- Train/test splitting
- Cross-validation
- Detecting overfitting and underfitting
- Ridge regression
- Hyperparameter tuning with Grid Search

### 6. Final Project
- End-to-end analysis and price prediction on a real-world housing dataset, applying all of the steps above

## Tools & Libraries

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- scikit-learn

## How to Run

1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Install the dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```
3. Open the notebooks:
   ```bash
   jupyter notebook
   ```

## Notes

The datasets used in these labs are provided by the course and are loaded from their source URLs inside the notebooks.
