# README for US House Prices Prediction Model

## Overview

This repository contains a data science model that aims to explain US house prices over the last 20 years (2002-2022). The model considers various economic and financial indicators, such as mortgage rates, GDP growth rate, unemployment rate, median household income, population growth rate, and inflation growth rate.

## Data Preparation

### Data Sources

The data used in this analysis comes from publicly available sources:

1. [House Prices](https://fred.stlouisfed.org/series/CSUSHPISA)
2. [30-Year Mortgage Rate](https://fred.stlouisfed.org/series/MORTGAGE30US)
3. [15-Year Mortgage Rate](https://fred.stlouisfed.org/series/MORTGAGE15US)
4. [GDP Growth Rate](https://fred.stlouisfed.org/series/A191RL1Q225SBEA)
5. [Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE)
6. [Median Household Income](https://fred.stlouisfed.org/series/MEHOINUSA672N)
7. [Population Growth Rate](https://www.macrotrends.net/countries/USA/united-states/population-growth-rate)
8. [Inflation Growth Rate](https://www.macrotrends.net/countries/USA/united-states/inflation-rate-cpi)

### Data Processing

The data was processed and transformed using Python with the help of pandas, numpy, and matplotlib libraries. Monthly data was interpolated, missing values were handled appropriately, and relevant features were selected for analysis.

## Exploratory Data Analysis (EDA)

Visualizations were created to explore the trends and relationships between house prices and various economic indicators. A correlation matrix was generated to quantify the relationships between different features.

## Model Building

The model is built using a Linear Regression algorithm and Random Forest Regressor. Features include historical house prices, mortgage rates, economic indicators, and lagged variables. Feature engineering techniques were applied, and the model was trained on a subset of the data, with predictions evaluated using mean squared error.

## Feature Engineering

Additional features were engineered to enhance the model's predictive power. These include lagged variables, moving averages, and time since the last peak in house prices. Seasonal flags were also created to capture potential seasonality effects.

## Model Evaluation

The model's performance was evaluated using mean squared error, providing insights into its predictive accuracy. Feature importances were analyzed to understand the relative impact of each variable on predicting house prices.

## Results and Insights

The model provides insights into the factors influencing US house prices. Key findings include:

- Positive impact factors: Population growth rate, mortgage rate momentum, historical house prices, and socioeconomic indicators.
- Negative impact factors: Interest rate headwind, unemployment rate, and economic contraction effects.

## Usage

To use this model for predictions, follow these steps:

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd [project_directory]`
3. Ensure you have the required dependencies installed: `pip install -r requirements.txt`
4. Run the Jupyter notebook or Python script to train and evaluate the model.

## Conclusion

This model provides a foundation for understanding the dynamics of the US housing market over the last two decades. Further refinement and parameter tuning can enhance its accuracy and predictive capabilities.

## Contributors

- Somansh Achary

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the data sources and libraries used in this analysis. Any citations or references are included in the bibliography section of this README.
