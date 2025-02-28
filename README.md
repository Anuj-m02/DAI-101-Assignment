# Laptop Price Analysis - Data Analysis & Visualization

## 🛠 Instructions
⚠️ **If this Python notebook does not open in GitHub or shows a rendering issue:**
- **Clone this repository** and open the `.ipynb` file in **Jupyter Notebook** on your personal laptop.
- **OR** use [nbviewer.org](https://nbviewer.org/) to view the notebook online.

## Project Overview
- Exploratory Data Analysis (EDA) on a laptop price dataset.
- Analyzes key attributes like price, RAM, CPU, GPU, weight, and screen size.
- Includes univariate, bivariate, and outlier detection techniques.

## Dataset
- **Numerical Features:** Inches, CPU Frequency (GHz), RAM (GB), Weight (kg), Price (Euro)
- **Categorical Features:** Company, TypeName, CPU Company, GPU Company, OpSys

## Workflow
### 1. Data Cleaning
- Handled missing and inconsistent values.
- Removed extreme outliers using Z-score (threshold = 3).

### 2. Univariate Analysis
- **Numerical Columns:** Distribution plots for price, weight, RAM, CPU frequency, etc.
- **Categorical Columns:** Count plots for company, type, CPU, and GPU manufacturers.

### 3. Outlier Detection & Handling
- Boxplots to detect extreme values.
- Removal of outliers using Z-score filtering.

### 4. Bivariate & Multivariate Analysis
- Correlation heatmap for numerical variables.
- Pairplots to explore feature interactions.
- Boxplots to show price distribution across different categories.

### 5. Additional Insights
- Price distribution by laptop brand.
- Top 10 most expensive laptops.
- CPU frequency vs. price (scatter plot).
- RAM vs. price distribution.
- GPU type vs. price (violin plot).
- Feature engineering: Created `Price_per_kg` metric.

## Results
- Detailed visualizations and insights into laptop price trends.
- Identifies key factors affecting laptop prices.

## Dependencies
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scipy`
