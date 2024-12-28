# GDP to Life Expectancy Analysis

## Overview
This project explores the relationship between GDP and life expectancy across different countries and years. The primary objective is to determine whether higher GDP correlates with better living standards or whether historical development plays a more significant role in predicting life expectancy.

## Dataset
The analysis uses data from a CSV file containing the following columns:
- `Country`: The name of the country.
- `Year`: The year of the observation.
- `Life expectancy at birth (years)`: The average life expectancy at birth in years.
- `GDP`: The Gross Domestic Product of the country.

## Tools and Libraries
The following Python libraries are used in the analysis:
- `pandas`: For data manipulation and cleaning.
- `numpy`: For numerical computations.
- `matplotlib` and `seaborn`: For data visualization.
- `statsmodels`: For statistical modeling and hypothesis testing.

## Key Features of the Analysis
1. **Data Preprocessing**:
   - Reads the CSV file into a Pandas DataFrame.
   - Handles missing or erroneous data, if any.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualizes trends in life expectancy and GDP over time for various countries.
   - Examines correlations between GDP and life expectancy.

3. **Statistical Modeling**:
   - Builds regression models using `statsmodels` to evaluate the impact of GDP and temporal factors on life expectancy.
   - Filters out variables with p-values greater than 0.05 to retain only statistically significant predictors.

4. **Visualization**:
   - Creates scatter plots, line graphs, and residual plots to understand the relationships and model performance.

## How to Run the Project
1. Clone or download the repository containing this notebook.
2. Ensure the following Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels
   ```
3. Place the dataset (`all_data.csv`) in the specified directory.
4. Run the Jupyter Notebook (`GDP_life-expectancy.ipynb`) using the following command:
   ```bash
   jupyter notebook GDP_life-expectancy.ipynb
   ```
5. Follow the steps in the notebook to reproduce the analysis.

## Results
The analysis highlights key factors that influence life expectancy, providing insights into:
- The extent to which GDP impacts life expectancy.
- Variations in life expectancy trends over time and across countries.

## Contact
For questions or feedback, please reach out via email or open an issue in the repository.
