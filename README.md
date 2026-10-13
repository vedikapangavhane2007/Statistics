# Statistics and Data Analysis – Units I–V

This repository contains Jupyter Notebook assignments and practical examples covering key topics in statistics and exploratory data analysis.

## Repository Contents

| Notebook | Topics Covered |
|---|---|
| `Unit1.ipynb` | **Introduction to Statistics** — descriptive and inferential statistics, sampling techniques, correlation, regression, data types, and case studies involving student marks and employee data. |
| `Unit2.ipynb` | **Descriptive Statistics** — mean, median, mode, variance, standard deviation, range, interquartile range (IQR), outlier detection, skewness, kurtosis, visualizations, and examples from five industry domains. |
| `Unit3.ipynb` | **Inferential Statistics** — normal and standard normal distributions, Student’s t-distribution, and confidence intervals for population means and proportions. |
| `Unit4.ipynb` | **Hypothesis Testing** — proportion tests, one-sample mean tests (left-tailed and two-tailed), one-way ANOVA, and chi-square tests of independence. |
| `Unit5.ipynb` | **Exploratory Data Analysis (EDA)** — loading and understanding data, descriptive summaries, missing-value handling, feature engineering and selection, visualizations, correlation analysis, and domain-based EDA examples. |

## Technologies and Libraries

The notebooks use Python and commonly used data-analysis libraries, including:

- **NumPy** — numerical operations and array handling
- **Pandas** — data manipulation and analysis
- **Matplotlib** — plotting and visualization
- **Seaborn** — statistical visualizations
- **SciPy** (`scipy.stats`) — statistical distributions and tests
- **Statsmodels** — proportion hypothesis testing

## Getting Started

### Option 1: Open in Google Colab

1. Open the repository on GitHub.
2. Open a notebook, such as `Unit1.ipynb`.
3. Select **Open in Colab** if available, or upload/download the notebook into [Google Colab](https://colab.research.google.com/).
4. Run the cells in order.

### Option 2: Run Locally with Jupyter Notebook

1. Install Python 3 if it is not already installed.
2. Clone the repository:

   ```bash
   git clone https://github.com/vedikapangavhane2007/Statistics.git
   cd Statistics
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scipy statsmodels jupyter
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open any `Unit*.ipynb` notebook and run the cells from top to bottom.

> **Note:** Unit 5 loads the Titanic sample dataset using Seaborn. Depending on your environment, downloading this dataset may require an internet connection the first time it is loaded.

## Learning Outcomes

By working through these notebooks, you can practise how to:

- Summarize data using descriptive statistics.
- Understand distributions, variability, skewness, and kurtosis.
- Explore relationships between variables using correlation and regression.
- Estimate population parameters with confidence intervals.
- Conduct hypothesis tests and interpret p-values.
- Clean and explore data, engineer basic features, and communicate findings with plots.

## Notes

- Some notebooks use generated or illustrative sample data, so results may differ if the data-generation code or random seed is changed.
- The examples are intended for learning and practice; statistical conclusions depend on the assumptions and data used in each example.
- Run the notebooks sequentially to view calculations, outputs, and visualizations.

## Author

[vedikapangavhane2007](https://github.com/vedikapangavhane2007)
pritigaikwad274


## License

No license has been specified yet. Add a license file if you want to define how others may use, modify, or distribute this repository.
