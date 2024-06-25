# Corruption Index Regression Analysis 📊

This project conducted in RStudio explores the relationship between corruption and various economic indicators using regression analysis. The primary goal is to understand how annual income, cost of living, and tourism impact the corruption index across different countries.

## Project Overview

The analysis involves:
- Loading and cleaning a dataset containing corruption indices and economic indicators for various countries.
- Visualizing the relationships between the corruption index and other variables such as annual income, cost index, and tourist count.
- Performing regression analyses to identify significant predictors of corruption.
- Comparing models with different combinations of predictors.
- Checking for heteroskedasticity and interpreting the results.

## Data Source

The data used in this analysis was extracted from [WorldData](https://www.worlddata.info/).

## Key Findings

- **Annual Income:** There is a negative correlation between annual income and corruption index. Higher income tends to be associated with lower corruption.
- **Cost Index:** Countries with higher cost indices tend to have lower corruption indices.
- **Tourism:** Tourist count as a percentage of population does not show a significant impact on the corruption index.

## Files 📂

- `Corruption_Data_Analysis.Rmd`: The main R Markdown file containing the full analysis.
- `corruption_index_clean_data.xlsx`: The dataset used for the analysis.

## Getting Started

To replicate the analysis:
1. Clone this repository.
2. Open the `Corruption_Data_Analysis.Rmd` file in RStudio.
3. Ensure you have the required packages installed.
4. Run the R Markdown file to see the analysis and results.

## Conclusion

The analysis reveals significant relationships between corruption and economic indicators like annual income and cost index. Future research could benefit from including additional variables such as political stability and safety measures.

---

Feel free to explore the `Corruption_Data_Analysis.Rmd` file for detailed code and insights.
