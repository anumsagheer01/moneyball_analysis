## Moneyball Analysis: Evaluating MLB Team Spending Efficiency

### Project Overview

This project analyzes the relationship between team spending and performance in Major League Baseball (MLB) from 1990 to 2014. Using data from the Lahman Baseball Database, the analysis seeks to evaluate how efficient teams were in converting payroll into wins, with a particular focus on the Oakland Athletics and their "Moneyball" era strategy. The project explores trends, performs data transformations, and visualizes insights into team performance and spending efficiency.

### Objectives

1. **Data Wrangling and Exploration**:
   - Combine salary and team performance data.
   - Address missing data and ensure clean, usable datasets.

2. **Exploratory Data Analysis (EDA)**:
   - Examine payroll distribution trends over time.
   - Analyze the correlation between team payroll and winning percentage.

3. **Data Transformation**:
   - Standardize payroll across years to compare spending efficiency.
   - Derive new metrics, such as spending efficiency and expected wins.

4. **Visualization and Insights**:
   - Highlight team trends using scatter plots and regression lines.
   - Focus on the Oakland A's efficiency during their Moneyball period (2000–2005).


### Data Sources

- **Lahman Baseball Database**: A comprehensive database of MLB statistics. Available on [GitHub](https://github.com/jknecht/baseball-archive-sqlite).
- **SQLite**: Used to query and analyze data from the database.
- **Pandas**: To load SQL query results into DataFrames for analysis.

### Methodology

#### 1. Data Wrangling
- Extracted payroll and team performance data using SQL queries.
- Calculated key metrics, including total payroll and winning percentage.
- Addressed missing values and ensured appropriate joins for clean data integration.

#### 2. Exploratory Data Analysis
- **Payroll Distribution**:
  - Created time-series plots of payroll distribution from 1990 to 2014.
  - Analyzed trends in payroll central tendency and spread over time.

- **Correlation Between Payroll and Winning Percentage**:
  - Divided data into five-year intervals.
  - Produced scatter plots for each interval, examining the relationship between payroll and wins.

#### 3. Data Transformations
- Standardized payrolls by year to allow for cross-year comparisons.
- Derived expected winning percentages using regression analysis.
- Computed spending efficiency as a measure of team performance relative to payroll.

#### 4. Visualization
- Plotted trends in spending efficiency for key teams:
  - Oakland A's (OAK), New York Yankees (NYA), Boston Red Sox (BOS), Atlanta Braves (ATL), and Tampa Bay Rays (TBA).
- Added regression lines and labels for better interpretability.

### Key Insights

- **Payroll Trends**: High-spending teams (e.g., Yankees) consistently maintained top payrolls, while smaller teams (e.g., Athletics) operated on tighter budgets.
- **Moneyball Success**: The Oakland A's demonstrated significantly higher efficiency during the Moneyball era, outperforming other teams with similar payrolls.
- **Spending Efficiency**: Teams like Oakland and Tampa Bay proved adept at maximizing wins relative to their spending, while others showed inefficiencies.

### Technologies Used

- **Python Libraries**: pandas, sqlite3, matplotlib, seaborn
- **Database**: SQLite
- **Jupyter Notebook**: For analysis, visualization, and documentation.


