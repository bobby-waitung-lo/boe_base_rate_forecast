# boe_base_rate_forecast
This repository contains a Jupyter notebook that predicts the Bank of England’s Base Rate for 2025 using polynomial regression, showcasing advanced data science and analytical skills. The project leverages data from the February 2025 Monetary Policy Report to forecast a potential rate cut to 4.25% by May 2025.

## Project Overview
The notebook models and predicts the Bank of England’s Base Rate decisions, a critical factor influencing the UK economy. By analyzing quarterly rate data from Overnight Index Swap (OIS) rates, the project employs polynomial regression to generate daily predictions, focusing on Monetary Policy Committee (MPC) meeting dates in 2025. Key outputs include a robust model with an adjusted R-squared of 0.969 and visualizations of predicted rates.

This project demonstrates proficiency in:
- **Data Processing**: Cleaning and transforming time-series data using Pandas.
- **Machine Learning**: Implementing polynomial regression with scikit-learn and model selection via adjusted R-squared.
- **Data Visualization**: Creating insightful plots with Matplotlib to communicate findings.
- **Economic Analysis**: Interpreting monetary policy data to derive actionable insights.

## Key Features
- **Data Preparation**: Processes quarterly rate data into a numerical format for modeling, handling date conversions and time-series calculations.
- **Model Development**: Tests polynomial models (degrees 1–5) and selects the best fit (degree 4) based on adjusted R-squared to balance accuracy and complexity.
- **Prediction Generation**: Produces daily rate predictions, rounded to 0.25% increments, reflecting practical Bank Rate adjustments.
- **Visualization**: Plots quarterly data, continuous predictions, and adjusted predictions for clear interpretation.
- **MPC Focus**: Extracts predicted rates for specific 2025 MPC meetings (e.g., May 8: 4.25%).

## Skills Showcased
- **Programming**: Python (Pandas, NumPy, scikit-learn, Matplotlib) for data manipulation, modeling, and visualization.
- **Data Science**: Time-series analysis, regression modeling, model evaluation, and feature engineering.
- **Analytical Thinking**: Translating economic data into predictive insights with real-world relevance.
- **Communication**: Clear documentation and visualizations to convey complex findings to technical and non-technical audiences.

## Repository Structure
`boe_base_rate_forecast.ipynb`: The main Jupyter notebook containing the analysis, code, and visualizations.
`README.md`: This file, providing an overview and guide to the project.

### Getting Started
Prerequisites
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`
- Install dependencies: `pip install pandas numpy matplotlib scikit-learn`

### Running the Notebook
1. Clone the repository: `git clone https://github.com/bobby-waitung-lo/boe_base_rate_forecast.git`
2. Navigate to the directory: `cd boe_base_rate_forecast`
3. Launch Jupyter: `jupyter notebook boe_base_rate_forecast.ipynb`
4. Run the cells to explore the analysis and visualizations.

## Results
The model predicts a gradual decline in the Bank Rate, with a key forecast of 4.25% for the May 8, 2025, MPC meeting. The high adjusted R-squared (0.969) indicates strong model fit, while visualizations provide clear insights into rate trends, making this project a valuable tool for understanding UK monetary policy.

## Why This Matters for My Portfolio
This project highlights my ability to:
- Tackle real-world economic problems using data science techniques.
- Build and evaluate predictive models with rigor and precision.
- Communicate actionable insights through code, visualizations, and documentation.
- Bridge technical skills with domain knowledge in economics and finance.
It’s a strong example of my qualifications for data science and analyst roles, showcasing both technical expertise and the ability to deliver impactful results.

## Contact
Feel free to reach out for questions or collaboration:
- GitHub: [bobby-waitung-lo](https://github.com/bobby-waitung-lo)
- LinkedIn: [Bobby Lo](https://www.linkedin.com/in/bobby-waitung-lo)
- Medium: [Bobby Lo](https://medium.com/@bobbylo/will-the-bank-of-england-cut-rates-in-2025-a-data-driven-forecast-may-2025-c8d10ef3e9c4)

Explore the notebook to see how data science can unlock insights into monetary policy and economic trends!
