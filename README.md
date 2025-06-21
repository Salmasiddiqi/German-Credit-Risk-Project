# German Credit Risk Analysis

This project performs data analysis and visualization on the **German Credit Risk** dataset from Kaggle.

---

## Dataset

The dataset contains information about credit applicants and whether they are considered good or bad credit risks.

- Source: [Kaggle - German Credit Data](https://www.kaggle.com/datasets/uciml/german-credit)
- Features include Age, Sex, Job, Housing, Saving accounts, Checking account, Credit amount, Duration, Purpose, etc.

---

## Project Overview

- Load and clean the dataset (handle missing values and data types).
- Perform exploratory data analysis (EDA) with charts and graphs.
- Analyze credit risk factors.
- Prepare the data for potential modeling (optional).
- Visualizations created using Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## Data Visualizations and Insights

The project includes several charts to explore and understand the German Credit dataset:

- **Age Distribution**: Distribution of applicants’ ages, highlighting common age groups.
- **Credit Amount by Purpose**: Bar chart showing credit amount differences by loan purpose.
- **Housing Status Breakdown**: Pie chart showing proportions of housing types (own, rent, etc.).
- **Saving Accounts and Checking Accounts Status**: Count plots revealing the distribution and missing data.
- **Credit Duration**: Histogram showing loan durations in months.
- **Credit Risk by Job Type**: Bar plot comparing credit risk status across job categories.
- **Correlation Heatmap**: Heatmap showing relationships between numerical features.

These visualizations help identify key patterns related to credit risk assessment.

---

## How to Use

1. Download the dataset from Kaggle using the link above.
2. Open the notebook (`your_notebook.ipynb`) in Jupyter Notebook or Google Colab.
3. Run all cells sequentially to reproduce the analysis and visualizations.

---

## Requirements

- Python 3.x  
- pandas  
- matplotlib  
- seaborn  

Install dependencies with:

```bash
pip install pandas matplotlib seaborn
